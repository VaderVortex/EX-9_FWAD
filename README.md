# Ex.09: Event Registration Web Application
# Date:
# AIM:
To design, develop and deploy a web application for event registration.

# DESIGN STEPS:
## Step 1:
Create a new frame.

## Step 2:
Select any one preset size of your choice.

## Step 3:
Select the shapes you need.

## Step 4:
Import images as needed.

## Step 5:
Create pages based on your need and link them.

## Step 6:
Validate the HTML and CSS code.

## Step 6:
Publish the website in the given URL.

# DESIGN TOOL:
Figma

# CODE:

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8" />
      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
      <title>Sports Event App</title>
      <style>
        * { box-sizing: border-box; }
        body {
          font-family: 'Poppins', sans-serif;
          margin: 0;
          padding: 0;
          background: linear-gradient(to bottom right, #e0f7ff, #fff0f5);
        }
        .screen {
          width: 390px;
          margin: 40px auto;
          border: 2px solid #ccc;
          border-radius: 20px;
          padding: 20px;
          background: white;
        }
        h1, h2 {
          text-align: center;
          color: #004aad;
        }
        button {
          display: block;
          width: 80%;
          margin: 10px auto;
          padding: 10px;
          font-size: 18px;
          background: red;
          color: white;
          border: none;
          border-radius: 8px;
          box-shadow: 0 4px 6px rgba(0,0,0,0.2);
          cursor: pointer;
        }
        ul {
          list-style-type: none;
          padding: 0;
        }
        ul li {
          padding: 10px;
          text-align: center;
          font-weight: bold;
          border-bottom: 1px solid #ccc;
        }
        form input {
          display: block;
          width: 100%;
          margin-bottom: 10px;
          padding: 10px;
          border: 1px solid #ccc;
          border-radius: 6px;
        }
        .thank-you {
          text-align: center;
          padding: 30px;
        }
        .contact {
          font-size: 14px;
          text-align: center;
          color: green;
          margin-top: 20px;
        }
      </style>
    </head>
    <body>
    
      <!-- Home Page -->
      <div class="screen">
        <h1>SPORTS DAY EVENTS</h1>
        <img src="logo.png" alt="College Logo" style="display:block;margin:auto;width:80px;">
        <button>LOGIN</button>
        <button>REGISTER</button>
        <p style="text-align:center;font-weight:bold;color:#ff6600">"BORN TO WIN"</p>
      </div>
    
      <!-- Events Page -->
      <div class="screen">
        <h2>SPORTS DAY EVENTS</h2>
        <ul>
          <li>🏏 Cricket</li>
          <li>🏸 Badminton</li>
          <li>🏐 Volley Ball</li>
          <li>🏃‍♂️ 100 Mts</li>
          <li>🏃‍♀️ 200 Mts</li>
          <li>🏃 400 Mts</li>
          <li>🎽 4×100 Relay</li>
        </ul>
      </div>
    
      <!-- Event Registration Page -->
      <div class="screen">
        <h2>EVENT REGISTRATION FORM</h2>
        <form>
          <input type="text" placeholder="Full Name">
          <input type="text" placeholder="Gender">
          <input type="number" placeholder="Age">
          <input type="text" placeholder="Register Number">
          <input type="text" placeholder="Department">
          <input type="text" placeholder="Mobile Number">
          <input type="email" placeholder="Email ID">
          <input type="text" placeholder="Events to Register">
          <button type="submit">REGISTER</button>
        </form>
      </div>
    
      <!-- Thank You Page -->
      <div class="screen">
        <h2>THANK YOU</h2>
        <div class="thank-you">
          <p>We are all eagerly waiting<br>for your participation in the sports events!</p>
        </div>
        <div class="contact">
          <p><strong>Contact us</strong></p>
          <p>Email: saveethaengineeringcollege@gmail.com</p>
          <p>Phone: 6369183394</p>
        </div>
      </div>
    
    </body>
    </html>

# OUTPUT:

![image](https://github.com/user-attachments/assets/12a81d3c-7384-49fe-8907-85f2bd7b9367)
![image](https://github.com/user-attachments/assets/255a1b81-6897-4c10-bde2-a415521d715b)


# RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.

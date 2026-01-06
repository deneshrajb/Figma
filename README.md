# Ex08 Event Registration Web Application
## Date: 6/1/2026

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Event Registration</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
        }

        .container {
            width: 100%;
            max-width: 900px;
            margin: auto;
            background-color: white;
            box-shadow: 0 0 10px #aaa;
        }

        /* Header */
        header {
            background-color: #4a148c;
            color: white;
            padding: 30px;
            text-align: center;
        }

        /* Event section */
        .event-info {
            padding: 30px;
            text-align: center;
        }

        .event-info h2 {
            color: #4a148c;
        }

        .event-info p {
            font-size: 16px;
        }

        /* Registration Form */
        .form-section {
            background-color: #f9f9f9;
            padding: 30px;
        }

        form {
            max-width: 500px;
            margin: auto;
        }

        label {
            display: block;
            margin-top: 15px;
            font-weight: bold;
        }

        input, select {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
        }

        button {
            margin-top: 20px;
            width: 100%;
            padding: 12px;
            background-color: #4a148c;
            color: white;
            border: none;
            font-size: 16px;
            cursor: pointer;
        }

        button:hover {
            background-color: #6a1b9a;
        }

        footer {
            text-align: center;
            padding: 15px;
            background-color: #333;
            color: white;
        }
    </style>
</head>
<body>

<div class="container">

    <header>
        <h1>Tech Fest 2026</h1>
        <p>Register now to be part of an exciting event</p>
    </header>

    <section class="event-info">
        <h2>Event Details</h2>
        <p><strong>Date:</strong> 20 March 2026</p>
        <p><strong>Venue:</strong> Chennai</p>
        <p><strong>Time:</strong> 10:00 AM – 4:00 PM</p>
    </section>

    <section class="form-section">
        <h2 style="text-align:center; color:#4a148c;">Event Registration</h2>

        <form>
            <label>Full Name</label>
            <input type="text" placeholder="Enter your name" required>

            <label>Email Address</label>
            <input type="email" placeholder="Enter your email" required>

            <label>Phone Number</label>
            <input type="tel" placeholder="Enter your phone number" required>

            <label>Event Category</label>
            <select>
                <option>Workshop</option>
                <option>Seminar</option>
                <option>Competition</option>
            </select>

            <button type="submit">Register</button>
        </form>
    </section>

    <footer>
        <p>© 2026 Event Registration Portal</p>
    </footer>

</div>

</body>
</html>
```

## OUTPUT:
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/9fcf731f-4410-4ff5-9b1c-b911d970f315" />

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.

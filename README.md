# Ex.06 Book Front Cover Page Design
## Date:15/12/2025
## NAME: DHANADEVAN REG NO:25013996

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Book Front Cover</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #e0e0e0;
            font-family: 'Georgia', serif;
        }

        .book-cover {
            width: 350px;
            height: 500px;
            background: linear-gradient(135deg, #2c3e50, #4ca1af);
            color: white;
            padding: 20px;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.4);
            position: relative;
            border-radius: 6px;
            box-sizing: border-box;
        }

        .title {
            font-size: 28px;
            font-weight: bold;
            text-align: center;
            margin-top: 20px;
            letter-spacing: 2px;
        }

        .decor-line {
            width: 80px;
            height: 4px;
            background: white;
            margin: 20px auto;
            border-radius: 2px;
        }

        .center-image {
            width: 100%;
            height: 160px;
            object-fit: cover;
            border-radius: 4px;
            margin-top: 10px;
        }

        .subtitle {
            font-size: 15px;
            text-align: center;
            margin-top: 15px;
            font-style: italic;
            opacity: 0.9;
        }

        .author {
            position: absolute;
            bottom: 30px;
            width: 100%;
            text-align: center;
            font-size: 17px;
            letter-spacing: 1px;
        }
    </style>
</head>
<body>

    <div class="book-cover">

        <!-- Book Title -->
        <div class="title">THE ART OF CODE</div>

        <div class="decor-line"></div>

        <!-- Center Image -->
        <img src="center-image.jpg" alt="Center Image" class="center-image">

        <!-- Subtitle -->
        <div class="subtitle">A Journey into Web Development</div>

        <!-- Author Name -->
        <div class="author">By Dhana</div>
    </div>

</body>
</html>
~~~

## OUTPUT:
<img width="1918" height="967" alt="image" src="https://github.com/user-attachments/assets/37c2ea73-84fa-4a7f-bb7a-06c0edf315ab" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

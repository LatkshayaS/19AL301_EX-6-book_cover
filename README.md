# Ex.06 Book Front Cover Page Design
# Date:21.12.2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Book Front Cover</title>

<style>
    body {
        background-color: #eaeaea;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        font-family: 'Arial', sans-serif;
    }

    .book {
        width: 320px;
        height: 480px;
        background: linear-gradient(135deg, #1e3c72, #2a5298);
        color: white;
        padding: 30px;
        box-shadow: 0 10px 25px rgba(0,0,0,0.3);
        border-radius: 8px;
        position: relative;
    }

    .title {
        font-size: 30px;
        font-weight: bold;
        text-align: center;
        margin-top: 80px;
        letter-spacing: 2px;
    }

    .subtitle {
        font-size: 16px;
        text-align: center;
        margin-top: 15px;
        opacity: 0.9;
    }

    .author {
        position: absolute;
        bottom: 80px;
        width: 100%;
        text-align: center;
        font-size: 18px;
    }

    .footer {
        position: absolute;
        bottom: 30px;
        width: 100%;
        text-align: center;
        font-size: 12px;
        opacity: 0.8;
    }

    .circle {
        width: 120px;
        height: 120px;
        border-radius: 50%;
        background-color: rgba(255,255,255,0.2);
        position: absolute;
        top: 20px;
        right: 20px;
    }
</style>

</head>
<body>

<div class="book">
    <div class="circle"></div>

    <div class="title">NEVER GIVE UP</div>
    <div class="subtitle">A Journey of Strength & Hope</div>

    <div class="author">By Latkshaya S</div>
    <div class="footer">First Edition • 2025</div>
</div>

</body>
</html>
```
# OUTPUT:![}(BOOK COVER.png)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

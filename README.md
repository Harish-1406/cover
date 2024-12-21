# Ex.06 Book Front Cover Page Design
## Date:21.12.2024

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
```
cover.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #f0f0f0;
        }

        .background-container {
            width: 210mm;
            height: 297mm;
            background-color: #fff;
            background-image: url('https://i.pinimg.com/originals/f1/2d/37/f12d37a112f8badeec0b4fbc1e109b80.jpg');
            background-repeat: no-repeat;
            background-position: center;
            background-size: cover;
            position: relative;
            padding: 20px;
            border: 2px solid #333;
        }

        .text-container {
            position: absolute;
            top: 5%; 
            left: 5%;
            color: #333;
            z-index: 10;
            font-size: 18px;
            line-height: 1.4;
            width: 60%; 
        }

        .expert-insight {
            font-size: 36px;
            font-weight: bold;
            color: #333;
            font-family: 'Georgia', serif;
            margin-bottom: 10px;
        }

        .book-title {
            font-size: 40px;
            font-weight: bold;
            line-height: 1.3;
        }

        .subtitle {
            font-size: 25px;
            font-style: italic;
            font-weight: 300;
            color: #6a6a6a;
            margin-top: 10px;
        }

        .author-name {
            font-size: 28px;
            font-weight: 100;
        }

        .line {
            width: 50%; 
            border-top: 3px solid #000; 
            margin-top: 10px;
        }

        .image-container {
            position: absolute;
            bottom: 12%;
            right: 5%;
        }

        .image-container img {
            width: 130px;
            height: 160px;
            border-radius: 5px;
            object-fit: cover;
        }

    </style>
</head>
<body>

<div class="background-container">
    <div class="text-container">
        <div class="expert-insight">
            JavaScript
        </div>
        <div class="line"></div> 
        <div class="book-title">
            The Definitive Guide
        </div>
        <div class="subtitle">
            Master the World's Most-Used<br>Programming Language
        </div>
        <div class="author-name">Divid Flanagan</div>
    </div>

    <div class="image-container">
        <img src="Harish.jpg" alt="Your Image">
    </div>
</div>

</body>
</html>

```

## OUTPUT:

![alt text](<harish/coverapp/static/Screenshot 2024-12-21 092947.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

# Ex.06 Book Front Cover Page Design
## Date:

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .bodyc {
            margin: 0;
            padding: 0;
            font-family: verdana;
            background: #CCC;
        }

        .center {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }

        .page {
            width: 400px;
            height: 600px;
            padding: 30px;
            background: #FFF;
            border-left: 30px solid #FF2929;
            transform: rotate(-45deg) skewX(10deg) scale(.8);
            box-shadow: -50px 50px 50px rgba(0, 0, 0, 0.5);
        }

        .page h1, .page p {
            font-weight: bold; /* Make headings and paragraphs bold */
            margin: 0 0 20px 0;
            padding: 0;
            text-align: center;
            font-size: 25px;
            color: #9e9e9e;
        }

        .page p {
            margin: 0;
            padding: 0;
            text-align: justify;
        }

        .page:before {
            content: "";
            width: 30px;
            height: 100%;
            background: #8a0e0e;
            position: absolute;
            top: 0;
            left: 0;
            transform: skewY(-45deg) translate(-57px, -43px);
        }

        .page:after {
            content: "";
            width: 106%;
            height: 30px;
            background: #CCC;
            position: absolute;
            bottom: 0;
            left: 0;
            transform: skewX(-45deg) translate(-11px, 30px);
        }

        .author-image {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            position: absolute;
            bottom: 10px;
            left: 50%;
            transform: translateX(-50%);
        }
    </style>
    <title>Responsive Web Design with HTML5 and CSS</title>
</head>
<body class="bodyc">
    <div class="center">
        <div class="page">
            <header>
                <h1>Responsive Web Design with HTML and CSS</h1>
                <p>Third Edition</p>
            </header>
            <main>
                <div class="content-container">
                    <img src="html.jpg" alt="Book cover for Responsive Web Design with HTML5 and CSS Third Edition">
                    <p>Develop future-proof responsive websites using the latest HTML and CSS techniques.</p>
                </div>
            </main>
            <section class="author-section">
                <img src="my.JPG" alt="" class="author-image">
                <p>By Ajay Surya</p>
            </section>
        </div>
    </div>
</body>
</html>

```
## OUTPUT:
![image](https://github.com/AjaysuryaS/cover/assets/114158396/6ce35d38-2cc4-491e-a029-c618933971b3)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

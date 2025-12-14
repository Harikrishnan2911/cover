# Ex.05 Book Cover Page Design
## Date: 14.12.2025

## AIM:
To design a book back cover page using HTML and CSS.

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

<html>
    <head>
        <title>Cover Page</title>
        <link rel="stylesheet" href="styles.css">
    </head>
<body>
<div class="container">
    <h2>About the Book</h2>
    <hr>
    <p>
        This book <b><mark>"Introduction to Modern Computing Systems"</mark></b> offers a clear and practical overview
        of how today's computer systems work. It covers the foundation of computing -- from binary logic
        and system architecture to algorithms, operating systems, and networking concepts.
    </p>
    <p>
        The chapters are designed to help beginners understand how hardware and software interact, how
        data flows through a system, and how real-time applications are built using core computing principles.
        Readers will gain confidence in analyzing problems, designing efficient solutions, and understanding
        the technology that drives today's digital world.
    </p>
    <div class="quote">
        "A strong foundation in computing makes complex technology simple -- and innovation possible."
    </div>
    <div class="author-box">
        <img src="Hari.jpg" alt="Author Image">
        <div>
            <h3>Harikrishnan P</h3>
            <p>
                Harikrishnan is a computer science enthusiast passionate about understanding how systems,
                software, and real-world applications are built from the ground up. With a growing interest in
                software engineering, system design, and development, he aims to build solutions that are
                efficient, scalable, and meaningful.
            </p>
        </div>
    </div>
    <div class="footer">
        <span><b>SEC Publishers</b><br>Printed in India</span>
        <span class="price">Price: Rs.399</span>
    </div>
</div>
</body>
</html>

styles.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 20px;
    background: rgb(5, 61, 113); 
}
.container {
    background: white;
    background-image: url(img2.jpg);
    width: 46%;
    margin: auto;
    padding: 25px;
    border-radius: 10px;
    border: 2px solid darkblue
}
h2{
    color: darkblue;
}
hr {
    border: none;
    height: 2px;
    background: darkblue;
    margin: 10px 0 20px 0;
}
p {
    line-height: 2;
    color: black;
}
.quote {
    border: 1px solid darkblue;
    background: lightcyan;
    border-left: 5px solid lightgreen;
    padding: 15px;
    margin: 25px 0;
    font-style: italic;
    color: darkblue;
    border-radius: 5px;
}
.author-box {
    display: flex;
    background: lightcyan;
    padding: 15px;
    border-radius: 10px;
    border: 1px solid darkblue;
    margin-top: 25px;
    gap: 15px;
}
.author-box img {
    border-radius: 8px;
    width: 80px;
    height: 80px;
    object-fit: cover;
    border: 2px solid darkblue;
}
.author-box h3 {
    margin: 0 0 5px 0;
    color: darkblue;
}
.footer {
    margin-top: 25px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: lightgreen;
    color: darkblue;
    padding: 12px 20px;
    border-radius: 10px;
}
.price {
    font-weight: bold;
    font-size: 18px;
}
```

## OUTPUT:

![alt text](<Screenshot (36).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.

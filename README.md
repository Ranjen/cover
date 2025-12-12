# Ex.05 Book Cover Page Design
## Date:12-12-2025

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
        <link href="styles.css" rel="stylesheet">
    </head>
    <body class="id1">
        <div class="id3">
            <h1>Principles of Software Engineering</h1>
            <hr color="black" size="2">
            <br>
            <font>The Book </font><font class="id2">"Principles of Software Engineering"</font><font>provides an engaging journey through the principles, methods, and practices used to build reliable software systems. It explores how structured processes, creative problem-solving, and technology come together to create efficient and maintainable applications. Readers will learn essential engineering concepts, development models, design principles, testing strategies, and the importance of quality assurance in transforming ideas into functional software products.</font>
            <div>
                <br>
                <font class="id4">"Software engineering is not just about writing code - it is about designing solutions that work reliably in the real world."</font>
            </div>
            <br><br>
            <div class="id5">
                <img src="image.jpg" style="height: 160px;width: 150px;">
                <div class="id6">
                    <b>Ranjen Munuswamy K B</b>
                    <br><br>
                    Ranjen Munuswamy K B is a passionate learner with a strong interest in software engineering,
    technology, and modern computer systems. Dedicated to exploring innovative ideas and improving
    technical skills, Ranjen continues to grow in the world of computing and development.
                </div>
            </div>
            <br><br><br>
            <div class="id7">
                <font class="color">SEC Publishers</font><br>
                <div class="Price">
                    <font>Price: </font><font class="color">$19.50</font>
                </div>               
                <font>Printed in India</font>    
            </div>
        </div>
    </body>
</html>

styles.css

body{
    background-image: url("image.png") ;
}
h1{
    padding-left: 5px;
    padding-top:20px;
    color:whitesmoke;
}
font{
    font-size: 18;
    align-self: auto;
    color:black;
}
.id2{
    color:whitesmoke;
    padding:5px;
}
.id3{
    width:700;
    background:linear-gradient(rgb(117, 17, 140),rgb(210, 8, 228),rgb(16, 149, 227));
    margin: auto;
    border:solid 4px black;
    border-radius: 35px 35px;
    padding: 25px;
}
.id4{
    background:linear-gradient(45deg,rgb(74, 8, 255),rgb(164, 179, 180)); 
    padding: 15px;   
    margin:  auto;
    font-size: 16px;
    font-style: italic;
    display:flex;
    border-left: 5px solid;
    text-align: center;
}
.id5 {
    background:linear-gradient(rgb(249, 4, 179),rgb(115, 0, 255));    
    padding: 15px;
    width: 400px;
    margin: auto;
    border-radius: 15px;
    display: flex;
    gap: 15px;   
    border:solid 3px black;                   
}
.id6 {
    font-size: 15;
}
.id7{
    background:linear-gradient(rgb(57, 64, 101),whitesmoke);
    border:solid 3px black;
    border-radius: 0px 10px;
    padding:15px;
    
}
.color{
    color:black;
    background:radial-gradient(gold,goldenrod,black);
    padding: 4px;
    border-radius: 5px 5px;
}
.price{
    padding-left: 84%;
}
```

## OUTPUT:
![alt text](<Screenshot 2025-12-12 160807.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.

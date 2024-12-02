# Ex.06 Book Front Cover Page Design
## Date:2/12/2024

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
body.html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>COVER</title>
        <!-- <link ref="stylesheet" href="bg imag.png"> -->
        <link rel="stylesheet" href="book.css">
    </head>
    <body >
        <div id="center">
            <img src="techimg.jpg" alt="" id="image">
            <img src="ameen-removebg-preview.png" alt="ameen" id="ameen">
            <p  id="head">EXPRERTS INSIGHT  </p>
            <p id="title">MERN FRAMWORK</p>
            <p id="subtitle"> Easiest way to lear web development </p>
            <p id="edition">FIRSTEDITION</p>
            <p id="name">Ameen Basha.A</p>
        <div >

    </body>
    </html>
```
```
book.css

*{
    padding: 0px;
    margin:0px;
}
#image{
    position: absolute;
    background-image: url(bg\ imag.png);
    background-size: cover;
    top:30px;
    height: 650px;
    width: 500px;
    /* border: 5px solid pink; */
}
#center
{
    margin-left:500px;
}
#head
{
    position:absolute;
    top: 50px;
    left:520px;
    color: red;
}

#title
{
    position:absolute;
    top: 150px;
    left:590px;
    font-size: 30px;
    color: red;
}
#subtitle
{
    position:absolute;
    top: 250px;
    left:590px;
    font-size: 20px;
    color: cyan;
    
}
#edition
{
    position:absolute;
    bottom: 80px;
    left:520px;
    font-size: 20px;
    color: whitesmoke;
}
#name
{
    position:absolute;
    bottom: 70px;
    left:840px;
    font-size: 20px;
    color: cyan;
}
#ameen{
    position:fixed;
    height: 180px;
    bottom: 100px;
    border-radius: 50px;
    left:840px;
}
```

## OUTPUT:
![alt text](<Screenshot (51).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

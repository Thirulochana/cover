# Ex.05 Book Cover Page Design
## Date:16.12.25

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
        <title>Book Page</title>
        <link href="styles.css" rel="stylesheet">
    </head>
    <body>
        <div class="container">  
         <div class="About">   
             <h1>About The Book</h1>
        <div class="hrstyle">
             <hr style="color:black;">
        </div>
          <p>Clean code is software that's easy to read, understand, and maintain, focusing
            on clarity, simplicity, and expressiveness for human developers, not just machines,
            by using meaningful names, small functions, and adhering to design principles to
            reduce complexity and technical debt.</p>
         </div>
             <div class="quote">
            <p>It is not enough for code to work.</p>
        </div>
        <div class="author">
            <img src="img 2.png" alt="Author Image">
            <div>THIRULOCHANA S
            <p>Thirulochana is a college student and a passionate young writer,who expressed
                her thoughts through words.balancing academics and creativity writes about emotions,
                real life experience,and the little moments that shape youth.</p>
                </div>
            </div>
        <div class="PUBLISHER">
            SEC PUBLISHERS-
            PRINTED IN INDIA
            <div>
            PRICE:RS.500
            </div>
    </body>
</html>

styles.css

body
{
    background:url('img 1.png')no-repeat center/contain;
    font-family: Arial, "Helvetica Neue", Helvetica, sans-serif;
    padding: 50px;
}
.container
{ 
    width:30%;
    margin:auto;
    padding: 20px 40px;
    border-radius: 20px;
    border: 3px lavender;
}
.About
{
    font-style: oblique;
    font-size: medium;
    font-weight: bolder;
    color: rgb(2, 1, 10);
    margin-top: 15px;
    margin-bottom: 15px;
}
.quote
{
    background-color: rgb(245, 147, 208);
    padding: 10px;
    margin: 5px;
    border-left: solid rgb(174, 10, 180);
    font-style: oblique;
    font-weight: 200;
    font-family: 'Times New Roman', Times, serif;
}
.Author
{
    display:flex;
    background-color: rgb(244, 169, 220);
    padding: 5px;
    border-radius: 20px;
    border: outset purple;
    margin-top: 20px;
    margin-bottom: 20px;
    font-weight: 100;
    font-style: 30px;
    color: rgb(2, 1, 8);
    flex-direction: row;
}
.Author img
{
    width:100px;
    height:100px;
    border-radius: 6px;
    margin-right: 10px;
    margin-left: 10px;
    border:5px rgb(146, 54, 243);
    color: rgb(240, 66, 167);
}
.PUBLISHER
{
    margin-top: 20px;
    margin-bottom: 20px;
    padding: 12px 20px;
    background-color: palevioletred;
    color: black;
    border-radius: 12px;
    text-align: center;
    font-weight: 200;
    font-style: oblique;
}
```
## OUTPUT:
![alt text](<img 3.png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.

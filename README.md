# Ex.06 Book Front Cover Page Design
## Date:12-04-2024

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
bk.html
<!DOCTYPE html>
<html lang="en">
   <head>
        <meta name="viewport" 
        content="width=device-width, initial-scale=1.0">
        <style>

       .bookpage{
           width: 400px;
           height: 600px;
           color:rgb(236, 91, 24);
           margin-left: auto;
           margin-right: auto;
           padding: 20px;
           font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
           background-image: url(./bg.jpeg);
           background-size: cover;
       }
           

       .insight{
           color: rgb(32, 150, 189);

       }

       
       .hrstyle{
           width:100px;
       }
       .author{
       
           display: inline;
           position: relative;
           color: black;
           top:190px;
           
           font-family:Georgia;
           font-size: medium;
       }
       .booktitle{
           font-family: 'Courier New', Courier, monospace;
           font-size: larger;
           text-align: center;
           position: relative;
           top: 30px;
       
       }
       .id {
           width:400px;
           position: relative;
           top:180px;
           
       }
       .ed{
           color: rgb(86, 46, 156);
           font-size: medium;
           font-family: Verdana;
           position:relative;
           top:85px;

       }
       .subtitle{
           color:yellowgreen;
           font-family:Verdana;
           font-size: large;
           position: relative;
           top:40px;
       }
       .mypic{
           position: relative;
           top: 135px;
           left: 260px;
           width: 100px;
           height: 100px;
           background-size: cover;
       }
       
       </style>
       <title>Book Cover Page</title>
   </head>
   <body>
       <div class="bookpage">
           <div class="insight">
               SEC INSIGHT
           </div>
           <div class="hrstyle">
               <hr style="color: black">
           </div>
           <div class="booktitle">
               <h2>PYTHON BASICS</h2></div>
           <div align="center" class="subtitle">
            A Practical Intorduction to Pyton3
           </div>
           <div class="mypic">
               <img src="./pic1.jpg" width="125" height="150" alt="">
           </div>
           <div class="id">
               <hr style="color: black;">
           </div>
           <div class="author">
              <p><b>NARRA AKHIL(212223230136)</b></p>
           </div>
           <div class="ed">
               <b>Second Edition</b>
           </div>
       </div>
   </body>
</html>
```


## OUTPUT:

![alt text](<Screenshot (37).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

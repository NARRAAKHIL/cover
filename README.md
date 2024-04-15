# Ex.06 Book Front Cover Page Design
<<<<<<< HEAD
## Date: 15-04-2024
=======
## Date:12-04-2024
>>>>>>> a9293a4eef446cd1793f1e8ec02baf45ce7a5171

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
<<<<<<< HEAD
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Front-end Web Development</title>
        <link rel="stylesheet" href="{% static 'css/index.css' %}">
        <style>
            body{
    color:black;
    font-family: Helvetica, sans-serif;
    background-color: #333
}

.book{
    width: 726px;
    height:891px;
    margin:auto;
    position: relative;
    background-image: url(background.jpg);
    background-repeat: no-repeat;
    background-size:cover;
    background-position: bottom 0px center;
}
h1{
    font-size:70px;
    margin:60px;
    margin-bottom:0px;
}
h3{
    margin:0px 0px 90px 60px;
    position: absolute;
    bottom:0px;
    font-size: xx-large;
    font-weight:10px;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    color:red

}
h4{
    font-size:20px;
    margin:60px;
   margin-top:10px;
   width:430px;
}
#top{
    border-bottom:2px solid red;
    padding:100px 0px 5px 30px;
}
footer{
    position: absolute;
    bottom: 10px;
    border-top:2px solid red;
    padding-top:0px;
    width:726px;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.photo{
            position: relative;
            top: 170px;
            left: 550px;
            width: 120px;
            height: 120px;
            background-size: cover;
        }
#HASH {
    display: flex;
    justify-content: space-between;
}
  #HASH span{
    margin:10px 0px 20px 60px;
    font-size: xx-large;
    font-weight: bold;
  }
  #end{
    padding-right:60px;
  }
        </style>
    </head>
    <body>
        <section class="book">
            <br><br>
        <span id="top">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
            <h1>JAVASCRIPT AND JQUERY</h1>
            <h4>INTERACTIVE FRONT-END WEB DEVELOPMENT</h4>
            <h3>SIXTH Edition</h3>  
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>NARRA AKHIL</span>
                    <span id="end"><u>SEC</u></span>
                </div>
            </footer>
            <div class="photo">
                <img src="MY PHOTO.jpg" width="150" height="170"alt="">
            </div>  
    </section>
    </body>
=======
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
>>>>>>> a9293a4eef446cd1793f1e8ec02baf45ce7a5171
</html>
```


## OUTPUT:
![alt text](<Screenshot (21).png>)

![Screenshot (37)](https://github.com/NARRAAKHIL/cover/assets/144979843/a6ec6d6e-d36d-4d32-954a-112239f05690)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

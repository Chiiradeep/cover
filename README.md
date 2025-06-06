# Ex.06 Book Front Cover Page Design
## Date:15/05/2025

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
<html lang="en">
   <head>
        <meta name="viewport" 
        content="width=device-width, initial-scale=1.0">
        <style>

       .bookpage{
           width: 400px;
           height: 600px;
           color:rgb(135, 11, 11);
           margin-left: auto;
           margin-right: auto;
           padding: 20px;
           font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
           background-image:url(download.jpeg);
           background-size: cover;
       }
           

       .insight{
           color: rgb(247, 247, 247);

       }

       
       .hrstyle{
           width:100px;
       }
       .author{
       
           display: inline;
           position: relative;
           color: rgb(199, 199, 199);
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
           color: rgb(255, 255, 255);
           font-size: medium;
           font-family: Verdana;
           position:relative;
           top:85px;

       }
       .subtitle{
           color:rgb(7, 7, 2);
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
               SEC 
           </div>
           <div class="hrstyle">
               <hr style="color: rgb(67, 90, 90);">
           </div>
           <div class="booktitle">
               <h2>LEANING into LOVE</h2></div>
           <div class="subtitle">
            The Secrets To Finding And Keeping Intimacy
           </div>
           <div class="mypic">
               <img src="passport photo copy.jpg" width="125" height="150" alt="">
           </div>
           <div class="id">
               <hr style="color: rgb(119, 131, 11);">
           </div>
           <div class="author">
              <p><b>Chiiradeep R</b></p>
           </div>
           <div class="ed">
               <b>First Edition</b>
           </div>
       </div>
   </body>
</html>
~~~

## OUTPUT:
![alt text](<Screenshot 2025-05-15 190557.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

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
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage{
            width: 400px;
            height: 600px;
            color:rgb(232, 193, 193);
            margin-left: auto;
            margin-right: auto;
            padding:20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('Book.jpg');
            background-size: cover;
        }
        
        .insight{
            color:rgb(146, 109, 109) ;
        }

        .hrstyle{
            width: 100px;
        }

        .author{
            color: rgb(76, 137, 29);
            display: inline;
            position: relative;
            color: rgb(32, 174, 176);
            top: 130px;
            left: 80px;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 60px;
        }

        .id{
            width: 410px;
            position: relative;
            top: 200px;
        }

        .pub{
            font-size: large;
            position: relative;
            top: 100px;
            left: 200px;
        }
        .ed{
            color: rgb(133, 34, 118);
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top:50px;
            left: 50px;

        }

        .subtitle{
            font-family: Tahoma;
            font-size: large;
            position: relative;
            margin-left: 100px;
            top: 50px;
        }
        .mypic{
            position: relative;
            top: 170px;
            left: 200px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="EXPERT INSIGHT">
                
            </div>
            <div class="hrstyle">
                <hr style="color: rgba(160, 124, 124, 0.842);">
            </div>
            <div class="booktitle">
                <h1>BASICS OF WEB DEVELOPMENT</h1>
            </div>
            <div class="subtitle">
            Basic Guide For Beginners
            </div>
            <div class="mypic">
                <img src="Myphoto.jpeg" width="120" height="120" alt="Error">
            </div>
            <div class="id">
                <hr style="color:rgb(184, 147, 147);">
            </div>
            <div class="author">
                <p><b>ARHAM S</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Extended Edition</b>
            </div>
        </div>
    </body>
</html>       
    
```

## OUTPUT:
![Screenshot (137)](https://github.com/arhamshajahan/cover/assets/127313881/5263f9fa-8f25-4d76-ab77-52c507d6d39e)

## CODE:
![Screenshot (136)](https://github.com/arhamshajahan/cover/assets/127313881/be3eef01-256c-4869-a0d7-0ce85b90ba90)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

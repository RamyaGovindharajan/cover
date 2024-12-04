# Ex.06 Book Front Cover Page Design
## Date:04-12-2024

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
<html>
    <head>
        <title>
            Front cover page
        </title>
        <style>
            .bookpage{
                height:680px;
                width:600px;
                margin-left:35%;
                background-image: url("cover.png");
                padding:10px;
                background-size: cover;
            }
            .hr1{
                width:200px

            }
            .booktitle{
                margin-top: 30px;
                color:rgb(11, 14, 20);
                padding:5px;
                font-size: xx-large;
            }
            .subtitle{
                color:rgb(21, 7, 7);
                font-size: large;
            }
            
            .mypic{
                position: relative;
                top:90px;
                left:470px;
                height: 100px;
                width: 70px;
            }
            .hr2{
                padding-top: 130px;
            
            }
            *{
                color: rgb(0, 0, 9);
            }
            .ed{
                position:relative;
                top: 80px;
            }
            .author{
                font-family: 'Trebuchet MS';
                font-size: large;
            }
            .pb{
                position: relative;
                left:420px;
                top:-50px;
                font-size: x-large;
            }
        </style>
        <body>
            <div class="bookpage">
            <div style="color:rgb(23, 19, 17)">INSIGHT </div>
            <div class="hr1"><hr ></div>
            <div class="booktitle"><h3>TECHNOLOGICAL INNOVATIONS AND MARKET TRENDS</h3></div>
            <div class="subtitle"><h4>The promotion of original and advanced products or services</h4></div>
            <div class="mypic"><img src="mypic.png" height="140px" ></div>
            <div class="ed">SPECIAL EDITION</div>
            <div class="hr2"><hr ></div>
            <div class="author">
            <div style="color:rgb(12, 12, 9)" > RAMYA G</div>
            <div class="pb"> <h2>SEC</h2></div>
        </div>
        </body>
    </head>
</html>
```

## OUTPUT:

![alt text](<cover output.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

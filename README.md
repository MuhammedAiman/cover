# Ex.06 Book Front Cover Page Design
## Date:7-12-2024

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
<head>
    <meta name="viewport" content="width=device=width, initial-scale=1.0">
    <style>

        .bookpage{
            width: 500px;
            height: 700px;
            color: rgb(235, 244, 244);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            background-image: url(book.jpg);
            background-size: cover;
        }


        .author{
            display: inline;
            position: relative;
            color: rgb(14, 14, 12);
            top: 415px;

            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: medium;
        }

        .booktitle{
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .ed{
            color: rgb(9, 10, 9);
            font-size: medium;
            font-family: German Frakturs;
            position: relative;
            top: 361px;

        }

        .subtitle{
            font-family: German Frakturs;
            font-size: large;
            position: relative;
            top: 40px;
        }

        .mypic{
            position: relative;
            top: 411px;
            left: 370px;
            width: 100px;
            height: 100px;
            background-size: cover;

        }
    </style>
    <title>BOOK COVER</title>
</head>
<body>
    <div class="bookpage">
        <div class=""> </div>
        <div class="">
            <hr style="color: rgb(19, 22, 22);">
        </div>
        <div class="booktitle">
         <h1>
                </h1>
        </div>
        <div class="subtitle">
            <center>
            


            </center>
        </div>
        <div class="mypic">
            <img src="mypic2.jpg" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: orange;">
        </div>
        <div class="author">
            <p><b> AIMAN </b></p>
        </div>
        <div class="ed">
            <b>FIRST EDITION</b>
        </div>
    </div>
</body>

</html>
```


## OUTPUT:
![alt text](<myproject/myapp/static/Screenshot (22).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

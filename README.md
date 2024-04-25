# Ex.06 Book Front Cover Page Design
## Date: 25-04-24

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
<!DOCTYPE html>
<html>

<head>
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color:rgb(217, 219, 220);
    }

    .book-cover {
      width: 500px;
      height: 700px;
      background-color:rgb(199, 198, 204);
      box-shadow: 0 0 10px rgba(11, 165, 111, 0.2);
      margin: 50px auto;
      position: relative;
    }
    
    .book-cover .insight {
      position: absolute;
      top: 20px;
      left: 20px;
      font-size: 24px;
      font-weight: bold;
      color: rgb(96, 11, 3);
    }
    .book-cover .line1
    {
      position: absolute;
      top: 40px;
      left: 5px;
      width: 80px;
    }
    .book-cover .title1 {
      position: absolute;
      top: 80px;
      left: 25px;
      font-size: 40px;
      font-weight: bold;
      color:  rgb(12, 14, 14);
    }
    .book-cover .title2 {
      position: absolute;
      top: 130px;
      left: 30px;
      font-size: 40px;
      font-weight: bold;
      color:  rgb(219, 212, 220);
    }

    .book-cover .subtitle1 {
      position: absolute;
      top: 470px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color:  rgb(222, 26, 72);
    }
    .book-cover .subtitle2 {
      position: absolute;
      top: 500px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color: rgb(77, 24, 202);
    }
    .book-cover .subtitle3 {
      position: absolute;
      top: 530px;
      left: 20px;
      font-size: 16px;
      font-weight: bold;
      color: rgb(24, 58, 253);
    }
    .book-cover .line2
    {
      position: absolute;
      top: 480px;
      left: 20px;
      width: 160px;
    }
    .book-cover .line3
    {
      position: absolute;
      bottom:38px;
      left: 20px;
      width: 115px;
    }


    .book-cover .author {
      position: absolute;
      bottom: 25px;
      left: 20px;
      font-size: 18px;
      color: rgb(130, 45, 88);
    }

    .book-cover .number {
      position: absolute;
      bottom: 5px;
      left: 20px;
      font-size: 18px;
      color: rgb(66, 58, 156);
    }

    .book-cover .end {
      position: absolute;
      bottom: 5px;
      right: 50px;
      font-size: 18px;
      color: rgb(188, 22, 22);
    }
    .book-cover .mypic
    {
      position: relative;
      top:550px;
      left: 370px;
      width : 8px;
      height: 8px;
      background-size:fit;
    }


    .book-cover .image {
      width: 100%;
      height: 100%;
      object-fit: cover;
      position: absolute;
      top:  0;
      left: 10;
    }
  </style>
</head>

<body>
  <div class="book-cover">
    <img src="c:\Users\admin\Downloads\book image.jpg" alt="Book Cover Image" class="image">
    <div class="insight">TECHNOLOGY</div>
    <div class="line1"><hr style="color:rgb(12, 228, 95)"></div>
    <div class="title1">MASTERING IN</div>
    <div class="title2">HTML,CSS & JAVASCRIPTS Web Publishing</div>
    <div class="subtitle1">Best For Beginners</div>
    <div class="line2"><hr style="color:rgb(238, 26, 185)"></div>
    <div class="subtitle2">Second Editon</div>
    <div class="subtitle3">The Secrets of Technology in Web Development</div>
    <div class="line3"><hr style="color:rgb(220, 130, 19)"></div>
    <div class="end">SEC</div>
    <div class="number">BPB publications</div>

    <div class="author">DHANUSYA K</div>

  </div>
</body>
</html>
~~~
## OUTPUT:
![Screenshot 2024-04-25 201250](https://github.com/Dhanu654/cover/assets/148514965/bd8ac09c-6a13-4c66-a4c0-d403c7c36203)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

# Ex.06 Book Front Cover Page Design
# Date:3.10.2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```

<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>COMIC</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: blue;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 160vh;
      font-family: 'Georgia', serif;
      width: 400vh ;
    }

    .book-cover {
      height: 860px;
      background: white;
      border: 2px solid rgb(222, 27, 27);
      padding: 40px 30px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .title {
      font-size: 28px;
      font-weight: bold;
      color: #2e2e2e;
      text-align: center;
      line-height: 1.3;
    }

    .subtitle {
      font-size: 16px;
      margin-top: 10px;
      text-align: center;
      font-style: italic;
    }

    .image {
      flex: 1;
      background: url('C:\Users\sribh\OneDrive\Desktop\experiment6.web\bookcover\bookapp\static\download (1).jpg') center/contain no-repeat;
      margin: 39px 0;
      height:45px;
    }

    .author {
      font-size: 18px;
      text-align: center;
      color: #444;
      margin-top: -20px;
    }

    .line {
      height: 2px;
      background: #333;
      width: 50px;
      margin: 10px auto;
    }

    .out{
      color:black;
      margin:auto;
      text-align: center;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div>
      <div class="title">COMIC LIBRARY</div>
      <div class="line"></div>
      <div class="subtitle">Read and Enjoy the art of the auther's Creation</div>
      <div class="out">Read well with the pleasure</div>
    </div>
    <div class="image">
        <img src="C:\Users\sribh\OneDrive\Desktop\experiment6.web\bookcover\bookapp\static\download (1).jpg" height="550px">
    </div>
    <div class="author"><h1>AKIRA TORIYAMA</h1></div>
  </div>
</body>
</html>
```
# OUTPUT:

![alt text][def C:\Users\sribh\OneDrive\Desktop\experiment6.web\book_cover\bookcover\bookapp\static\image.png]

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.


[def]: book_cover/bookcover/bookapp/static/image.png

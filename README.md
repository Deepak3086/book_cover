# Ex.06 Book Front Cover Page Design
# Date: 12/11/24
## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:
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

## PROGRAM:
~~~
<html>
<head>
  <title>Tesla Autobiography Book Cover</title>
  <style>
    body {
      margin: 0;
      font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: #eff0f0;
      color: white;
      
    }
    .book-cover {
      width: 300px;
      height: 450px;
      background: #0f2027;
      border: 3px solid #203a43;
      text-align: center;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 20px;
      box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    }
    .title {
      font-size: 1.8rem;
      font-weight: bold;
      margin-bottom: 10px;
      padding: 20px;
    }
    .subtitle {
      font-size: 1rem;
      margin-bottom: 20px;
      padding: 20px;
      font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
    }
    .author {
      font-size: 1rem;
      font-style: italic;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="title">Tesla: The Innovator</div>
    <img src="c:\Users\admin\Pictures\web photos\tesla.jpg">
    <div class="subtitle">A look into the life of a visionary </div>
    <div class="author">by Nikola Tesla</div>
  </div>
</body>
</html>
~~~

## OUTPUT:
![alt text](<Screenshot 2024-12-03 180749.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

# Ex.06 Book Front Cover Page Design
# Date: 18/11/24
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
        <title> Book cover</title>
        <style>
            .Book{
                text-align: center;
                background-color:turquoise;
                width: 45%; height: 100%;
                margin:auto;
                padding: 20px;
            }
            .title{
               font-size: 70px;
                font-weight: bold;
                color: rgb(10, 7, 7);
            }
            .author{
                font-size: 40px;
                font-style: italic;
            }

           .image{
            height: 15%;
            width: 15%;
            padding-left: 60%;
           }
           
        </style>
    </head>
    <body>
        <div class="Book">
            <div class="title">The Autobiography of Nikola Tesla </div>

            <div class="author">Nikola Tesla</div>
            <img src="C:\Users\admin\Downloads\mbp\book cover.jpg" style="height: 40%; width: 40%;">
                       
            <div style="font-size: 40px; top: 1px";> <i>The Journey through the Life and Mind of a visionary </i> </div>
            <img src="C:\Users\admin\Downloads\mbp\tesla.jpg" class="image">
            
        </div>
    </body>
</html>
~~~
## OUTPUT:
![image](https://github.com/user-attachments/assets/66e7c179-8ea6-4021-9242-b31f85da52c1)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## DESIGN STEPS:

### Step 1:
Create a new Django project and app

### Step 2:
Create a static file directory and mention the changes in settings.

### step 3:
Make a new folder templates inside your app and create a html and map them using views and url.

### step 4:
Write down the code for book cover using HTML and CSS.

### step 5:
Add images and other contents using CSS record a screenshot of it.

## CODE:
```
NAME:G.R.NANDHAKUMAR
REF NO:212222100029
```
```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <title> SPIDERMAN</title>
        <style>
        h1{
           color:white;
        }
         .bookpage{
             width: 400px;
             height: 650px;
             background-color: black;
             background-position: center;
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url("/static/images/spider2.png");
             background-size: cover;
             background-repeat: no-repeat;

         }
         .toptext{
             color:azure;
             padding-left: 10px;
             font-size: 14px;
             font-style:italic;
             font-family: Arial, Helvetica, sans-serif;

         }
         .tophr{
             color:#e36f2f;
              width: 180px;
         }
         hr{
             color:#e36f2f;

         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 0px 10px;
             display: flex;
            align-items: center;
            justify-content: center;
  margin-right: 10px;
  margin-left: 10px;
  font-size: 20px;
         }
         .author{
             color:red
             ;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
             font-size: 24px;
             position:relative;
             line-height: 20px;


         }
         .sub-text {
             color:white;
             font-family: Arial, Helvetica, sans-serif;
             display: flex;
             line-height: 5px;

  margin-right: 10px;
  margin-left: 10px;

  font-size: 14px;
  }

.footer {
  color:rgb(244, 243, 241);
  padding-top: 180px;
}
.image {
    color:white;
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
  margin-right: 20px;
}
.bottomhr {
    color:rgb(243, 246, 248);
              width: 400px;

}
img {
    width: 90px;
    height: 100px;
    margin-right: 20px;
    vertical-align: bottom;
}
.edition {
    color:rgb(255, 55, 55);
             font-family: Arial, Helvetica, sans-serif;
 font-size: 22px;
 line-height:bottom;

}


        </style>
        </head>
            <body>
                <div class="bookpage">

                    <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;SPIDEY ON DUTY</div>
                    <div class="tophr"><hr></div>
               <div class="booktitle"><h1>SPIDERMAN</h1></div>
               <h3 class="sub-text">THE ADVENTURES OF SPIDEY</h3>
                    <h3 class="sub-text">WRITTEN BY STANLEE</h3>
                    <div class="footer">
                        <h2 class="edition">&nbsp;&nbsp;FIRSTEDITION&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="/static/images/stanlee.jpeg" alt="Author"></h2>

                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3>&nbsp;&nbsp;STANLEE &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h3></div>

                </div>
                </div>

            </body>


</html>
```

## OUTPUT:
### SERVER OUTPUT:
![Screenshot (109)](https://github.com/Nandhakumar1313/cover-page-design/assets/120230694/d63ce7ff-3044-42da-925f-e7e9612c123b)

### CLIENT OUTPUT:
![Screenshot (107)](https://github.com/Nandhakumar1313/cover-page-design/assets/120230694/e30489fc-057a-4944-9848-e5631777b824)


## RESULT:
Thus a website to display the cover page design of a book was successfully created.

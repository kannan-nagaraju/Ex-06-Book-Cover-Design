# Ex-06-Book-Cover-Design
# AIM:
To develop a website to display the cover page design of a book
# Design Steps:
# Step 1:
Create a new Django project and app.
# Step 2:
Create a static file directory and mention the changes in settings.
# Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.
# Step 4:
Write down the code for book cover using HTML and CSS.
# Step 5:
Add images and other contents using CSS record a screenshot of it.
# STEP 6 :
Style author image (img) with fixed width, height, and margin.
# STEP 7 : End the HTML structure
Run the code.

# Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Book Coverpage</title>
        <style>
        h1{
           color:white;
        }
         .bookpage{
             width: 400px;
             height: 650px;
             
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url("bookcover.png");
             background-position: center;
             background-color: black;
             background-repeat: no-repeat;
         }
         .toptext{
             color:white;
             padding-left: 5px;
             font-size: 14px;
             font-family: Arial, Helvetica, sans-serif;
             
         }
         .tophr{
             color: orange;
              width: 180px;
         }
         hr{
             color: orange;
            
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
             line-height:normal;
         }
         .author{
             color:white;
             display:inline;
             position:relative;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
             font-size: 24px;
             line-height: 5px;
              
             
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
    color:orange;
    padding-top:180px;
}
.image {
    color:white;
             font-family: Arial, Helvetica, sans-serif;
    font-size: 22px;
    margin-right: px;
}
.bottomhr { 
    color: red;
              width: 400px;

}
img {
    width: 90px;
    height: 100px;
    margin-right: 20px;
    vertical-align:bottom;
}
.edition {
    color:orange;
             font-family: Arial, Helvetica, sans-serif;
    font-size: 22px;
    line-height: bottom;
 
}


        </style>
        </head>
            <body>
                <div class="bookpage">
                    <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;EXPERT INSIGHT</div>
                    <div class="tophr"><hr></div> 
               <div class="booktitle"><h1> Responsive Web Design with HTML5 and CSS </h1></div>
               <h3 class="sub-text">&nbsp;&nbsp;&nbsp;Develop future-proof responsive websites</h3>
                    <h3 class="sub-text">&nbsp;&nbsp;&nbsp;using the latest HTML5 and CSS designs</h3>
                    <div class="footer">
                        <h2 class="edition">&nbsp;&nbsp;First Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  <img src="author.png"></h2>
                      
                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3>&nbsp;&nbsp;Kannan &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Packt></h3></div>
                    
                </div>
                </div> 
                
            </body>
        
    
</html>
```
# OUTPUT:
![Alt](<Screenshot 2023-12-21 083235.png>)

# RESULT:
The book cover design has been successfully created using HTML and CSS.


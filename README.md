# Ex.06 Book Front Cover Page Design
## Date:22.04.2024

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
## HTML CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="stylee.css">
</head>
<body>
    <div class="box">
        <div class="winner">
            <h1>WINNER OF THE PULITZER PRIZE</h1>
        </div>
        <div class="my-book-cover">
            <div class="my">
                <h1><b>MY</b></h1>
            </div>
            <div class="book">
                <h1><b>BOOK</b></h1>
            </div>
            <div class="cover">
                <h1><b>COVER</b></h1>
            </div>

        </div>
        <div class="footer">
            <div class="secrets">
                <h1>secrets in a</h1>

            </div>
            <div class="silicon">
                <h1>Silicon Valley</h1>
            </div>
            <div>
                <h1><b>---------------------------------------------------------------------------------------------</b></h1>
                
            </div>
            <div class="photo" >
        
               <img src="PHOTO.jpg" alt="photo" width="200px" height="110px">
               <div class="publish">
                <h2><b>BOOK PUBLISHER-POPURI SRAVANI</b></h2>
               </div>
               
            </div>
            
            
              
            
        
        </div>
    </div>
</body>
</html>
```
## CSS Code
.box{
    height: 1400px;
    width: 1000px;
    margin: 70px 100px 400px 700px;
    
    background-color: red;
    
}
.winner{
    
    font-family: 'Courier New', Courier, monospace;
    color: whitesmoke;
    display: flex;
    font-size: larger;
    align-items: center;
    padding-left: 120px;
    padding-top: 160px;
    text-decoration: none;
    text-align: center;
    height: 10px;
    font-size: x-large;
    
    
}
.my-book-cover{
    font-size: 7em;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    
   

}
.my{
    
    padding-left: 320px;
    height: 15px;
    width: 15px;
    padding-bottom: 15px;
    
    
}
.book{
    padding-left: 190px;
    height: 15px;
    width: 15px;
    padding-bottom: 15px;
}
.cover{
    
    padding-left: 130px;


}
.secrets{
    color: whitesmoke;
    font-size: larger;
    
    
    padding-left: 350px;
    font-family: 'Courier New', Courier, monospace;
}
.silicon{
    color: whitesmoke;
    font-size: larger;
    
    
    padding-left: 330px;
    font-family: 'Courier New', Courier, monospace;

}
.photo{
    
    display: flex;
    font-family: 'Courier New', Courier, monospace;
    color: whitesmoke;
}
.publish{
    padding-top: 15px;
    padding-left: 100px;
    font-size: larger;
}
```


## OUTPUT:
![Screenshot 2024-04-24 173046](https://github.com/sravanipopuri2006/cover/assets/139778301/d5156eba-e8f3-4a73-b1f8-31b52140870a)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

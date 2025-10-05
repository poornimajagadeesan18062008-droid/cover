# Ex.06 Book Front Cover Page Design
## Date:05/10/2025

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
cover.html

<html>
    <head>
        <link rel="stylesheet" href="styles.css">
        <title>sample page</title>
    </head>
    <body>
        <div class="name"><h3><i>POORNIMA J(25015718)</i></h3></div>
        <div class="backgroundi">
            <div class="insight"><h3>SEC Insights<hr></h3><br></div>
            <div class="topic"><h1>Programming<br> Pearls</h1></div>
            <div class="des"><h3><i>Learn lots about programming languages<br>
            "Good programmers know what to write. Great ones know what to rewrite (and reuse)."</i></h3><i>BEST SELLER OF 2025</i></div>
            <div class="img"><img src="photo.jpg"></div>
            <div class="edit">Special Edition<hr></div>
            <div class="writer">Poornima J</div>
            <div class="bottom">poorni</div>
        </div>
    </body>
</html>

style.css

.name{
    color:aqua;
    text-align: center;
    font-family: italic;
}
.backgroundi{
    background-repeat: no-repeat;
    background-size:cover;
    background-image:url(background.jpeg);
    background-position:center center;
    box-shadow: inset 0 0 0 2px black;
    height:650px;
    width:500px;
    margin: auto;
    border: 13px solid;
    border-color:rgb(85, 191, 230);
}
.insight{
    padding-left: 15px;
    width:130px;
}
.topic{
    text-align:center;
    font-style: italic;
    color:blueviolet;
    font-size: 30px;
}
.des{
    font-family: italic;

}
.img{
    width: 90px; 
    height:120px;
    position:relative;
    top: 70px;
    left:380px; 
}
.edit{
    position:relative;
    top:50px;
    font-size: 20px;
    padding-left: 10px;
}
.writer{
    font-size:30px;
    position: relative;
    top:40px;
    padding-left: 10px; 
}
.bottom{
    font-size: 20px;
    position:relative;
    top:10px;
    left:420px;
}

```

## OUTPUT:
![alt text](<covers/bookapp/static/Screenshot (56).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

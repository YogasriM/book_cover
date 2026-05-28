# Ex.05 Book Front Cover Page Design
# Date: 28/05/2026
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
cover.html
<html>
    <head>
        <title>About The Book</title>
        <link rel="stylesheet" href="styles.css">
    </head>

<body>
    <div class="container">
        <h1>About The Book</h1>
        <hr class="title-line">
        <p>
            This book <span class="highlight">"Fundamendals of Web Application"</span>
            helps the reader to ensure whether he/she is familiar with basics such as HTML,CSS.
            This book provides the reader a well deep unstanding of the concepts in precise manner.
        </p>
        <div class="quote">
             If You Think Math is Hard Try Web Design.
        </div>
        <div class="author">
            <img src="aut.jpg"class="aut-img">
            <div class="author-text">
                <h3>Ralph Moosley</h3>
                <p>
                     Ralph Moosley is a technology enthusiast and web app developer  who enjoys exploring
                    dynamic web designing and modern computing. He has nearly 25 years of experience in web design and technonology.                
                </p>
            </div>
        </div>
        <div class="foot">
            <span class="publisher">SEC Publishers</span>
            <span class="price">Price:Rs 499</span>
        </div>

    </div>
</body>
</html>

styles.css

body {
    margin: 0;
    padding: 0;
    background: rgb(237, 240, 237);
}

.container {
    width: 470px;
    height: 600px;
    background-image: url('coverbook.jpg');
    background-size: cover;
    background-position: center;
    border: 4px solid rgb(16, 140, 178);
    border-radius: 12px;
    box-shadow: 0 10px 30px rgba(67, 9, 214, 0.2);
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    text-align: left;
    padding: 30px;
    margin: 40px auto;
    
}


h1 {
    color: rgb(5, 5, 5);
    margin-bottom: 20px;
    border-bottom: 2px solid;
    padding-bottom: 5px;
    
}

.highlight {
    background: rgb(14, 148, 174);
}

.title-line {
    border: none;
    height: 3px;
    background-color: rgb(19, 117, 147);  
    width: 2xpx;
    margin: 0 0 15px 0;
}


.quote {
    background: rgb(4, 130, 213);
    border-left: 5px solid rgb(19, 117, 147);
    padding: 15px;
    margin: 25px 0;
    font-style: italic;
}

.author {
    display: flex;
    align-items: center;
    background: rgb(7, 125, 210);
    padding: 20px;
    border-radius: 8px;
    margin-top: 10px;

}

.aut-img {
    width: 70px;
    height: 80px;
    border-radius: 5px;
    margin-right: 15px;
    object-fit: cover;
}

.foot {
    margin-top: 30px;
    display: flex;
    justify-content: space-between;
    background: rgb(7, 111, 246);
    color: rgb(22, 15, 1);
    padding: 12px 20px;
    border-radius: 6px;
    font-weight: bold;
}

.publisher {
    color: rgb(7, 6, 6);
}
```
# OUTPUT:
<img width="1832" height="853" alt="image" src="https://github.com/user-attachments/assets/f9d91501-9d48-47d0-bade-15ae3e4e4cd0" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

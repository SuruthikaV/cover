# Ex.05 Book Cover Page Design
## Date:15-12-2025

## AIM:
To design a book back cover page using HTML and CSS.

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
        <title>cover of book</title>
        <link href="styles.css" rel="stylesheet">
    </head> 
    <body>
        <div class="container">
            <div class="about">
                <h2>About the book</h2>
                <hr>
            </div>
            <div class="content">
                <p>This book <span>"Mastering Data Structures & Algorithms"</span> a clear and engaging introduction to one of the most essential foundations of computer science.
It explains how structured data and efficient algorithms work together to solve complex problems in technology. 
Readers will explore core concepts including arrays, linked lists, trees, graphs, sorting, and searching techniques, along with practical examples and problem-solving strategies.
The book blends theory with application, helping learners build strong analytical skills that
are vital for software development and competitive programming.</p>
            </div>
                <br>
                <br> 
            <div class="quote">
                <h2>"Great programs are not written </h2>
                <h2>They are designed through logic, structure, and clarity."</h2>
                <br>
            </div>
            <br>
            <br>
            
            <div class="author">
                <h2>V Suruthika</h2>
                
                <div class="photo">
                    <img src="img2.jpg" width="100">
                </div>
                <div class="para">
                    <p>V Suruthika is an emerging writer and passionate technology learner with a strong interest in programming and problem solving.
                 Her clear explanations and student-friendly approach make this book an excellent companion for anyone beginning
                 their journey into data structures and algorithms.</p>  
                </div>             
            </div>
            
            <br>
            <br>
            <br>
            <footer>
                <div class="publisher">
                    SEC Publishers
                </div>
                <div class="print">
                    printed in India
                </div>
                <div class="rate">
                    Price: RS.355
                </div>
            </footer>   
        </div>
    </body>
</html>

styles.css

.container
{
    
    padding: 50px;
    align-items: center;
    margin-left: 550px;
    width: 700;
    height: 800;
    background-image: url('img1.jpeg');
    background-position: center;
    background-size: cover;
    text-align: justify;
    border: solid 3px black;
    border-radius: 8px;
}
.quote
{
    text-align: center;
    align-items: center;
    border-left: solid 3px;
    border-color: rgb(5, 6, 6);
    background-color: rgb(166, 168, 170);
    font-style: italic;
}
.para
{
    text-align: left;
}
.author
{
    height: 150px;
    background-color: rgb(166, 168, 170);
    border-color: black;
    bottom: 500px;
    text-align: left;
    padding-left: 10px;

}
footer
{
   background-color: rgb(166, 168, 170);
   width: 700px;
   height: 60px; 
}
.publisher
{
    font-weight: bold;
    padding-left: 10px;
    position: relative;
    top: 10px;
}
.para
{
    padding-left: 110px;
    padding-bottom: 200px;
    position: relative;
    
    font-size: large;
    bottom: 100px;

}
h3
{
    padding-left: 110px;
    position: relative;
    bottom: 60px;
    top: 20px;
}
.rate
{
    padding-left: 610px;
    position: relative;
    bottom: 15px;
}
.print
{
    padding-left: 10px;
    position: relative;
    top: 10px;
}

.photo
{
    position: relative;
    bottom: 30px;
    top: 1px;
}
span
{
    background-color: rgb(189, 234, 248);
}
.content
{
    font-size: large;
}

```


## OUTPUT:
![alt text](<Screenshot (31).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.

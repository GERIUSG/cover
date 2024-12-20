# Ex.06 Book Front Cover Page Design
## Date:04/12/2024

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
<style>
    .bookpage {
        width: 400px;
        height: 600px;
        color: rgb(202, 15, 77);
        margin-left: auto;
        margin-right: auto;
        padding: 20px;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        background-image: url(back.png);
        background-size: cover;
    }


    .insight {
        color: rgb(231, 235, 13);

    }


    .hrstyle {
        width: 170px;
    }

    .author {

        display: inline;
        position: relative;
        color: rgb(235, 235, 9);
        top: 270px;

        font-family: Georgia;
        font-size: medium;
    }

    .booktitle {
        font-family: 'Courier New', Courier, monospace;
        font-size: larger;
        text-align: center;
        position: relative;
        top: 30px;

    }

    .id {
        width: 400px;
        position: relative;
        top: 280px;

    }

    .pub {
        color: rgb(138, 13, 99);
        font-size: medium;
        position: relative;
        top: 235px;
        left: 350px;
    }

    .ed {
        color: white (1, 2, 6);
        font-size: medium;
        font-family: Verdana;
        position: relative;
        top: 185px;

    }

    .subtitle {
        color: rgb(248, 240, 240);
        font-family: Tahoma;
        font-size: large;
        position: relative;
        top: 40px;
        font-weight: bold;
    }

    .mypic {
        position: relative;
        top: 230px;
        left: 260px;
        width: 100px;
        height: 90px;
        background-size: cover;
    }
</style>
<title>Book Cover Page</title>
</head>

<body>
    <div class="bookpage">
        <div class="insight">
            EXPERT INSIGHT
        </div>
        <div class="hrstyle">
            <hr style="color: yellow;">
        </div>
        <div class="booktitle">
            <h1>QUANTUM PHYSICS</h1>
        </div>
        <div class="subtitle">
            <font size="3">
                We will study Quantum Physics and Classical physics. Newton’s laws of motion can explain the behaviour
                of macroscopic objects or objects that are at a scale of human interaction and experience, even
                including astronomical objects.
        </font>
        </div>
        <div class="mypic">
            <img src="mypic.JPG" width="130" height="145" alt="">
        </div>
        <div class="id">
            <hr style="color: goldenrod;">
        </div>


        <div class="author">
            <p><b>GERIUS G</b></p>
        </div>
        <div class="pub">
            SEC
        </div>
        <div class="ed">
            <b>FIRST Edition</b>
        </div>
    </div>
</body>

~~~

## OUTPUT:
![alt text](<Screenshot (62).png>)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.

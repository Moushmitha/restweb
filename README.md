# Ex.06 Restaurant Website
## Date:14.03.2026

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in Localhost.

## PROGRAM:
```
cafe.html
<html>
    <head>
        <title>Golden Hour Cafe</title>
    </head>
        <style>
            body{
                background-image: url(cafe.jpg);
                background-repeat: no-repeat;
                background-size: cover;
            }
            .name{
                font-size: 65px;
                margin-top: 150px;
                color: rgb(246, 173, 28);
                font-weight: bolder;
                text-align: center;
                font-style: italic;
            }
            .greetings{
                text-align: center;
                margin-top: 10px;
                font-size: large;
                font-weight: bolder;
                font-style: italic;
                color: rgb(255, 220, 105);
            }
            .link{
                display: flex;
                position: fixed;
                top: 10;
                justify-content: space-evenly;
                width: 800px;
                height: 55px;
                font-size: 21px;
                margin-left: 330px;
            }
            a{
                text-decoration: none;
                color: rgb(243, 187, 89);
                font-weight: bold;
            }
            a:hover{
                color: rgb(112, 54, 18);
            }
            footer{
                text-align: center;
                color: wheat;
                background-color: black;
                padding: 5px;
                position: fixed;
                bottom: 0;
                left: 0;
                width: 100%;
            }
            </style>
            <body>
                <div class="name">
                    <p>Golden Hour Cafe</p>
                </div>
                <div class="greetings">
                   <h2>Step into Golden Hour Cafe, a cozy little corner where good coffee, 
                    delicious food, and warm conversations come together. 
                    Whether you're here for a quick coffee break, a sweet dessert, 
                    or to relax with friends, we are happy to serve you</h2> 
                </div>
                <div class="link">
                    <a href="cafe.html">Cafe House</a>
                    <a href="nuts.html">Cafe Offerings</a>
                    <a href="creator.html">Cafe Creators</a>
                    <a href="find.html">Find our Cafe</a>
                </div>
                <footer>
                    &copy; Moushmitha B (25014643)
                </footer>
            </body>
</html>

nuts.html
<html>
    <head>
        <title>Cafe Offereings</title>
    </head>
    <style>
        body{
            background-image: url(cafe.jpg);
            background-repeat: no-repeat;
            background-size: cover;
        }
        .link{
            display: flex;
            position: fixed;
            top: 10;
            justify-content: space-evenly;
            width: 800px;
            height: 55px;
            font-size: 21px;
            margin-left: 330px;
        }
        a{
            text-decoration: wavy;
            color: rgb(243, 187, 89);
            font-weight: bold;
        }    
        a:hover{
            color: rgb(112, 54, 18);
        }
        .name{
            font-size: 65px;
            margin-top: 100px;
            color: rgb(246, 173, 28);
            font-weight: bolder;
            text-align: center;
            font-style: italic;
        }
        .menu{
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 80px;
        }
        .item{
            margin: 20px;
            text-align: center;
            background-color: wheat;
            padding: 15px;
            border-radius: 20px;
            width: 220px;
        }
        .item img{
            max-width: 200px;
            max-height: 200px;
            border-radius: 20px;
            object-fit: cover;
        }
        footer{
            text-align: center;
            color: wheat;
            background-color: black;
            padding: 5px;
            position: fixed;
            bottom: 0;
            left: 0;
            width: 100%;
        }
    </style>
    <body>
        <div class="link">
            <a href="cafe.html">Cafe House</a>
            <a href="nuts.html">Cafe Offerings</a>
            <a href="creator.html">Cafe Creators</a>
            <a href="find.html">Find our Cafe</a>
        </div>
        <div class="name">
            <p>Golden Hour Cafe</p>
        </div>
        <div class="menu">
            <div class="item">
                <img src="hotcho.jpg">
                <h3>Hot Chocolate</h3>
                <h4>$3.50</h4>
            </div>
            <div class="item">
                <img src="cappuccino.jpg">
                <h3>Cappuccino</h3>
                <h4>$3.25</h4>
            </div>
            <div class="item">
                <img src="Americano.jpg">
                <h3>Americano</h3>
                <h4>$2.75</h4>
            </div>
            <div class="item">
                <img src="Cara.jpg">
                <h3>Caramel Machiato</h3>
                <h4>$4.25</h4>
            </div>
            <div class="item">
                <img src="macha.jpg">
                <h3>Green Matcha</h3>
                <h4>$3.50</h4>
            </div>
        </div>
        <footer>
            &copy; Moushmitha B (25014643)
        </footer>
    </body>
</html>

creator.html
<html>
    <head>
        <title>Golden Hour Cafe</title>
    </head>
    <style>
        body{
            background-image: url(cafe.jpg);
            background-repeat: no-repeat;
            background-size: cover;
        }
    
        .link{
            display: flex;
            position: fixed;
            top: 10px;
            justify-content: space-evenly;
            width: 800px;
            height: 55px;
            font-size: 21px;
            margin-left: 330px;
        }
        a{
            text-decoration: wavy;
            color: rgb(243, 187, 89);
            font-weight: bold;
        }    
        a:hover{
            color: rgb(112, 54, 18);
        }
        .name{
            font-size: 65px;
            margin-top: 100px;
            color: rgb(246, 173, 28);
            font-weight: bolder;
            text-align: center;
            font-style: italic;
        }
        .creator{
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 80px;
        }
        .creator-member{
            margin: 20px;
            text-align: center;
            background-color: wheat;
            padding: 15px;
            border-radius: 20px;
            width: 220px;
            margin-bottom:100;
        }
        .creator-member img{
            width: 200px;
            height: 200px;
            border-radius: 20px;
            object-fit: cover;
        }
        footer{
            text-align: center;
            color: wheat;
            background-color: black;
            padding: 5px;
            position: fixed;
            bottom: 0;
            left: 0;
            width: 100%;
        }
    </style>
    <body>
        <div class="name">
            <p>Golden Hour Cafe</p>
        </div>
        <div class="link">
            <a href="cafe.html">Cafe House</a>
            <a href="nuts.html">Cafe Offerings</a>
            <a href="creator.html">Cafe Creators</a>
            <a href="find.html">Find our Cafe</a>
        </div>
        <div class="creator">
            <div class="creator-member">
                <img src="profile.jpeg">
                <h2>Moushmitha B</h2>
                <p>Founder</p>
            </div>
            <div class="creator-member">
                <img src="Tae.jpg">
                <h2>Kim Taehyung</h2>
                <p>CO-Founder</p>
            </div>
            <div class="creator-member">
                <img src="Tay.jpg">
                <h2>Taylor Swift</h2>
                <p>Master Barista</p>
            </div>
            <div class="creator-member">
                <img src="DQ.jpg">
                <h2>Dulquer Salmaan</h2>
                <p>House Operation Keeper</p>
            </div>
            <div class="creator-member">
                <img src="Jiyo.jpg">
                <h2>Park Jihyo</h2>
                <p>Guest Experience Curator</p>
            </div>
        </div>
        <footer>
            &copy; Moushmitha B (25014643)
        </footer>
    </body>
</html>

find.html
<html>
    <head>
        <title>Golden Hour Cafe</title>
    </head>
    <style>
        body{
            background-image: url(cafe.jpg);
            background-repeat: no-repeat;
            background-size: cover;
        }
        .link{
            display: flex;
            position: fixed;
            top: 10px;
            justify-content: space-evenly;
            width: 800px;
            height: 55px;
            font-size: 21px;
            margin-left: 330px;
        }
        a{
            text-decoration: wavy;
            color: rgb(243, 187, 89);
            font-weight: bold;
        }    
        a:hover{
            color: rgb(112, 54, 18);
        }
        .name{
            font-size: 65px;
            margin-top: 100px;
            color: rgb(246, 173, 28);
            font-weight: bolder;
            text-align: center;
            font-style: italic;
        }
        .box{
            font-size: 25;
            text-align: center;
            border-style: outset;
            border-color: rgb(95, 54, 5);
            border-width: 6px;
            width: 600px;
            margin-bottom:50;
            margin-left: 450px;
            bottom: 300px;
            top: 50px;
            background-color: rgb(230, 160, 85);
        }
        footer{
            text-align: center;
            color: wheat;
            background-color: black;
            padding: 5px;
            position: fixed;
            bottom: 0;
            left: 0;
            width: 100%;
        }
    </style>
    <body>
        <div class="link">
            <a href="cafe.html">Cafe House</a>
            <a href="nuts.html">Cafe Offerings</a>
            <a href="creator.html">Cafe Creators</a>
            <a href="find.html">Find our Cafe</a>
        </div>
        <div class="name">
            <p>Golden Hour Cafe</p>
        </div>
        <div class="box">
            <h2>Our Whereabouts</h2>
            <p>Reach the House:</p>
            <p>21,Beach Road, Chennai</p>
            <p>Say Hello Through:+91 98476 23785</p>
            <p>Social Media:@ghourcafe</p>
        </div>
        <footer>
            &copy; Moushmitha B(25014643)
        </footer>
    </body>
</html>
```


## OUTPUT:
![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (45).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

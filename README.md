<!DOCTYPE html>
<html lang="en">
<head>
    <index.html></index.html> 
    <blog/index.html></blog>   
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles1.css">
    <title>Eman's - Webpage</title>
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Eman's - Webpage</title>
        <style>
            body {
                background-image: url('dubai2.jpg');
                background-color: rgb(255, 255, 255);
                color: #ffffff;
                background-size: cover;
                font-family: Arial, Helvetica, sans-serif;
                margin: 0;
                padding: 0;
            }
    
            .container {
                display: flex;
                flex-direction: column;
                min-height: 100vh;
            }
    
            header {
                background-color: #000000;
                color: #e100fa;
                padding: 15px 0;
                text-align: center;
            }
    
            main {
                padding: 20px;
                text-align: center;
            }
    
            section {
                margin-bottom: 40px;
                text-align: center;
            }
    
            img {
                max-width: 100%;
                height: auto;
                margin: 0 auto;
            }
    
            footer {
                background-color: #000000(255, 255, 255);
                color: #ffffff;
                text-align: center;
                padding: 10px 0;
                width: 100%;
                }
        </style>
    </head>
    <body>
        <div class="container">
            <header>
                 <a href="Eman's Webpage Part - 1.html">Home</a>
                 <a href="Eman's Webpage Part - 2.html">Blog</a>
            </header>
            <main>
                <section>
                    <h1>Eman Singh Takhar</h1>
                    <img src="Eman10.jpeg.jpeg" alt="Eman Singh Takhar">
                </section>
                <section>
                    <h2>About Me</h2>
                    <p>Student at BCIT - Information Technology</p>
                </section>
                <section>
                    <h2>Education</h2>
                    <ul>
                        <p>Highschool Diploma - Khalsa Secondary School</p>
                        <p>Currently Studying at BCIT - Information Technology</p>
                    </ul>
                </section>
                <section>
                    <h2>Courses at BCIT</h2>
                    <ul>
                        <p>BCIT Course 1 (COMP -1)</p>
                        <p>BCIT Course 2 (COMP -2)</p>
                        <p>BCIT Course 3 (COMP -3)</p>
                    </ul>
                </section>
                <section>
                    <h3>Contacts</h3>
                    <p>Email: etakhar1@my.bcit.ca</p>
                </section>
            </main>
            <footer>
                <p>&copy; 2023 Eman Takhar Homepage</p>
            </footer>
        </div>
    </body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <index.html></index.html> 
    <blog/index.html></blog>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eman Singh Takhar - Blog</title>
    <link rel="stylesheet" href="styles1.css">
    <style>
        body, html {
            height: 100%;
            margin: 0;
            display: flex;
            flex-direction: column;
        }

        body {
                background-image: url('newyork3.jpeg');
                color: #ffffff;
                background-size: cover;
                font-family: Arial, Helvetica, sans-serif;
                margin: 0;
                padding: 0;
            }
    
            .container {
                display: flex;
                flex-direction: column;
                min-height: 100vh;
            }
    
            header {
                background-color: #000000;
                color: #ffffff;
                padding: 15px 0;
                text-align: center;
            }
    
            main {
                padding: 20px;
                text-align: center;
            }
    
            section {
                margin-bottom: 40px;
                text-align: center;
            }
    
            img {
                max-width: 100%;
                height: auto;
                margin: 0 auto;
            }
    
            footer {
                background-color: #ffffff(255, 255, 255);
                color: #ffffff;
                text-align: center;
                padding: 10px 0;
                width: 100%;
            }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <a href="Eman's Webpage Part - 1.html">Home</a>
            <a href="Eman's Webpage Part - 2.html">Blog</a>
        </header>
        <main>
            <section>
                <h1>Eman Singh Takhar - Webpage</h1>
            </section>
               <section class="favorites">
                   <ul>
                        <h2>Favorite Soccer Player</h2>
                        <img src="cr7012.png" alt="Cristiano Ronaldo">
                        <h2>Favorite Artist</h2>
                        <img src="sidhumoosewala12.png" alt="Sidhu Moose Wala">
                        <h2>Favourite Car</h2>
                        <img src="lambo1234.png" alt="Lamborghini Aventador">
                   </ul>
               </section>
           </main>
           <footer>
            <p>&copy; 2023 Eman Takhar Webpage</p>
            </footer>
    </div>
</body>
</html>

.wrapper {
    width: 500px;
    min-height: 500px;
    margin: 0 auto;
    text-align: center;
    background: url(images/bg-light.png) no-repeat;
    padding-top: 20px;
}
body { 
    background: #ffffff url(images/bg.png) repeat;
    margin: 0;
    padding: 0;
    font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}

body, html {
    height: 100%;
    margin: 0;
    padding: 0;
    text-align: center;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

.container {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

header {
    background-color: #ffffff;
    color: rgb(255, 255, 255);
    padding: 10px 0;
    
}

.content {
    max-width: 500px;
    margin: 0 auto;
    padding: 20px;
    flex: 1;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav ul li {
    margin-right: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

footer {
    background-color: #000000;
    color: rgb(255, 255, 255);
    text-align: center;
    padding: 10px 0;
    width: 100%;
}

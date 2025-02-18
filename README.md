# online-cv
HTML Skills Challenge Challenge: Create an HTML5 structure for personal Online CV webpage that contains the following elements.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online CV</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        header {
            font-size: 18px;
            margin-bottom: 10px;
        }
        ul {
            list-style-type: disc;
        }
        ul li a {
            text-decoration: none;
            color: purple;
        }
        .image-container {
            text-align: center;
            margin: 20px 0;
        }
        .image-container img {
            width: 150px; /* Adjust size as needed */
            height: 150px;
        }
        .page-content {
            border: 1px solid black;
            padding: 10px;
            margin-top: 10px;
        }
        h1 {
            font-size: 28px;
        }
        #about, #education, #skills, #portfolio, #contact {
            margin-bottom: 5px;
        }
        footer {
            margin-top: 20px;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <header>
        <p>I am header with an unordered list of hyperlinks</p>
        <ul>
            <li><a href="#about">I am About link and my href value is #about</a></li>
            <li><a href="#education">I am Education link and my href value is #education</a></li>
            <li><a href="#skills">I am Skills link and my href value is #skills</a></li>
            <li><a href="#portfolio">I am Portfolio link and my href value is #portfolio</a></li>
            <li><a href="#contact">I am Contact link and my href value is #contact</a></li>
        </ul>
    </header>

    <div class="image-container">
        <img src="dan.png" alt="Custom Image">
        <p>I am an image and I'm all by myself</p>
    </div>

    <div class="page-content">
        <p>I am division with class equal to page-content that encloses all other division elements below</p>
        
        <h1>Hello! I am a text with the largest heading</h1>

        <div id="about">I am division with id equal to about</div>
        <div id="education">I am division with id equal to education</div>
        <div id="skills">I am division with id equal to skills</div>
        <div id="portfolio">I am division with id equal to portfolio</div>
        <div id="contact">I am division with id equal to contact</div>

        <footer>I am a footer the last section of this page</footer>
    </div>

</body>
</html>

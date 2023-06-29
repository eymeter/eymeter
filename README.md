<!DOCTYPE html>
<html>
<head>
    <title>About Me</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        h1, h2 {
            color: #333;
        }

        p {
            font-size: 18px;
            line-height: 1.6;
        }

        .profile-image {
            max-width: 200px;
            border-radius: 50%;
        }

        .experience {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-top: 20px;
        }

        .experience div {
            display: flex;
            align-items: center;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .experience img {
            width: 30px;
            height: 30px;
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>About Me</h1>
        <img class="profile-image" src="your-image-url" alt="Your Name">
        <p>Hello! I'm [Your Name]. I'm a [Your Profession] based in [Your Location]. I have a passion for [Your Passion].</p>
        <p>You can check out my work on <a href="your-github-url">GitHub</a> or reach me at <a href="mailto:your-email">your-email</a>.</p>

        <h2>Experiences</h2>
        <div class="experience">
            <div>
                <img src="python-logo-url" alt="Python">
                <span>Python</span>
            </div>
            <div>
                <img src="html-logo-url" alt="HTML">
                <span>HTML</span>
            </div>
            <div>
                <img src="css-logo-url" alt="CSS">
                <span>CSS</span>
            </div>
            <div>
                <img src="js-logo-url" alt="JavaScript">
                <span>JavaScript</span>
            </div>
            <div>
                <img src="nim-logo-url" alt="Nim">
                <span>Nim</span>
            </div>
            <div>
                <img src="cpp-logo-url" alt="C++">
                <span>C++</span>
            </div>
        </div>
    </div>
</body>
</html>

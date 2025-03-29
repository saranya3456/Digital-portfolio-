<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saranya - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f1f1f1;
        }
        header {
            background-color: #b6ff00;
            padding: 20px;
            text-align: center;
            color: white;
        }
        nav {
            background-color: #d81b60;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            padding: 20px;
        }
        .section {
            background-color: white;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 20px;
            border: 3px solid #d81b60;
        }
        footer {
            background-color: #212121;
            color: white;
            text-align: center;
            padding: 10px;
        }
        .resume-button {
            background-color: black;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Saranya</h1>
        <p>BSc Computer Science Student</p>
    </header>

    <nav>
        <a href="#">About</a>
        <a href="#">Education</a>
        <a href="#">Skills</a>
        <a href="#">Projects</a>
        <a href="#">Resume</a>
    </nav>

    <div class="container">
        <div class="section">
            <h2>About Me</h2>
            <p>I am currently pursuing 2nd year BSc Computer Science.</p>
        </div>

        <div class="section">
            <h2>Education</h2>
            <p>BSc Computer Science - 2nd Year</p>
        </div>

        <div class="section">
            <h2>Skills</h2>
            <ul>
                <li>Python</li>
                <li>HTML & CSS</li>
                <li>JavaScript</li>
                <li>C++</li>
                <li>Data Structures</li>
                <li>Problem Solving</li>
            </ul>
        </div>

        <div class="section">
            <h2>Projects</h2>
            <ul>
                <li><a href="#">Project 1</a></li>
                <li><a href="#">Project 2</a></li>
                <li><a href="#">Project 3</a></li>
            </ul>
        </div>

        <div class="section">
            <h2>Resume</h2>
            <button class="resume-button">Download CV</button>
        </div>
    </div>

    <footer>
        © 2025 Saranya
    </footer>
</body>
</html

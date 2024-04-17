<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
        }

        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

        .about-me {
            background-color: #fff;
            padding: 20px;
            border-radius: 5px;
            margin-bottom: 20px;
        }

        .page-links {
            display: flex;
            justify-content: space-between;
            padding: 10px 0;
        }

        .page-link {
            background-color: #fff;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            color: #333;
            transition: background-color 0.3s ease;
        }

        .page-link:hover {
            background-color: #ddd;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="about-me">
            <h2>About Me</h2>
            <p>Write a paragraph about yourself here...</p>
        </div>
        
        <div class="page-links">
            <a href="education.html" class="page-link">Education</a>
            <a href="awards.html" class="page-link">Awards</a>
            <!-- Add more page links as needed -->
        </div>
    </div>
</body>
</html>

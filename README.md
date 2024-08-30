<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .header h1 {
            margin: 0;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .hero {
            text-align: center;
            margin-bottom: 40px;
        }
        .hero h2 {
            margin-bottom: 20px;
            font-size: 2.5em;
        }
        .hero p {
            font-size: 1.2em;
            color: #555;
        }
        .cta-button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007bff;
            color: white;
            text-decoration: none;
            font-size: 1.2em;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .cta-button:hover {
            background-color: #0056b3;
        }
        .features {
            display: flex;
            justify-content: space-around;
            text-align: center;
        }
        .feature-item {
            width: 30%;
            padding: 20px;
        }
        .feature-item h3 {
            margin-bottom: 10px;
            font-size: 1.5em;
        }
        .feature-item p {
            font-size: 1em;
            color: #555;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Welcome to Our Landing Page</h1>
    </div>

    <div class="container">
        <div class="hero">
            <h2>Your Solution to [Problem/Need]</h2>
            <p>Discover how we can help you achieve your goals with our amazing product.</p>
            <a href="#" class="cta-button">Get Started</a>
        </div>

        <div class="features">
            <div class="feature-item">
                <h3>Feature 1</h3>
                <p>Describe the first feature here. Explain why it's great and how it benefits the user.</p>
            </div>
            <div class="feature-item">
                <h3>Feature 2</h3>
                <p>Describe the second feature here. Show how it solves the user's problem.</p>
            </div>
            <div class="feature-item">
                <h3>Feature 3</h3>
                <p>Describe the third feature here. Highlight its unique value.</p>
            </div>
        </div>
    </div>

    <div class="footer">
        <p>&copy; 2024 Your Company. All rights reserved.</p>
    </div>
</body>
</html>


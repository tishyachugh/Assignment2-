<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather App Demo</title>
    <style>
        /* Reset and Styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #74EBD5, #ACB6E5);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #444;
        }
        .container {
            text-align: center;
            background: #ffffff;
            padding: 50px;
            width: 90%;
            max-width: 600px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            border-radius: 12px;
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .container:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.3);
        }
        h1 {
            font-size: 2.5rem;
            color: #3498db;
            margin-bottom: 20px;
        }
        .btn {
            background: #2ecc71;
            color: #fff;
            padding: 12px 30px;
            font-size: 18px;
            border: none;
            border-radius: 8px;
            cursor: pointer;
            transition: background 0.3s, transform 0.2s;
        }
        .btn:hover {
            background: #27ae60;
            transform: scale(1.1);
        }
        .collaborators {
            margin-top: 30px;
            font-size: 16px;
            color: #555;
        }
        .collaborators span {
            font-weight: bold;
            color: #2c3e50;
        }
        /* Stylish Footer */
        .footer {
            margin-top: 40px;
            font-size: 14px;
            color: #777;
        }
        .footer a {
            color: #3498db;
            text-decoration: none;
            transition: color 0.3s;
        }
        .footer a:hover {
            color: #1abc9c;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Weather App Demo 🌦️</h1>
    <button class="btn" onclick="alert('Button Clicked!')">Explore Weather</button>

    <!-- Collaborators Section -->
    <div class="collaborators">
        <p>👥 <span>Collaborators:</span> Ritika, Riva, Tishya, Yakshi</p>
    </div>

    <!-- Footer -->
    <div class="footer">
        Made with 💙 by <a href="https://github.com/your-github-profile" target="_blank">Your Team</a>
    </div>
</div>

</body>
</html>


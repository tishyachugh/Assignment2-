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
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #f4f4f4, #d7e1ec);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #333;
        }
        .container {
            text-align: center;
            background: #fff;
            padding: 40px;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            transition: transform 0.3s;
        }
        .container:hover {
            transform: scale(1.05);
        }
        h1 {
            color: #3498db;
            margin-bottom: 20px;
        }
        .btn {
            background: #2ecc71;
            color: white;
            padding: 12px 25px;
            font-size: 18px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }
        .btn:hover {
            background: #27ae60;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Welcome to My Weather App 🚀</h1>
    <button class="btn" onclick="alert('Button Clicked!')">Click Me!</button>
</div>

</body>
</html>




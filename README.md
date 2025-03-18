# 🌟 Weather App

## 📌 Description
The **Weather App** is a web-based application that provides **real-time weather updates**, forecasts, and alerts. It allows users to search for weather details by **city name** or **PIN code** and offers a **5-day weather forecast**. The app includes features like:
- 🌤️ **Dynamic background images** that change based on the weather condition.  
- 📍 **Auto-detect location** using the Geolocation API.  
- 🕰️ **Real-time date and time display**.  
- 📊 **Interactive charts** to visualize weather data.  
- 📱 **PWA functionality** for offline access and installability.  

---

## 🎨 **Demo Preview**
Here is a simple **HTML & CSS snippet** from the project:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather App Demo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
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
            padding: 40px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            border-radius: 12px;
        }
        .btn {
            background: #2ecc71;
            color: white;
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
    </style>
</head>
<body>

<div class="container">
    <h1>Weather App Demo 🌦️</h1>
    <button class="btn" onclick="alert('Button Clicked!')">Explore Weather</button>

    <div class="collaborators">
        <p>👥 <span>Collaborators:</span> Ritika, Riva, Tishya, Yakshi</p>
    </div>
</div>

</body>
</html>



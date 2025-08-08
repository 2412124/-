<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <title>הרב ליאור לוי דף הבית</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #f0f4f8, #dbeafe);
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
        }
        h1 {
            margin-top: 30px;
            font-size: 2.2rem;
            color: #1e3a8a;
            text-shadow: 1px 1px 2px rgba(0,0,0,0.1);
        }
        .video-container {
            margin-top: 20px;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            max-width: 900px;
            width: 90%;
        }
        iframe {
            width: 100%;
            height: 250px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.2);
        }
        .contact, .donate {
            margin-top: 30px;
            padding: 15px;
            background-color: #1e3a8a;
            color: white;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            display: inline-block;
        }
        footer {
            margin-top: auto;
            padding: 15px;
            font-size: 0.9rem;
            color: #555;
        }
    </style>
</head>
<body>
    <h1>הרב ליאור לוי דף הבית</h1>

    <!-- סרטונים מיוטיוב -->
    <div class="video-container">
        <iframe src="https://www.youtube.com/embed/סרטון1" frameborder="0" allowfullscreen></iframe>
        <iframe src="https://www.youtube.com/embed/סרטון2" frameborder="0" allowfullscreen></iframe>
    </div>

    <!-- כפתורי קשר ותרומה -->
    <a href="tel:0535353745" class="contact">📞 צור קשר: 053-5353745</a>
    <a href="tel:0546692050" class="donate">💖 לתרומות על ספר הרב: 054-6692050</a>

    <footer>© כל הזכויות שמורות - הרב ליאור לוי</footer>
</body>
</html>
 

<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>הרב ליאור לוי</title>
<style>
  body {
    margin: 0; font-family: Arial, sans-serif;
    background: #fff;
    color: #222;
  }
  header {
    background: #f5f5f5;
    padding: 20px 10px;
    text-align: center;
    font-size: 28px;
    font-weight: bold;
    box-shadow: 0 2px 5px rgb(0 0 0 / 0.1);
    position: fixed;
    top: 0; left: 0; right: 0;
    z-index: 1000;
  }
  nav {
    background: #fff;
    display: flex;
    justify-content: center;
    gap: 30px;
    padding: 12px 0;
    position: fixed;
    top: 68px; /* מתחת לכותרת */
    width: 100%;
    box-shadow: 0 2px 5px rgb(0 0 0 / 0.05);
    z-index: 999;
  }
  nav a {
    text-decoration: none;
    color: #333;
    font-weight: 600;
    font-size: 18px;
    transition: color 0.3s;
  }
  nav a:hover {
    color: #0066cc;
  }
  .banner {
    margin-top: 120px; /* מקום לכותרת ותפריט */
    width: 100%;
    height: 300px;
    background: url('https://via.placeholder.com/1200x300?text=תמונת+באנר+זמנית') center/cover no-repeat;
  }
  .intro-text {
    text-align: center;
    font-size: 24px;
    padding: 30px 15px;
    max-width: 700px;
    margin: 0 auto 50px auto;
  }
  section {
    max-width: 900px;
    margin: 0 auto 80px auto;
    padding: 0 15px;
  }
  section h2 {
    font-size: 28px;
    border-bottom: 3px solid #0066cc;
    padding-bottom: 6px;
    margin-bottom: 25px;
  }
  /* טקסט פשוט לאודות */
  #about p {
    font-size: 18px;
    line-height: 1.6;
  }
  [/* חלק שיעורים - נניח טקסט */](https://youtube.com/shorts/TnZJujLwQ9E) סרטון מחזק!!!https://youtube.com/shorts/tGLXBWt94bw 
  #lessons p {
    font-size: 18px;
    line-height: 1.6;
  }
 ליצירת קשר על ספר הרב או פרטים אחרים:0535353745
  form {
    max-width: 500px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 15px;
  }
  input, textarea {
    padding: 10px;
    font-size: 16px;
    border: 1.5px solid #ccc;
    border-radius: 5px;
    resize: vertical;
  }
  button {
    background-color: #0066cc;
    border: none;
    color: white;
    padding: 14px 20px;
    font-size: 18px;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s;
  }
  button:hover {
    background-color: #004999;
  }
  .contact-info {
    text-align: center;
    margin-top: 15px;
    font-size: 18px;
    color: #333;
  הרשמו לערוץ הרב ברשתות החברתיות, תודה!
  .social {
    text-align: center;
    margin-top: 40px;
  }
  .social a {
    margin: 0 12px;
    display: inline-block;
  }
  .social img {
    width: 36px;
    height: 36px;
    filter: grayscale(0);
    transition: filter 0.3s;
  }
  .social a:hover img {
    filter: brightness(0.7);
  }
  /* גלילה חלקה */
  html {
    scroll-behavior: smooth;
  }
  /* רספונסיבי */
  @media (max-width: 600px) {
    nav {
      gap: 15px;
      font-size: 16px;
    }
    header {
      font-size: 22px;
    }
    .banner {
      height: 180px;
    }
    .intro-text {
      font-size: 20px;
    }
  }
</style>
</head>
<body>

<header>הרב ליאור לוי</header>

<nav>
  <a href="#about">אודות</a>
  <a href="#lessons">שיעורים</a>
  <a href="#contact">יצירת קשר</a>
</nav>

<div class="banner"></div>

<div class="intro-text">ברוכים הבאים לאתר הרב ליאור לוי</div>

<section id="about">
  <h2>אודות</h2>
  <p>
    הרב ליאור לוי רב ומעביר שיעורים בעיר קריית עקרון, מחבר ספרי חוזר לאור, ויש לרב שיעורי תורה ביוטיוב פייסבוק וכו' הרב מרצה למגזר הדתי, חרדי, חילוני, מתחזק, בקיצור לכולם!
  </p>
</section>

<section id="lessons">
  <h2>שיעורים</h2>
  <p>
    [/* חלק שיעורים - נניח טקסט */](https://youtube.com/shorts/TnZJujLwQ9E) סרטון מחזק!!!https://youtube.com/shorts/tGLXBWt94bw 
  </p>
</section>

<section id="contact">
  <h2>יצירת קשר</h2>
  <form onsubmit="alert('תודה! ההודעה נשלחה.'); return false;">
    <input type="text" name="name" placeholder="שם מלא" required />
    <input type="email" name="email" placeholder="אימייל" required />
    <textarea name="message" rows="5" placeholder="הודעה" required></textarea>
    <button type="submit">שלח</button>
  </form>
  <div class="contact-info">
    טלפון ליצירת קשר: 053-5353745
  </div>
  <div class="social">
    <a href="https://youtube.com/channel/UCKmVkIJOgpG99tZyYnqOBMA?si=gX9vMjDqkQVwRyQH" target="_blank" rel="noopener noreferrer" title="יוטיוב">
      <img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" alt="יוטיוב" />
    </a>
    <a href="https://www.facebook.com/groups/4194997850786708/" target="_blank" rel="noopener noreferrer" title="פייסבוק">
      <img src="https://cdn-icons-png.flaticon.com/512/1384/1384053.png" alt="פייסבוק" />
    </a>
  </div>
</section>

</body>
</html>

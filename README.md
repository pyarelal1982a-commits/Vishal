<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>ALBstore</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f2f2f2;
    }

    header {
      background: #0a1cff;
      color: white;
      padding: 15px;
      text-align: center;
      font-size: 28px;
      font-weight: bold;
    }

    .container {
      max-width: 900px;
      margin: 20px auto;
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.2);
    }

    .profile {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      align-items: center;
    }

    .profile img {
      width: 250px;
      border-radius: 10px;
    }

    .details h2 {
      margin-top: 0;
      color: #0a1cff;
    }

    .details p {
      font-size: 16px;
      line-height: 1.6;
    }

    .youtube {
      margin-top: 30px;
      padding: 20px;
      background: #f9f9f9;
      border-radius: 10px;
      text-align: center;
    }

    .youtube h3 {
      color: #ff0000;
    }

    .youtube-btn {
      display: inline-block;
      margin-top: 15px;
      padding: 12px 25px;
      background: #ff0000;
      color: white;
      text-decoration: none;
      font-size: 18px;
      border-radius: 25px;
      font-weight: bold;
    }

    .youtube-btn:hover {
      background: #cc0000;
    }

    footer {
      text-align: center;
      padding: 10px;
      background: #222;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <header>
    ALBstore
  </header>

  <div class="container">

    <!-- PROFILE SECTION -->
    <div class="profile">
      <img src="photo.jpg" alt="My Photo">

      <div class="details">
        <h2>My Name is Vishal</h2>
        <p>
          Main ek <b>Game Developer</b> hoon.  
          Main different type ke <b>interesting aur high-quality games</b> banata hoon.
        </p>
        <p>
          Mujhe coding aur game development bahut pasand hai  
          aur main future me <b>professional game developer</b> banna chahta hoon.
        </p>
      </div>
    </div>

    <!-- YOUTUBE SECTION -->
    <div class="youtube">
      <h3>🎬 My YouTube Channel</h3>

      <p>
        Mere YouTube channel par main <b>Avengers videos</b> dalta hoon.  
        Main ek <b>proud Avengers fan</b> hoon aur mujhe  
        Avengers ke characters, scenes aur edits banana bahut pasand hai.
      </p>

      <p>
        Iske saath-saath main <b>game development</b>,  
        <b>Godot tutorials</b> aur <b>coding related content</b> bhi share karta hoon.  
        Agar aapko Avengers, games aur coding pasand hai  
        to mera channel aapke liye perfect hai.
      </p>

      <a class="youtube-btn"
         href="https://youtube.com/@alb_attitude?si=KOq6HX80iZuEmpZU"
         target="_blank">
         Subscribe on YouTube
      </a>
    </div>

  </div>

  <footer>
    © 2026 ALBstore | Game Developer | Avengers Fan | YouTuber
  </footer>

</body>
</html>

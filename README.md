<html>
<head>
  <style>
    /* Reset & body */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  display: flex;
  color: white;
  text-align: right; /* keep text right-aligned */
  
  /* Blue icy gradient */
  background: linear-gradient(135deg, #0a2a43, #0d4f7c, #1e81ce);
  background-attachment: fixed;
  background-size: cover;
  position: relative;
  overflow: hidden;
}

/* Blurry overlay */
body::before {
  content: '';
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  backdrop-filter: blur(6px);
  background: rgba(0,0,0,0.3);
  z-index: -1;
}

/* Ice-like shapes */
body::after {
  content: '';
  position: absolute;
  top: 0; left: 0;
  width: 100%; height: 100%;
  
  /* Abstract black icy shards with white wave accents */
  background: 
    repeating-radial-gradient(circle at 20% 30%, rgba(0,0,0,0.7) 0, rgba(0,0,0,0.7) 2px, transparent 3px, transparent 80px),
    repeating-radial-gradient(circle at 70% 60%, rgba(0,0,0,0.8) 0, rgba(0,0,0,0.8) 2px, transparent 3px, transparent 90px),
    repeating-linear-gradient(45deg, rgba(255,255,255,0.2) 0, rgba(255,255,255,0.2) 2px, transparent 3px, transparent 40px);
  opacity: 0.5;
  z-index: -1;
}


    /* Sidebar */
    .sidebar {
      position: fixed;
      top: 0;
      left: 0;
      width: 220px; /* slightly smaller */
      height: 100vh;
      background: rgba(0,0,0,0.6); /* frosted glass effect */
      backdrop-filter: blur(10px);
      border-right: 1px solid rgba(255,255,255,0.2);
      padding: 20px;
      box-shadow: 2px 0 12px rgba(0,0,0,0.3);
      text-align: right; /* keep sidebar text right-aligned */
    }

    .sidebar h2 {
      margin-top: 0;
      font-size: 22px;
      color: #00bfff;
    }

    .sidebar a {
      display: block;
      margin: 10px 0;
      text-decoration: none;
      color: #ffffff;
      font-weight: bold;
      transition: all 0.2s ease;
    }

    .sidebar a:hover {
      background: rgba(255,255,255,0.2);
      color: #00ffff;
      padding-left: 5px;
    }

    /* Main content */
    .content {
      margin-left: 220px; /* match sidebar width */
      padding: 30px;
      max-width: calc(100% - 220px);
      text-align: right; /* keep content aligned right */
      background: rgba(0,0,0,0.3); /* subtle frosted effect for content */
      backdrop-filter: blur(6px);
      border-radius: 10px;
    }

    .content h2 {
      color: royalblue;
      margin-bottom: 15px;
    }

    .content p {
      color: white;
      margin-bottom: 12px;
    }

    .content img {
      max-width: 100%;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.5);
      display: block;
      margin-left: auto; /* keep image on the right */
      }
  </style>    
</head>
<body>

  <!-- Sidebar -->
  <div class="sidebar">
    <h2>Navigation</h2>
    <a href="https://smarmyleague.wordpress.com/" target="_blank">SMALL MEDIUM ARMY LEAGUE</a>
    <a href="https://youtube.com/@arcticvikings?si=D4ylBQh1vhXm7Xrs" target="_blank">YouTube channel</a>
    <a href="https://discord.gg/u2E4caAQpX" target="_blank">Discord server</a>
    <a href="https://cpabattleground.com" target="_blank">CPAB (game)</a>
    <a href="https://waddleleague.wordpress.com/" target="_blank">waddle league</a>
  </div>

  <!-- Main content -->
  <div class="content">
    <h2>Recent Events Week 2</h2>
 
  <p>Asia/Ausia event</p>
    <p style="color: red;">MAX 2</p>
    <img src="https://cdn.discordapp.com/attachments/1405700987422769222/1409629650510020770/Screenshot_20250825_215301_com.brave.browser.jpg?ex=68b3596a&is=68b207ea&hm=bf9122e6c403b59c05e85be1b264c466215431cb0548d7eaf65d5e7f8eddd6dd&" alt="error" width="400">

<p>formation-event</p>  
<p style="color: red;"> MAX 3<p>
<img src="https://cdn.discordapp.com/attachments/1405700987422769222/1409995707393380443/Screenshot_2025-08-26_160446.png?ex=68b35cd5&is=68b20b55&hm=03d4471479fe9792a471f612a5291cdd9c3d0efc782434c1d75d71e3410eb6cd&" alt="error" width="400">

<p>Teaching the new how to play</p>
    <p style="color: red;">MAX 2</p>
<img src="https://cdn.discordapp.com/attachments/1405700987422769222/1411102107783659611/Screenshot_20250829_231433_com.brave.browser.jpg?ex=68b36ebf&is=68b21d3f&hm=c036c7144cdbfbb977c4e2a7a93485a6705f724537d299cabcd2862d2f059ecf&" alt="error" width="400">
</div>
  </body>
</html>



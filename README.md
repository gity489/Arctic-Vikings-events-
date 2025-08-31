<html>
<head>
  <style>
/* Reset & body */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
text-align: center;
}

body {
  font-family: Arial, sans-serif;
  display: flex;
  flex-direction: column;
  color: white;
  text-align: right;
  
  /* Arctic ice gradient */
  background: linear-gradient(180deg, #0a2740, #124e89, #1c7ed6);
  background-attachment: fixed;
  background-size: cover;
  position: relative;
  min-height: 100vh;
}

/* Frosty blur overlay */
body::before {
  content: '';
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  backdrop-filter: blur(6px);
  background: rgba(0, 30, 60, 0.45); /* icy dark blue tint */
  z-index: -1;
}

/* Arctic ice cracks + snowy waves */
body::after {
  content: '';
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  
  background: 
    /* black ice cracks */
    repeating-linear-gradient(60deg, rgba(0,0,0,0.5) 0px, rgba(0,0,0,0.5) 2px, transparent 3px, transparent 80px),
    repeating-linear-gradient(-60deg, rgba(0,0,0,0.4) 0px, rgba(0,0,0,0.4) 2px, transparent 3px, transparent 80px),
    
    /* white snowy waves */
    repeating-radial-gradient(circle at 20% 40%, rgba(255,255,255,0.2) 0px, rgba(255,255,255,0.2) 2px, transparent 3px, transparent 100px),
    repeating-radial-gradient(circle at 80% 70%, rgba(255,255,255,0.15) 0px, rgba(255,255,255,0.15) 2px, transparent 3px, transparent 120px);
  
  opacity: 0.55;
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
    <a href="https://waddleleague.wordpress.com/" target="_blank">waddle league</a>
  </div>

  <!-- Main content -->
  <div class="content">
    <h2>Recent Events Week 3</h2>
 
  <p>unscheduled event</p>
    <p style="color: red;">MAX 3</p>
    <img src="https://cdn.discordapp.com/attachments/1405700987422769222/1411764689993728160/Screenshot_2025-08-31_131402.png?ex=68b5d7d3&is=68b48653&hm=4c5ca2e719ca8b9e3cd6df52c1649e5e3e17e01ca2a1ab57f5f9e5d9c5202349&" alt="error" width="400">
</div>
  </body>
</html>



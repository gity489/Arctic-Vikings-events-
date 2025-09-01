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
      flex-direction: column;
      color: white;
      text-align: center; /* center text everywhere */
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
      background: rgba(0, 30, 60, 0.45);
      z-index: -1;
    }

    /* Arctic ice cracks + snowy waves */
    body::after {
      content: '';
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background:
        repeating-linear-gradient(60deg, rgba(0,0,0,0.5) 0px, rgba(0,0,0,0.5) 2px, transparent 3px, transparent 80px),
        repeating-linear-gradient(-60deg, rgba(0,0,0,0.4) 0px, rgba(0,0,0,0.4) 2px, transparent 3px, transparent 80px),
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
      width: 220px;
      height: 100vh;
      background: rgba(0,0,0,0.6);
      backdrop-filter: blur(10px);
      border-right: 1px solid rgba(255,255,255,0.2);
      padding: 20px;
      box-shadow: 2px 0 12px rgba(0,0,0,0.3);
      text-align: right;
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
      margin-left: 220px;
      padding: 30px;
      max-width: calc(100% - 220px);
      text-align: center; /* center everything */
      background: rgba(0,0,0,0.3);
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
      margin: 0 auto; /* center image */
    }

    /* Responsive: Mobile */
    @media (max-width: 768px) {
      .sidebar {
        position: relative;
        width: 100%;
        height: auto;
        border-right: none;
        border-bottom: 1px solid rgba(255,255,255,0.2);
        text-align: center;
      }

      .content {
        margin-left: 0;
        max-width: 100%;
      }
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
    <img src="https://cdn.discordapp.com/attachments/1405700987422769222/1411764689993728160/Screenshot_2025-08-31_131402.png?ex=68b72953&is=68b5d7d3&hm=69dcb4263f388cc7a3187217af525c7ed5114e0d43df0613fba4e891a7153b4a&" alt="event screenshot" width="400">
  </div>
</body>
</html>

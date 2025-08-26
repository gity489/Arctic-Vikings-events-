<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>AVK Events</title>
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
      background: url('https://cdn.discordapp.com/attachments/1349427999568691271/1409730170197119037/file_00000000f54861f5a19d5d5255e98132.png') no-repeat center center fixed;
      background-size: cover;
    }

    /* Blurry overlay */
    body::before {
      content: '';
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      backdrop-filter: blur(8px);
      background: rgba(0,0,0,0.4);
      z-index: -1;
    }

    /* Sidebar */
    .sidebar {
      position: fixed;
      top: 0;
      left: 0;
      width: 200px;          /* <-- change this number to make it smaller/bigger */
      height: 100vh;
      background: rgba(0,0,0,0.7);
      border-right: 1px solid rgba(255,255,255,0.2);
      padding: 20px;
    }

    .sidebar h2 {
      font-size: 18px;
      color: #00bfff;
      margin-bottom: 15px;
    }

    .sidebar a {
      display: block;
      margin: 12px 0;
      text-decoration: none;
      color: #fff;
      font-weight: bold;
      transition: 0.2s;
    }

    .sidebar a:hover {
      color: cyan;
      padding-left: 5px;
    }

    /* Main content */
    .content {
      margin-left: 200px;     /* <-- must match sidebar width */
      padding: 20px;
      flex: 1;
    }

    .content h2 {
      color: royalblue;
      margin-bottom: 15px;
    }

    .content p {
      margin-bottom: 12px;
    }

    .content img {
      max-width: 100%;
      border-radius: 8px;
      display: block;
      margin-bottom: 20px;
    }
  </style>
</head>
<body>

  <!-- Sidebar -->
  <div class="sidebar">
    <h2>Navigation</h2>
    <a href="https://smarmyleague.wordpress.com/" target="_blank">SMALL MEDIUM ARMY LEAGUE</a>
    <a href="https://youtube.com/@arcticvikings" target="_blank">YouTube channel</a>
    <a href="https://discord.gg/u2E4caAQpX" target="_blank">Discord server</a>
    <a href="https://cpabattleground.com" target="_blank">CPAB (game)</a>
    <a href="https://waddleleague.wordpress.com/" target="_blank">Waddle league</a>
  </div>

  <!-- Main content -->
  <div class="content">
    <h2>Recent Events Week 2</h2>
    <p>Asia/Ausia event</p>
    <p style="color: red;">MAX 2</p>
    <img src="https://cdn.discordapp.com/attachments/1405700987422769222/1409629650510020770/Screenshot_20250825_215301_com.brave.browser.jpg" alt="event 1">

    <p>Formation Event</p>
    <p style="color: red;">MAX 3</p>
    <img src="https://cdn.discordapp.com/attachments/1405700987422769222/1409995914797650071/Screenshot_20250826_221942_com.huawei.himovie.overseas.jpg" alt="event 2">
</div>

</body>
</html>

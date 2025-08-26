
<html>
<head>
  <style>
    /* Body styles with background image */
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: white;
      display: flex;
      text-align: center;
      image-align: center;
      header-align: center;
      title-align: center;
    }
    

    /* Blurry background using a full-screen div */
    .background {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-image: url('https://cdn.discordapp.com/attachments/1349427999568691271/1409730170197119037/file_00000000f54861f5a19d5d5255e98132.png?ex=68ae7108&is=68ad1f88&hm=d0e3be8acf0c1020904d92bff20edf41d75077e9cadf569aa4e51a5141438566&');
      background-size: cover;
      background-position: center;
      filter: blur(8px);  /* this makes it blurry */
      z-index: -1; /* send behind everything */
    }

    /* Sidebar styles */
    .sidebar {
      position: fixed;
      top: 0;
      left: 0;
      width: 250px;
      height: 100vh;
      background: rgba(0,0,0,0.7); /* semi-transparent black */
      border-right: 1px solid #ddd;
      padding: 20px;
      box-shadow: 2px 0 8px rgba(0,0,0,0.3);
      text-align: center;
    }

    .sidebar h2 {
      margin-top: 0;
      font-size: 25px;
      color: #fff;
    }

    .sidebar a {
      display: block;
      margin: 12px 0;
      text-decoration: none;
      color: #00bfff;
      font-weight: bold;
    }

    .sidebar a:hover {
      text-decoration: underline;
    }

    /* Main content */
    .content {
      margin-left: 250px; 
      padding: 20px;
      max-width: calc(100% - 250px);
    }

    .content h2 {
      color: royalblue;
    }

    .content p {
      color: white;
    }
  </style>
</head>
<body>

  <!-- Blurry background -->
  <div class="background"></div>

  <!-- Sidebar -->
  <div class="sidebar">
    <h2>Navigation</h2>
    <a href="https://smarmyleague.wordpress.com/" target="_blank">SMALL MEDIUM ARMY LEAGUE</a>
    <a href="https://youtube.com/@arcticvikings?si=D4ylBQh1vhXm7Xrs" target="_blank">YouTube channel</a>
    <a href="https://discord.gg/u2E4caAQpX" target="_blank">Discord server</a>
    <a href="https://cpabattleground.com" target="_blank">CPAB (game)</a>
  </div>

  <!-- Main content -->
  <div class="content">
    <h2>Recent Events Week 2</h2>
    <p>Asia/Ausia event</p>
    <p style="color: red;">MAX 2</p>
    <img src="https://cdn.discordapp.com/attachments/1405700987422769222/1409629650510020770/Screenshot_20250825_215301_com.brave.browser.jpg?ex=68ae136a&is=68acc1ea&hm=d9cf62e26e03354f6c196e654faa9cc5c26cf9d7fabafe4a39377996060111f4&" alt="error" width="400">
  </div>

</body>
</html>

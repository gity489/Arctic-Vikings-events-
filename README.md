<!DOCTYPE html>
<html>
<head>
  <style>
    /* Body styles */
    body {
      margin: 0;
      background: repeating-linear-gradient(
        45deg,         /* angle of the stripes */
        black,         /* start color */
        black 10px,    /* stripe size */
        black 10px,     /* stripe start */
        blaxk 20px      /* stripe end */
      );
      color: white; 
      font-family: Arial, sans-serif;
      text-align: center;
      image-align: center;
    }

    /* Sidebar styles */
    .sidebar {
      position: fixed;      /* stays on the side */
      top: 0;
      left: 0;
      width: 220px;
      height: 100vh;        /* full screen height */
      background: white;
      border-right: 1px solid #ddd;
      padding: 20px;
      box-shadow: 2px 0 8px rgba(0,0,0,0.1);
      text-align: left;
    }

    .sidebar h2 {
      margin-top: 0;
      font-size: 20px;
      color: #333;
    }

    .sidebar a {
      display: block;
      margin: 12px 0;
      text-decoration: none;
      color: #007bff;
      font-weight: bold;
    }

    .sidebar a:hover {
      text-decoration: underline;
    }

    /* Push main content so it’s not behind sidebar */
    .content {
      margin-left: 240px; 
      padding: 20px;
    }
  </style>
</head>
<body>

  <!-- Sidebar -->
  <div class="sidebar">
    <h2>Navigation</h2>
    <a href="https://google.com" target="_blank">Google</a>
    <a href="https://youtube.com" target="_blank">YouTube</a>
    <a href="https://github.com" target="_blank">GitHub</a>
    <a href="https://example.com" target="_blank">Example</a>
  </div>

  <!-- Main content -->
  <div class="content">
    <h2 style="color: royalblue;">Recent Events Week 2</h2>
    <p>Asia/Ausia event</p>
    <p style="color: red;">MAX 2</p>
    <img src="https://cdn.discordapp.com/attachments/1405700987422769222/1409629650510020770/Screenshot_20250825_215301_com.brave.browser.jpg?ex=68ae136a&is=68acc1ea&hm=d9cf62e26e03354f6c196e654faa9cc5c26cf9d7fabafe4a39377996060111f4&" 
         alt="error" width="400">
  </div>

</body>
</html>

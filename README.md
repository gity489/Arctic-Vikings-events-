
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Arctic Vikings</title>

  <style>
    /* ====== Theme Vars ====== */
    :root{
      --accent: #00bfff;
      --accent-2: #00ffff;
      --ice-1: #0a2740;
      --ice-2: #124e89;
      --ice-3: #1c7ed6;
      --frost-bg: rgba(0, 30, 60, 0.45);
      --glass: rgba(0,0,0,0.6);
      --content-glass: rgba(0,0,0,0.3);
      --border: rgba(255,255,255,0.2);
      --text: #ffffff;
      --title: royalblue;
      --radius: 12px;
      --sidebar-w: 240px;
      --pad: 24px;
    }

    /* ====== Reset ====== */
    *, *::before, *::after { box-sizing: border-box; }
    html, body { margin: 0; padding: 0; }
    img { max-width: 100%; height: auto; display: block; }

    /* ====== Base ====== */
    body{
      font-family: Arial, sans-serif;
      color: var(--text);
      background: linear-gradient(180deg, var(--ice-1), var(--ice-2), var(--ice-3));
      background-attachment: fixed;
      min-height: 100vh;
      position: relative;
    }

    /* Frosty blur overlay */
    body::before{
      content:'';
      position: fixed; inset: 0;
      backdrop-filter: blur(6px);
      -webkit-backdrop-filter: blur(6px);
      background: var(--frost-bg);
      z-index: -1;
    }

    /* Arctic ice cracks + snowy waves */
    body::after{
      content:'';
      position: fixed; inset: 0;
      background:
        repeating-linear-gradient(60deg, rgba(0,0,0,0.5) 0 2px, transparent 3px 80px),
        repeating-linear-gradient(-60deg, rgba(0,0,0,0.4) 0 2px, transparent 3px 80px),
        repeating-radial-gradient(circle at 20% 40%, rgba(255,255,255,0.2) 0 2px, transparent 3px 100px),
        repeating-radial-gradient(circle at 80% 70%, rgba(255,255,255,0.15) 0 2px, transparent 3px 120px);
      opacity: .55;
      z-index: -1;
    }

    /* ====== Layout ====== */
    .sidebar{
      position: fixed;
      inset: 0 auto 0 0;
      width: var(--sidebar-w);
      height: 100vh;
      background: var(--glass);
      backdrop-filter: blur(10px);
      border-right: 1px solid var(--border);
      box-shadow: 2px 0 12px rgba(0,0,0,.3);
      padding: var(--pad);
      text-align: center; /* sidebar text centered too */
      overflow-y: auto;
    }

    .content{
      margin-left: var(--sidebar-w);
      padding: calc(var(--pad) + 8px);
      max-width: 1200px;
      background: var(--content-glass);
      backdrop-filter: blur(6px);
      border-radius: var(--radius);
      text-align: center; /* center content text */
      margin-right: auto;
    }

    /* ====== Sidebar bits ====== */
    .sidebar h2{
      margin: 0 0 10px 0;
      font-size: 22px;
      color: var(--accent);
    }
    .nav{
      display: grid;
      gap: 8px;
    }
    .nav a{
      text-decoration: none;
      color: var(--text);
      font-weight: bold;
      padding: 8px 10px;
      border-radius: 8px;
      transition: transform .15s ease, background .15s ease, color .15s ease;
      word-break: break-word;
    }
    .nav a:hover, .nav a:focus{
      background: rgba(255,255,255,.2);
      color: var(--accent-2);
      outline: none;
      transform: translateY(-2px);
    }

    /* ====== Content bits ====== */
    .content h2{
      margin: 0 0 12px 0;
      color: var(--title);
    }
    .content p{ margin: 0 0 10px 0; }
    .max-line{ color: red; font-weight: bold; }

    /* Image card */
    .card-img{
      border-radius: 10px;
      box-shadow: 0 6px 16px rgba(0,0,0,.45);
      margin: 20px auto 0 auto;
      width: min(100%, 520px);
    }

    /* ====== Tablet (<= 1024px): sidebar becomes top bar ====== */
    @media (max-width: 1024px){
      .sidebar{
        position: static;
        width: 100%;
        height: auto;
        border-right: none;
        border-bottom: 1px solid var(--border);
        box-shadow: none;
        text-align: center;
        padding-top: calc(var(--pad) + env(safe-area-inset-top, 0px));
      }
      .nav{
        display: flex;
        gap: 8px;
        flex-wrap: wrap;
        justify-content: center;
      }
      .nav a{ padding: 10px 12px; }
      .content{
        margin: 0;
        border-radius: 0;
        text-align: center;
      }
      .card-img{ margin: 20px auto; }
    }

    /* ====== Mobile (<= 600px) ====== */
    @media (max-width: 600px){
      :root{ --pad: 18px; }
      .sidebar h2{ font-size: 18px; }
      .nav a{ padding: 12px 14px; border-radius: 10px; }
      .content{ padding: calc(var(--pad) + 4px); }
      .content h2{ font-size: 20px; }
      .content p{ font-size: 16px; line-height: 1.4; }
    }
  </style>
</head>
<body>

  <!-- Sidebar / Top bar -->
  <aside class="sidebar">
    <h2 id="navTitle" contenteditable="true">Navigation</h2>
    <nav class="nav">
      <a href="https://smarmyleague.wordpress.com/" target="_blank" rel="noopener">SMALL MEDIUM ARMY LEAGUE</a>
      <a href="https://youtube.com/@arcticvikings?si=D4ylBQh1vhXm7Xrs" target="_blank" rel="noopener">YouTube channel</a>
      <a href="https://discord.gg/u2E4caAQpX" target="_blank" rel="noopener">Discord server</a>
      <a href="https://waddleleague.wordpress.com/" target="_blank" rel="noopener">Waddle League</a>
    </nav>
  </aside>

  <!-- Main content -->
  <main class="content">
    <h2 id="mainTitle" contenteditable="true">Recent Events Week 3</h2>
    <p id="eventText" contenteditable="true">unscheduled event</p>
    <p id="maxText" class="max-line" contenteditable="true">MAX 3</p>

    <img
      class="card-img"
      alt="Event screenshot"
      src="https://cdn.discordapp.com/attachments/1405700987422769222/1411764689993728160/Screenshot_2025-08-31_131402.png?ex=68b5d7d3&is=68b48653&hm=4c5ca2e719ca8b9e3cd6df52c1649e5e3e17e01ca2a1ab57f5f9e5d9c5202349&"
    />
  </main>

  <!-- Optional: save text edits per-device (localStorage) -->
  <script>
    const ids = ["navTitle","mainTitle","eventText","maxText"];
    ids.forEach(id => {
      const el = document.getElementById(id);
      if (!el) return;
      const saved = localStorage.getItem(id);
      if(saved!==null) el.textContent = saved;
      el.addEventListener("input",()=>{ localStorage.setItem(id, el.textContent); });
    });
  </script>

</body>
</html>

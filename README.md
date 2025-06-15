<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Miku ⚡ | Backend Dev in Progress</title>
  <link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&display=swap" rel="stylesheet"/>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Share Tech Mono', monospace;
    }
    body {
      background: #0a0a0a;
      color: #00fff7;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      padding: 2rem;
      text-align: center;
    }
    h1 {
      font-size: 3rem;
      animation: pulse 1.5s infinite;
    }
    h2 {
      color: #f0f0f0;
      margin-top: 0.5rem;
      font-weight: lighter;
    }
    .btn {
      margin-top: 2rem;
      padding: 1rem 2rem;
      background: transparent;
      border: 2px solid #00fff7;
      color: #00fff7;
      text-decoration: none;
      transition: 0.3s ease;
    }
    .btn:hover {
      background: #00fff7;
      color: #0a0a0a;
    }
    @keyframes pulse {
      0% { opacity: 0.6; }
      50% { opacity: 1; }
      100% { opacity: 0.6; }
    }
    footer {
      margin-top: 3rem;
      font-size: 0.85rem;
      color: #999;
    }
  </style>
</head>
<body>

  <h1>Miku ⚡</h1>
  <h2>Backend Dev in Progress</h2>
  <p style="margin-top:1rem; color:#ccc;">
    🧠 Writing clean code • Building smart apps • Learning in public
  </p>

  <a href="https://github.com/megabytis" class="btn" target="_blank">Visit My GitHub</a>

  <footer>Built with 💻 & caffeine · © 2025 Miku</footer>

</body>
</html>

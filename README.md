# thebillionshots
Instagram newletter
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>thebillionshots</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600&family=Inter:wght@400;500&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: radial-gradient(circle at top, #1a1a1a 0%, #000 60%);
      color: #fff;
      font-family: 'Inter', sans-serif;
    }

    .container {
      position: relative;
      text-align: center;
      padding: 24px;
      width: 100%;
      max-width: 420px;
    }

    .bg-letter {
      position: absolute;
      inset: 0;
      display: flex;
      align-items: center;
      justify-content: center;
      font-family: 'Playfair Display', serif;
      font-size: 420px;
      font-weight: 600;
      color: rgba(255,255,255,0.03);
      user-select: none;
      pointer-events: none;
    }

    h1 {
      position: relative;
      font-family: 'Playfair Display', serif;
      font-size: 42px;
      margin-bottom: 24px;
      z-index: 1;
    }

    form {
      position: relative;
      display: flex;
      gap: 10px;
      background: rgba(255,255,255,0.08);
      padding: 8px;
      border-radius: 14px;
      backdrop-filter: blur(8px);
      z-index: 1;
    }

    input[type="email"] {
      flex: 1;
      border: none;
      outline: none;
      background: transparent;
      color: #fff;
      padding: 14px 16px;
      font-size: 15px;
    }

    input::placeholder {
      color: rgba(255,255,255,0.6);
    }

    button {
      border: none;
      cursor: pointer;
      background: #f5c84c;
      color: #000;
      font-weight: 500;
      padding: 14px 20px;
      border-radius: 10px;
      display: flex;
      align-items: center;
      gap: 6px;
      font-size: 15px;
    }

    button:hover {
      background: #ffd766;
    }

    .subtext {
      position: relative;
      margin-top: 14px;
      font-size: 13px;
      color: rgba(255,255,255,0.6);
      z-index: 1;
    }

    @media (max-width: 480px) {
      h1 {
        font-size: 36px;
      }

      .bg-letter {
        font-size: 320px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="bg-letter">B</div>

    <h1>thebillionshots</h1>

    <form>
      <input type="email" placeholder="Enter your email" required />
      <button type="submit">Join →</button>
    </form>

    <div class="subtext">No spam, ever. Unsubscribe anytime.</div>
  </div>
</body>
</html>

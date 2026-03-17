<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sajib Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #0f0f0f;
      color: white;
    }

    nav {
      display: flex;
      justify-content: space-between;
      padding: 20px 50px;
      background: rgba(0,0,0,0.7);
      position: sticky;
      top: 0;
    }

    nav h2 {
      color: #00ffcc;
    }

    header {
      height: 90vh;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      text-align: center;
      background: linear-gradient(120deg, #000000, #1f1f1f);
    }

    header h1 {
      font-size: 50px;
    }

    header p {
      margin: 15px 0;
      color: #aaa;
    }

    .btn {
      padding: 12px 30px;
      background: #00ffcc;
      color: black;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 60px 20px;
      text-align: center;
    }

    .card {
      background: #1a1a1a;
      padding: 20px;
      margin: 10px;
      border-radius: 15px;
      display: inline-block;
      width: 250px;
    }

    footer {
      text-align: center;
      padding: 20px;
      color: #777;
    }
  </style>
</head>

<body>

<nav>
  <h2>Sajib</h2>
</nav>

<header>
  <h1>I am Sajib 👋</h1>
  <p>Content Creator | Designer | Freelancer</p>
  <a href="#" class="btn">Contact Me</a>
</header>

<section>
  <h2>My Services</h2>
  <div class="card">🎨 Design</div>
  <div class="card">🎥 Video Editing</div>
  <div class="card">💻 Web Design</div>
</section>

<footer>
  © 2026 Sajib | All Rights Reserved
</footer>

</body>
</html>

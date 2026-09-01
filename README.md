# welcome-
welcome 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Welcome</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: linear-gradient(135deg, #111827, #312e81);
      color: white;
      text-align: center;
    }

    .box {
      width: 90%;
      max-width: 500px;
      padding: 45px 25px;
      background: rgba(255,255,255,0.08);
      border: 1px solid rgba(255,255,255,0.15);
      border-radius: 25px;
      backdrop-filter: blur(15px);
      box-shadow: 0 20px 50px rgba(0,0,0,0.3);
    }

    .icon {
      font-size: 55px;
      margin-bottom: 20px;
    }

    h1 {
      font-size: 38px;
      margin-bottom: 12px;
    }

    p {
      font-size: 17px;
      color: #d1d5db;
      line-height: 1.6;
      margin-bottom: 28px;
    }

    .btn {
      display: inline-block;
      padding: 13px 28px;
      background: white;
      color: #312e81;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      transform: scale(1.05);
    }

    .footer {
      margin-top: 25px;
      font-size: 13px;
      color: #9ca3af;
    }
  </style>
</head>

<body>

  <div class="box">

    <div class="icon">👋</div>

    <h1>Welcome!</h1>

    <p>
      Welcome to my website.<br>
      I'm glad you're here.
    </p>

    <a href="#" class="btn">Get Started</a>

    <div class="footer">
      © 2026 All Rights Reserved
    </div>

  </div>

</body>
</html>
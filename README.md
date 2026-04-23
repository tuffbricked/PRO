<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PRO - Home</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    .hero {
      text-align: center;
      color: #fff;
      padding: 40px 20px;
      max-width: 800px;
      width: 100%;
    }
    .hero h1 {
      font-size: 36px;
      margin-bottom: 15px;
      font-weight: 700;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.2);
    }
    .hero p {
      font-size: 16px;
      margin-bottom: 35px;
      opacity: 0.95;
      text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
    }
    .nav-buttons {
      display: flex;
      gap: 30px;
      justify-content: center;
      flex-wrap: wrap;
    }
    .nav-btn {
      display: inline-block;
      padding: 15px 40px;
      font-size: 18px;
      font-weight: 600;
      text-decoration: none;
      border-radius: 50px;
      transition: all 0.3s ease;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
      cursor: pointer;
    }
    .nav-btn.primary {
      background: #4CAF50;
      color: white;
    }
    .nav-btn.primary:hover {
      background: #45a049;
      transform: translateY(-3px);
      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
    }
    .nav-btn.secondary {
      background: #2196F3;
      color: white;
    }
    .nav-btn.secondary:hover {
      background: #0b7dda;
      transform: translateY(-3px);
      box-shadow: 0 6px 20px rgba(0, 0, 0, 0.3);
    }
    .nav-btn:active {
      transform: translateY(-1px);
    }
    @media (max-width: 768px) {
      .hero h1 {
        font-size: 36px;
      }
      .hero p {
        font-size: 16px;
      }
      .nav-buttons {
        flex-direction: column;
        gap: 15px;
      }
      .nav-btn {
        width: 100%;
        padding: 12px 30px;
        font-size: 16px;
      }
    }
  </style>
</head>
<body>
  <div class="hero">
    <h1>Welcome to PRO</h1>
    <p>Manage your account and share your feedback with us</p>
    
    <div class="nav-buttons">
      <a href="USERLOGINFORM.html" class="nav-btn primary">User Login</a>
      <a href="CUSTOMERFEEDBACK.html" class="nav-btn secondary">Customer Feedback</a>
    </div>
  </div>
</body>

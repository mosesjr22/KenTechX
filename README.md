<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Digital Machine Workforce Management</title>

  <style>
    /* ===== Reset and Base ===== */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: radial-gradient(circle at top left, #050505, #0d1b2a, #1b263b);
      color: #fff;
      min-height: 100vh;
      overflow-x: hidden;
    }

    /* ===== Navigation Bar ===== */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 60px;
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(8px);
      border-bottom: 1px solid rgba(255, 255, 255, 0.1);
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 10;
    }

    .logo {
      font-size: 24px;
      font-weight: 700;
      letter-spacing: 1px;
      color: #00d4ff;
      text-shadow: 0 0 8px #00d4ff;
    }

    .nav-links {
      list-style: none;
      display: flex;
      gap: 30px;
    }

    .nav-links li a {
      color: #fff;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s ease, text-shadow 0.3s ease;
    }

    .nav-links li a:hover {
      color: #00d4ff;
      text-shadow: 0 0 10px #00d4ff;
    }

    /* ===== Hero Section ===== */
    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
      padding: 100px 20px;
      background: linear-gradient(135deg, rgba(0, 212, 255, 0.1), rgba(0, 255, 136, 0.05));
      position: relative;
    }

    .hero h1 {
      font-size: 45px;
      color: #00d4ff;
      text-shadow: 0 0 15px rgba(0, 212, 255, 0.8);
      margin-bottom: 15px;
      animation: glow 2.5s infinite alternate;
    }

    @keyframes glow {
      from {
        text-shadow: 0 0 10px #00d4ff, 0 0 20px #00d4ff;
      }
      to {
        text-shadow: 0 0 25px #00ff99, 0 0 50px #00d4ff;
      }
    }

    .hero p {
      font-size: 18px;
      max-width: 700px;
      margin-bottom: 30px;
      line-height: 1.6;
      color: #d4d4d4;
    }

    .hero a {
      background: linear-gradient(90deg, #00d4ff, #00ff99);
      color: #000;
      text-decoration: none;
      padding: 14px 35px;
      border-radius: 30px;
      font-weight: 600;
      font-size: 16px;
      box-shadow: 0 0 15px rgba(0, 212, 255, 0.5);
      transition: all 0.4s ease;
    }

    .hero a:hover {
      transform: scale(1.05);
      box-shadow: 0 0 25px rgba(0, 255, 136, 0.7);
      background: linear-gradient(90deg, #00ff99, #00d4ff);
    }

    /* ===== Features Section ===== */
    .features {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      background: #0a192f;
      padding: 80px 40px;
    }

    .feature-box {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 20px;
      width: 300px;
      margin: 20px;
      padding: 30px;
      text-align: center;
      transition: all 0.4s ease;
      box-shadow: 0 5px 15px rgba(0, 212, 255, 0.1);
    }

    .feature-box:hover {
      transform: translateY(-10px);
      box-shadow: 0 10px 25px rgba(0, 212, 255, 0.3);
    }

    .feature-box h3 {
      color: #00d4ff;
      margin-bottom: 10px;
      font-size: 22px;
    }

    .feature-box p {
      color: #cfcfcf;
      font-size: 15px;
      line-height: 1.5;
    }

    /* ===== Footer ===== */
    footer {
      background: rgba(255, 255, 255, 0.05);
      text-align: center;
      padding: 20px;
      border-top: 1px solid rgba(255, 255, 255, 0.1);
      color: #aaa;
      font-size: 14px;
    }

    /* ===== Responsive Design ===== */
    @media (max-width: 700px) {
      nav {
        flex-direction: column;
        gap: 10px;
      }
      .hero h1 {
        font-size: 30px;
      }
      .feature-box {
        width: 90%;
      }
    }
  </style>
</head>

<body>
  <!-- ===== Navigation ===== -->
  <nav>
    <div class="logo">Digital Machine Workforce</div>
    <ul class="nav-links">
      <li><a href="index.html">Home</a></li>
      <li><a href="digital.html">Register</a></li>
      <li><a href="#">Login</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

  <!-- ===== Hero Section ===== -->
  <section class="hero">
    <h1>Welcome to Digital Machine Workforce Management</h1>
    <p>
      Manage employees, attendance, shifts, payroll, and performance — all from one intelligent, automated platform designed for the future of work.
    </p>
    <a href="digital.html">Get Started</a>
  </section>

  <!-- ===== Features Section ===== -->
  <section class="features">
    <div class="feature-box">
      <h3>Smart Scheduling</h3>
      <p>Automatically create optimized shift schedules and track attendance digitally.</p>
    </div>
    <div class="feature-box">
      <h3>Employee Insights</h3>
      <p>Monitor performance and get analytics that help boost productivity.</p>
    </div>
    <div class="feature-box">
      <h3>Integrated Payroll</h3>
      <p>Generate payslips, track deductions, and process payments seamlessly.</p>
    </div>
    <div class="feature-box">
      <h3>Secure Access</h3>
      <p>Role-based login ensures safe and controlled access for all users.</p>
    </div>
  </section>

  <!-- ===== Footer ===== -->
  <footer>
    &copy; 2025 Digital Machine Workforce Management | Designed with 💙 by You
  </footer>
</body>
</html>

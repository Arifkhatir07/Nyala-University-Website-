<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nyala University</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
    }
    header {
      background: #2e8b57;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    nav {
      background: #444;
      color: white;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    main {
      padding: 20px;
    }
    footer {
      background: #2e8b57;
      color: white;
      text-align: center;
      padding: 15px 0;
      position: relative;
      bottom: 0;
      width: 100%;
    }
    .college-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 10px;
      margin-top: 20px;
    }
    .college {
      background: white;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 0 5px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>
  <header>
    <h1>Nyala University</h1>
    <p>Sudan</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#">Colleges</a>
    <a href="#">Contact</a>
  </nav>

  <main>
    <h2>Our Colleges</h2>
    <div class="college-list">
      <div class="college">College of Medicine</div>
      <div class="college">College of Veterinary Medicine</div>
      <div class="college">College of Engineering</div>
      <div class="college">College of Education</div>
      <div class="college">College of Law</div>
      <div class="college">College of Economics and Administration</div>
      <div class="college">College of Agriculture</div>
      <div class="college">College of Community Development</div>
      <div class="college">College of Nursing Sciences</div>
      <div class="college">College of Computer Science and IT</div>
      <div class="college">College of Medical Laboratory Sciences</div>
      <div class="college">College of Public and Environmental Health</div>
    </div>

    <h2>Contact Us</h2>
    <p><strong>Address:</strong> Nyala, South Darfur, Sudan</p>
    <p><strong>Phone:</strong> +249 711 234567</p>
    <p><strong>Email:</strong> info@nyalauniversity.sd</p>
    <p><strong>Website:</strong> <a href="http://www.nyala.edu.sd">www.nyala.edu.sd</a></p>
  </main>

  <footer>
    <p>&copy; 2025 Nyala University. All rights reserved.</p>
  </footer>
</body>
</html>
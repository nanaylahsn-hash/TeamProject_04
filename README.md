<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Emanate</title>

  
  <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">

  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
    }

    .navbar {
      padding: 20px;
      background-color: white;
    }

    .hero {
      background-color: lightblue;
      padding: 80px 20px;
    }

    button {
      background-color: blueviolet;
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 5px;
      font-size: 16px;
    }

    .features {
      padding: 50px 20px;
    }

    
    .icon-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      margin-top: 30px;
    }

    .icon-item {
      width: 130px;
    }

    /* Ini yang ngatur ukuran & warna icon-nya */
    .icon-item .material-icons {
      font-size: 36px;
      color: blueviolet;
    }

    .dark {
      background-color: black;
      color: white;
      padding: 50px 20px;
    }

    .pricing {
      background-color: black;
      color: white;
      padding: 50px 20px;
    }

    .box {
      background-color: dimgray;
      display: inline-block;
      padding: 20px;
      margin: 10px;
      width: 150px;
      border-radius: 8px;
    }

    footer {
      background-color: whitesmoke;
      padding: 30px;
    }
  </style>
</head>

<body>

  
  <div class="navbar">
    <strong>EMANATE</strong>
    &nbsp;&nbsp;
    <a href="#">Home</a>
    <a href="#">Pricing</a>
    <a href="#">Log In</a>
  </div>

  
  <div class="hero">
    <h1>Emanate HTML Template</h1>
    <p>Template landing page yang simpel dan responsive.</p>
    <button>Get Started</button>
  </div>

  
  <div class="features">
    <h2>Based On Modular Design</h2>
    <p>Build awesome websites with simple, independent parts.</p>

    <div class="icon-list">

      <div class="icon-item">
        <span class="material-icons">format_shapes</span>
        <p>Minimal Design</p>
      </div>

      <div class="icon-item">
        <span class="material-icons">network_check</span>
        <p>Rocket Fast</p>
      </div>

      <div class="icon-item">
        <span class="material-icons">line_style</span>
        <p>Custom Framework</p>
      </div>

      <div class="icon-item">
        <span class="material-icons">chrome_reader_mode</span>
        <p>Style Guide</p>
      </div>

      <div class="icon-item">
        <span class="material-icons">code</span>
        <p>CSS + SASS</p>
      </div>

      <div class="icon-item">
        <span class="material-icons">settings</span>
        <p>100% Customizable</p>
      </div>

      <div class="icon-item">
        <span class="material-icons">dashboard</span>
        <p>Modular Design</p>
      </div>

      <div class="icon-item">
        <span class="material-icons">check</span>
        <p>HTML5 Valid</p>
      </div>

    </div>
  </div>

  
  <div class="dark">
    <h2>Cepat. Sangat Cepat.</h2>
    <p>Fokus utama template ini adalah performa.</p>
  </div>

  
  <div class="pricing">
    <h2>Pilih Paket</h2>

    <div class="box">
      <h3>Professional</h3>
      <p>$10/bulan</p>
    </div>

    <div class="box">
      <h3>Team</h3>
      <p>$20/bulan</p>
    </div>

    <div class="box">
      <h3>Enterprise</h3>
      <p>$50/bulan</p>
    </div>
  </div>

  
  <footer>
    <p>&copy; 2026 Emanate. Semua hak dilindungi.</p>
  </footer>

</body>
</html>

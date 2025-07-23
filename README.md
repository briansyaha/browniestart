<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Brownies Tart</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #111;
      color: white;
      display: flex;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      background-color: #1a1a1a;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 0 20px rgba(0,0,0,0.6);
      max-width: 900px;
    }

    .image-section img {
      width: 100%;
      height: auto;
      object-fit: cover;
      max-width: 450px;
      display: block;
    }

    .text-section {
      padding: 2rem;
      flex: 1;
    }

    h1 {
      margin-top: 0;
      font-size: 2rem;
    }

    p {
      font-size: 0.95rem;
      line-height: 1.6;
      color: #ccc;
    }

    .free {
      margin-top: 1rem;
      color: #ff6961;
    }

    .btn {
      margin-top: 1.5rem;
      display: inline-block;
      padding: 10px 20px;
      background-color: #444;
      color: white;
      text-decoration: none;
      border-radius: 6px;
      transition: background-color 0.3s;
    }

    .btn:hover {
      background-color: #666;
    }

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="image-section">
      <img src="brownies-tart.jpg" alt="Brownies Tart Cake" />
    </div>
    <div class="text-section">
      <h1>BROWNIES TART</h1>
      <p>Bentuk, model, warna, tema dan toping sesuai pesenan customer. Harga tergantung diameter, kerumitan, dan toping. Bisa membawa contoh sendiri.</p>
      <p class="free">📍 Free lilin</p>
      <a class="btn" href="#">Learn More ›</a>
    </div>
  </div>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>EVERTH BERMUDEZ S.A - Carros Últimos Modelos</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: #111;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    nav {
      background: #222;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://cdn.pixabay.com/photo/2016/06/29/16/53/auto-1481060_1280.jpg') no-repeat center center/cover;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 2rem;
      font-weight: bold;
      text-shadow: 2px 2px 6px black;
    }
    .container {
      padding: 30px;
      max-width: 1200px;
      margin: auto;
    }
    .cars {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .car {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    .car:hover {
      transform: scale(1.03);
    }
    .car img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }
    .car h3 {
      margin: 10px;
      font-size: 1.2rem;
    }
    .car p {
      margin: 0 10px 10px;
      font-size: 0.9rem;
      color: #666;
    }
    footer {
      background: #111;
      color: #fff;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>EVERTH BERMUDEZ S.A</h1>
    <p>Car
    

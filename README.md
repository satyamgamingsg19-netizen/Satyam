<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Satyam's Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background: linear-gradient(135deg, #89f7fe, #66a6ff);
      margin: 0;
      padding: 50px;
    }
    .card {
      background: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0px 5px 15px rgba(0,0,0,0.2);
      display: inline-block;
      animation: fadeIn 1s ease-in-out;
    }
    img {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 20px;
      border: 5px solid #66a6ff;
    }
    h1 {
      margin: 0;
      color: #333;
      font-size: 2.2rem;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.9); }
      to { opacity: 1; transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="card">
    <img src="satyam.jpg" alt="Satyam's Photo">
    <h1>Satyam</h1>
  </div>
</body>
</html>

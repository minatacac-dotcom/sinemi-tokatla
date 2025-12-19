<!doctype html>
<html lang="tr">
<head>
  <meta charset="utf-8" />
  <title>Sinem’i Tokatla 👋</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    body {
      margin: 0;
      min-height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: #f3f4ff;
      font-family: Arial, sans-serif;
    }
    .box {
      background: white;
      padding: 30px;
      border-radius: 16px;
      text-align: center;
      box-shadow: 0 10px 30px rgba(0,0,0,.15);
    }
    h1 { margin-bottom: 10px; }
    #count {
      font-size: 50px;
      font-weight: bold;
      margin: 20px 0;
    }
    button {
      font-size: 18px;
      padding: 12px 20px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      background: #5b6cff;
      color: white;
    }
    button:active {
      transform: scale(0.97);
    }
  </style>
</head>
<body>

  <div class="box">
    <h1>Sinem’i Tokatla 👋</h1>
    <div id="count">0</div>
    <button onclick="tokatla()">Tokatla 👊</button>
  </div>

  <script>
    let sayi = 0;
    function tokatla() {
      sayi++;
      document.getElementById("count").innerText = sayi;
    }
  </script>

</body>
</html>

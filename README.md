<html>
<head>
  <style>
    body {
      background-color: lightgreen;
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      flex-direction: column; /* Вирівнювання по вертикалі */
    }
    header {
      text-align: center;
    }
    p {
      font-weight: bold;
      font-size: 80px;
      text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.6); /* Обводка тексту */
    }
    .button-container {
      display: flex;
      justify-content: space-between;
      width: 100%; /* Розтягуємо контейнер на всю ширину */
      padding: 0 20px; /* Відступи з боків */
    }
    .button {
      text-align: center;
      margin-top: 20px;
    }
    .button a {
      background-color: blue;
      color: white;
      padding: 15px 30px;
      text-decoration: none;
      font-size: 20px;
      border-radius: 5px;
      display: inline-block;
    }
    .button a:hover {
      background-color: darkblue;
    }
  </style>
</head>
<body>
  <header>
    <p>ІГРОВИЙ АВТОМАТ</p>
    <div class="button-container">
      <!-- Кнопка зліва для переходу на Poki -->
      <div class="button">
        <a href="https://poki.com/" target="_blank">Перейти на Poki</a>
      </div>
      <!-- Кнопка по центру для переходу на онлайн дошку -->
      <div class="button">
        <a href="https://wbo.ophir.dev/" target="_blank">Онлайн Дошка</a>
      </div>
    </div>
  </header>
</body>
</html>

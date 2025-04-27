# easysmeta.github.io
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Калькулятор</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <button id="calcBtn" class="calc-btn">Калькулятор</button>

    <div id="calculator" class="calculator">
      <label for="squareMeters">Введите кв.м:</label>
      <input type="number" id="squareMeters" placeholder="Кв. м">
      <button id="calculateBtn">Рассчитать</button>
      <div id="result" class="result"></div>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>

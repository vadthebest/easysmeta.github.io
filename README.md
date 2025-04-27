# easysmeta.github.io
JavaScript


document.getElementById('calcBtn').addEventListener('click', function() {
  document.getElementById('calculator').style.display = 'block';
});

document.getElementById('calculateBtn').addEventListener('click', function() {
  const squareMeters = parseFloat(document.getElementById('squareMeters').value);
  
  if (!isNaN(squareMeters)) {
    const result = squareMeters * 150;
    document.getElementById('result').textContent = `Результат: ${result} руб.`;
  } else {
    document.getElementById('result').textContent = 'Пожалуйста, введите корректное число.';
  }
});

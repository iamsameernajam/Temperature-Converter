<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Temperature Converter</title>
  <style>
    body {
      font-family: Arial Rounded MT Bold ;
      text-align: center;
    }

    input[type="number"] {
      width: 180px;
      padding: 9px;
      margin: 10px;
    }

    button {
      padding: 12px;
    }
  </style>
</head>

<body>
  <h1>Temperature Converter</h1>
  <label for="celsius">Celsius:</label>
  <input type="number" id="celsius" placeholder="Enter temperature in Celsius" />
  <br>

  <label for="fahrenheit">Fahrenheit:</label>
  <input type="number" id="fahrenheit" placeholder="Enter temperature in Fahrenheit" />
  <br>

  <label for="kelvin">Kelvin:</label>
  <input type="number" id="kelvin" placeholder="Enter temperature in Kelvin" />
  <br>

  <button onclick="convertTemperature()">Convert</button>

  <script>
    function convertTemperature() {
      const celsiusInput = document.getElementById("celsius");
      const fahrenheitInput = document.getElementById("fahrenheit");
      const kelvinInput = document.getElementById("kelvin");

      const celsius = parseFloat(celsiusInput.value);
      const fahrenheit = (celsius * 9 / 5) + 32;
      const kelvin = celsius + 273.15;

      if (!isNaN(celsius)) {
        fahrenheitInput.value = fahrenheit.toFixed(2);
        kelvinInput.value = kelvin.toFixed(2);
      } else {
        fahrenheitInput.value = "";
        kelvinInput.value = "";
      }
    }
  </script>
</body>

</html>


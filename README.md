
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Andrea es la Más Hermosa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            background-color: #f8f9fa;
        }
        .container {
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 20px;
            display: inline-block;
        }
        button {
            margin: 10px;
            padding: 10px 20px;
            font-size: 16px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .btn-yes {
            background-color: #28a745;
            color: #ffffff;
        }
        .btn-no {
            background-color: #dc3545;
            color: #ffffff;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Andrea es la más hermosa del mundo</h1>
        <button class="btn-yes" onclick="showMessage()">Sí</button>
        <button class="btn-no" onclick="showMessage()">No</button>
        <p id="response"></p>
    </div>
    <script>
        function showMessage() {
            document.getElementById('response').innerText = "No importa, siempre serás la más hermosa";
        }
    </script>
</body>
</html>

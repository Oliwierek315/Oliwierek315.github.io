<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pozdrowienia</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
        }
        .message {
            font-size: 24px;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="message" onclick="changeMessage()">Kiedyś coś tu będzie! ~Pozdrawiam, Oliwier</div>
    
    <script>
        function changeMessage() {
            const message = document.querySelector('.message');
            message.textContent = 'Miłego dnia!';
        }
    </script>
</body>
</html>

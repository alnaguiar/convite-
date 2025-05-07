# convite-
Convite especial com interface gráfica
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Convite Especial</title>
    <style>
        body {
            background-color: #FFEBEE;
            font-family: Arial, sans-serif;
            text-align: center;
            color: #B71C1C;
        }
        .button {
            padding: 10px 20px;
            font-size: 16px;
            margin: 10px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .yes-button {
            background-color: #C8E6C9;
            color: #2E7D32;
        }
        .no-button {
            background-color: #FFCDD2;
            color: #B71C1C;
        }
    </style>
</head>
<body>
    <h1>Quer sair comigo?</h1>
    <div>
        <button class="button yes-button" onclick="location.href='/sim'">Sim</button>
        <button class="button no-button" onclick="location.href='/nao'">Não</button>
    </div>
    <footer>
        <p>da Alanna, beijos linda ❤️</p>
    </footer>
</body>
</html>

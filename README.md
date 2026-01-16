<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>Vent Client – Download</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            margin: 0;
            font-family: Inter, Arial, sans-serif;
            background: #0B0F14;
            color: #EDEDED;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .card {
            background: #121826;
            padding: 40px;
            border-radius: 16px;
            width: 420px;
            box-shadow: 0 0 40px rgba(0,0,0,.6);
            text-align: center;
        }
        h1 {
            margin-bottom: 10px;
        }
        p {
            opacity: .8;
        }
        a.button {
            display: block;
            margin-top: 20px;
            padding: 14px;
            border-radius: 12px;
            background: #EDEDED;
            color: #0B0F14;
            text-decoration: none;
            font-weight: bold;
            transition: .2s;
        }
        a.button:hover {
            transform: scale(1.05);
        }
        .small {
            font-size: 12px;
            margin-top: 15px;
            opacity: .6;
        }
    </style>
</head>
<body>
    <div class="card">
        <h1>Vent Client 🌙</h1>
        <p>Oficjalna strona pobierania</p>

        <a class="button" href="https://fabricmc.net/use/installer/" target="_blank">
            Pobierz Fabric Installer
        </a>

        <a class="button" href="#" onclick="alert('Vent Client wkrótce!')">
            Pobierz Vent Client
        </a>

        <div class="small">
            Wymagana Java 17 • Minecraft 1.8.9
        </div>
    </div>
</body>
</html>

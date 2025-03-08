# -
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>8 Наурызға шақырту</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #ffe6f2;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 600px;
            margin: 50px auto;
            padding: 20px;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #d63384;
        }
        p {
            font-size: 18px;
            color: #555;
        }
        .button {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 18px;
            color: white;
            background: #d63384;
            text-decoration: none;
            border-radius: 5px;
            cursor: pointer;
            border: none;
        }
        .button:hover {
            background: #b02066;
        }
        .footer {
            margin-top: 20px;
            font-size: 14px;
            color: #777;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1> Құрметті қыздар! </h1>
        <p> Сіздерді Халықаралық әйелдер күнімен құттықтаймыз! Осы тамаша мерекенің құрметіне Сіздерді көңілді іс-шараға, ауызашарға және жақсы көңіл-күйге шақырамыз! </p>
        <p><strong>Күні:</strong> 9 Наурыз 2025 ж.<br>
           <strong>Уақыты:</strong> 17:00<br>
           <strong>Орын:</strong> Кафе "Априори"</p>
        <button class="button" onclick="confirmParticipation()"> Қатысуды растау </button>
        <p class="footer"> Сізді көруге қуаныштымыз! Сіздің сыныптастарыңыз. </p>
    </div>

    <script>
        function confirmParticipation() {
            alert("Рахмет! Сіздің қатысуыңыз расталды. Сіздерді мерекеде күтеміз!");
        }
    </script>
</body>
</html>

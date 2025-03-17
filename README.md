<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Резюме Димы</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
        body {
            background-color: black;
            color: #ffffff;
            font-family: 'Roboto', sans-serif;
            text-align: center;
            padding: 50px;
            animation: backgroundGlow 5s infinite alternate;
        }
        @keyframes backgroundGlow {
            0% { background-color: black; }
            100% { background-color: #002244; }
        }
        .glow {
            text-shadow: 0 0 10px #00aaff, 0 0 20px #ff00ff;
            animation: textGlow 1.5s infinite alternate;
            transition: transform 0.3s ease-in-out;
        }
        .glow:hover {
            transform: scale(1.1);
        }
        @keyframes textGlow {
            from { text-shadow: 0 0 10px #00aaff; }
            to { text-shadow: 0 0 20px #ff00ff; }
        }
        .section {
            margin: 20px 0;
            padding: 20px;
            border: 2px solid #00aaff;
            border-radius: 10px;
            background-color: rgba(0, 0, 0, 0.9);
            animation: pulse 1.5s infinite alternate;
            transition: transform 0.3s ease-in-out;
        }
        .section:hover {
            transform: scale(1.05);
        }
        @keyframes pulse {
            from { box-shadow: 0 0 10px #00aaff; }
            to { box-shadow: 0 0 30px #ff00ff; }
        }
        p, h2 {
            cursor: pointer;
        }
        .photo-frame {
            width: 200px;
            height: 200px;
            border: 4px solid #00aaff;
            border-radius: 50%;
            margin: 20px auto;
            background-color: rgba(0, 0, 0, 0.9);
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
            box-shadow: 0 0 20px #00aaff;
            animation: frameGlow 1.5s infinite alternate;
        }
        .photo-frame img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            border-radius: 50%;
        }
        @keyframes frameGlow {
            from { box-shadow: 0 0 10px #00aaff; }
            to { box-shadow: 0 0 30px #ff00ff; }
        }
    </style>
</head>
<body>
    <h1 class="glow" contenteditable="true">🚀 Резюме: Дима (a.k.a. Легенда Технологий) 🚀</h1>
    
    <div class="photo-frame" id="photo-container">
        <img id="photo" src="images/myphoto.jpg" alt="Фото">

    </div>
    
    <div class="section" contenteditable="true">
        <h2 class="glow">💻 Программирование и QA</h2>
        <p>Опыт: 1 год+</p>
        <p>Python, автоматизация тестирования, Selenium, Pytest, API-тестирование, Postman.</p>
        <p>Создание Telegram-ботов, веб-разработка, интеграция AI.</p>
    </div>
    
    <div class="section" contenteditable="true">
        <h2 class="glow">🔍 Тестирование ПО</h2>
        <p>Функциональное и нефункциональное тестирование.</p>
        <p>Разработка автотестов, CI/CD, работа с Docker и виртуальными средами.</p>
        <p>Анализ багов, работа с Jira, TestRail.</p>
    </div>
    
    <div class="section" contenteditable="true">
        <h2 class="glow">📢 Бизнес и маркетинг</h2>
        <p>Создаёт строительную компанию «Холдинг Строй».</p>
        <p>Продвигает бизнес в соцсетях: ВК, Instagram, YouTube, TikTok, RuTube.</p>
        <p>Разрабатывает AI-таргетолога для автоматизированного маркетинга.</p>
    </div>
    
    <div class="section" contenteditable="true">
        <h2 class="glow">🔥 Личный вызов</h2>
        <p>Цель: похудеть с 105 кг до 80 кг, набрать мышечную массу.</p>
        <p>Тренировки в зале, усиленный режим без жёстких диет.</p>
    </div>
    
    <div class="section" contenteditable="true">
        <h2 class="glow">🍳 Кулинарный проект</h2>
        <p>Создаёт сайт с рецептами и видеороликами.</p>
        <p>Снимает кулинарные видео, продвигает их через AI.</p>
    </div>
    
    <div class="section" contenteditable="true">
        <h2 class="glow">🎯 Личное кредо</h2>
        <p>«Делай качественно, логично, по шагам».</p>
        <p>Всегда ищет новые технологии для автоматизации и роста!</p>
    </div>
</body>
</html>

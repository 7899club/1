<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>主页</title>
    <link rel="stylesheet" href="css/style.css">
    <style>
        body {
            background-image: url('https://tinyurl.com/3wcesw6m');
            background-size: cover;
            background-position: center;
            font-family: Arial, sans-serif;
            text-align: center;
            min-height: 100vh;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        header {
            background-color: rgba(0, 0, 0, 0.5);
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        @keyframes colorChange {
            0% { color: white; }
            25% { color: red; }
            50% { color: yellow; }
            75% { color: blue; }
            100% { color: green; }
        }
        header h1 {
            font-size: 2rem;
            margin: 0;
            animation: colorChange 5s infinite;
        }
        nav {
            margin-top: 10px;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: red;
            font-weight: bold;
            border: 2px solid red;
            padding: 5px 10px;
            transition: color 0.3s ease, border-color 0.3s ease;
        }
        nav ul li a:hover {
            color: #4CAF50;
            border-color: #4CAF50;
        }
        main {
            flex: 1;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        main section {
            background-color: rgba(255, 255, 255, 0.7);
            padding: 20px;
            border-radius: 10px;
            width: 80%;
            max-width: 600px;
            text-align: left;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        main section:hover {
            transform: translateY(-10px);
        }
        footer {
            background-color: rgba(0, 0, 0, 0.5);
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>欢迎来到我们的平台</h1>
        <nav>
            <ul>
                <li><a href="login/login.html">登录</a></li>
                <li><a href="sign/register.html">注册</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h2><a href="login/login.html" style="color: red; text-decoration: underline;">7899.club</a>成立于2017年，凭借卓越的信誉和无与伦比的责任感，我们很荣幸向您介绍一下我们平台的历史背景。</h2>
            <p>7899.club成立于2017年，以其卓越的信誉和无与伦比的责任感，立志成为全球玩家信赖的首选游戏平台。我们深知游戏的乐趣和社交的重要性，因此致力于打造一个安全、公正和充满活力的游戏社区。作为业内领先的游戏运营商之一，我们不仅仅提供多样化的游戏选择，更注重用户体验的持续优化和创新。我们的团队由一群充满激情和专业知识的人才组成，不断推动技术创新和服务升级，以确保您在7899.club获得无与伦比的游戏享受和尊贵待遇。无论您是热爱传统游戏还是追求创新玩法的玩家，我们都致力于为您提供个性化的游戏体验和最优质的客户服务。现在就加入7899.club，与全球玩家一同探索无限可能，享受精彩纷呈的游戏时光！</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 我们的平台</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Débora Melo</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #121212;
            color: #ffffff;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            text-align: center;
        }
        h1 {
            font-size: 2.5em;
            margin: 0;
            animation: fadeIn 1s;
        }
        h2 {
            font-size: 1.5em;
            margin: 0.5em 0;
            animation: fadeIn 1.5s;
        }
        .skills {
            display: flex;
            justify-content: center;
            margin: 1em 0;
        }
        .skills img {
            margin: 0 10px;
            transition: transform 0.3s;
        }
        .skills img:hover {
            transform: scale(1.2);
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
    </style>
</head>
<body>

    <h1>Olá! Eu sou Débora Melo</h1>
    <h2>Estudante de Análise e Desenvolvimento de Sistemas</h2>
    <h2>De Santana de Parnaíba - SP</h2>

    <div class="skills">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C" width="40" height="40"/>
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML" width="40" height="40"/>
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS" width="40" height="40"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" width="40" height="40"/>
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" width="40" height="40"/>
    </div>

</body>
</html>

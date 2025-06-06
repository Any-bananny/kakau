<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title> Feliz Dia dos Namorados meu Kardeczinho ❤️</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', sans-serif;
            background: #fff0f5;
            color: #333;
            text-align: center;
            padding: 20px;
        }

        h1 {
            color: #d63384;
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        .heart {
            font-size: 3em;
            animation: pulse 1s infinite;
            color: red;
            margin-bottom: 20px;
        }

        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.3); }
            100% { transform: scale(1); }
        }

        p {
            font-size: 1.2em;
            margin-bottom: 25px;
        }

        button {
            padding: 12px 25px;
            background-color: #d63384;
            color: white;
            border: none;
            border-radius: 10px;
            font-size: 1em;
            cursor: pointer;
            margin-bottom: 20px;
        }

        button:hover {
            background-color: #ad296b;
        }

        #surpresa {
            display: none;
            font-size: 1.1em;
            margin-top: 20px;
            color: #5c2a69;
        }

        .carousel {
            margin: 30px 0;
            position: relative;
            max-width: 100%;
            overflow: hidden;
        }

        .slides {
            display: flex;
            width: 300%;
            animation: slide 12s infinite;
        }

        .slides img {
            width: 100%;
            border-radius: 12px;
        }

        @keyframes slide {
            0% { transform: translateX(0); }
            33% { transform: translateX(-100%); }
            66% { transform: translateX(-200%); }
            100% { transform: translateX(0); }
        }

        .timeline {
            background: #ffe0ec;
            padding: 20px;
            border-radius: 12px;
            margin-top: 30px;
        }

        .timeline h2 {
            margin-bottom: 10px;
            color: #d63384;
        }

        .timeline ul {
            list-style: none;
            padding: 0;
        }

        .timeline li {
            margin: 10px 0;
            font-size: 1.05em;
        }

        audio {
            margin-top: 20px;
        }

        footer {
            margin-top: 40px;
            font-size: 0.9em;
            color: #888;
        }

        @media (max-width: 600px) {
            h1 { font-size: 2em; }
            .heart { font-size: 2em; }
            button { width: 80%; }
        }
    </style>
</head>
<body>

    <h1> Feliz Dia dos Namorados Roliço! 💖</h1>
    <div class="heart">❤️</div>

    <p>Amor, esse site é uma das 99999milhões de demonstrar o meu amor.<br>
        Cada momento ao seu lado é único e especial. Te amo demais! 💘</p>

    <button onclick="mostrarSurpresa()">Clique aqui para uma surpresa</button>

    <div id="surpresa">
       💌 Você é a minha pessoa favorita, Obrigada por ser o meu porto seguro, <br>
        espero que algum dia eu possa ser o seu tambem. TE AMO! 💞
    </div>

    <!-- Carrossel de imagens -->
    <div class="carousel">
        <div class="slides">
            <img src="c:\Users\banan\OneDrive\Pictures\Captura de tela 2025-06-05 204714.png" alt="Foto 1">
            <img src="c:\Users\banan\OneDrive\Pictures\Captura de tela 2025-06-05 210631.png" alt="Foto 2">
            <img src="c:\Users\banan\OneDrive\Pictures\Captura de tela 2025-06-05 210959.png" alt="Foto 3">
        </div>
    </div>

    <!-- Linha do tempo de datas especiais -->
    <div class="timeline">
        <h2>Nossos Momentos 💌</h2>
        <ul>
            <li>💍 04/05/2023 — Dia da nossa data de namoro</li>
            <li>💑 10/05/2023 — Nosso primeiro beijo </li>
            <li>💌 20/05/2023 — Nosso primeiro encontro fora da escola </li>
            <li>🎉 todos — Todos os dias ao seu lado são incriveis </li>
        </ul>
    </div>

    <!-- Música romântica -->
    <audio autoplay loop controls>
        <source src="https://youtu.be/GJNdR_MKuDM?si=ZrqXwpEz5vNSH6T6" type="audio/mpeg">
        Seu navegador não suporta áudio.
    </audio>

    <footer>
        Criado com carinho 💕 por Kauany — Para meu Kardeczinho.
    </footer>

    <script>
        function mostrarSurpresa() {
            document.getElementById("surpresa").style.display = "block";
        }
    </script>

</body>
</html>

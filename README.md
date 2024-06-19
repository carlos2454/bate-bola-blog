<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bate-Bola Blog</title>
    <style>
        /* Definições gerais */
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            line-height: 1.6;
        }

        /* Estilos do cabeçalho */
        header {
            background-color: #1e90ff;
            color: #fff;
            padding: 1em 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        /* Estilos da navegação */
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 1em;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 1.1em;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #ffeb3b;
        }

        /* Estilos do conteúdo principal */
        main {
            padding: 2em;
            max-width: 800px;
            margin: 0 auto;
        }

        /* Estilos das seções */
        section {
            background: #fff;
            padding: 1.5em;
            margin-bottom: 2em;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            margin-top: 0;
            color: #1e90ff;
            font-size: 2em;
        }

        /* Estilos do rodapé */
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            margin-top: 2em;
            box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.1);
        }

        footer a {
            color: #1e90ff;
            text-decoration: none;
            transition: color 0.3s;
        }

        footer a:hover {
            color: #ffeb3b;
        }

        footer p {
            margin: 0.5em 0;
        }

        /* Adicionando um efeito hover nos links das seções */
        section a {
            color: #1e90ff;
            text-decoration: none;
            transition: color 0.3s;
        }

        section a:hover {
            color: #ffeb3b;
        }

        /* Ajustando o layout responsivo */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }

            nav ul li {
                margin: 0.5em 0;
            }

            main {
                padding: 1em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Bate-Bola Blog</h1>
        <nav>
            <ul>
                <li><a href="#futebol">Futebol</a></li>
                <li><a href="#basquete">Basquete</a></li>
                <li><a href="#volei">Vôlei</a></li>
                <li><a href="#contato">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="futebol">
            <h2>Futebol</h2>
            <p>O futebol é um esporte de equipe jogado entre dois times de onze jogadores cada, e é amplamente considerado o esporte mais popular do mundo.</p>
        </section>

        <section id="basquete">
            <h2>Basquete</h2>
            <p>O basquete é um esporte de equipe em que duas equipes de cinco jogadores cada tentam marcar pontos arremessando uma bola através de um cesto elevado.</p>
        </section>

        <section id="volei">
            <h2>Vôlei</h2>
            <p>O vôlei é um esporte de equipe em que dois times de seis jogadores são separados por uma rede, e cada time tenta marcar pontos jogando uma bola no chão do campo adversário.</p>
        </section>
    </main>

    <footer>
        <section id="contato">
            <h2>Contato</h2>
            <p>Para mais informações, entre em contato pelo email: <a href="mailto:contato@batebolablog.com">contato@batebolablog.com</a></p>
        </section>
        <p>&copy; 2024 Bate-Bola Blog</p>
    </footer>

    <script>
        // scripts.js - Opcional, pode ser usado para adicionar funcionalidades interativas no futuro
        console.log("Bem-vindo ao Bate-Bola Blog!");
    </script>
</body>
</html>

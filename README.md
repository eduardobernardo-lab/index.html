# index.html
# Curr-culo
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo - Eduardo Bernardo</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Georgia, 'Times New Roman', serif;
            background-color: #f4f2ef;
            color: #2c2c2c;
            line-height: 1.7;
        }

        header {
            background-color: #2c2c2c;
            color: #f4f2ef;
            padding: 32px 40px;
        }

        header h1 {
            font-size: 1.8rem;
            font-weight: normal;
            letter-spacing: 0.04em;
            margin-bottom: 16px;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 24px;
            flex-wrap: wrap;
        }

        nav ul li a {
            color: #c8bfb0;
            text-decoration: none;
            font-size: 0.9rem;
            letter-spacing: 0.03em;
            transition: color 0.2s;
        }

        nav ul li a:hover {
            color: #f4f2ef;
        }

        main {
            max-width: 760px;
            margin: 48px auto;
            padding: 0 24px;
        }

        .foto-section {
            margin-bottom: 40px;
        }

        .foto-section h2 {
            font-size: 0.75rem;
            text-transform: uppercase;
            letter-spacing: 0.12em;
            color: #888;
            margin-bottom: 16px;
            font-weight: normal;
        }

        .fotos {
            display: flex;
            gap: 16px;
        }

        .fotos img {
            width: 100px;
            height: 100px;
            object-fit: cover;
            border-radius: 4px;
            border: 1px solid #d8d3cc;
        }

        section {
            background-color: #fff;
            border: 1px solid #ddd9d3;
            border-radius: 6px;
            padding: 32px;
            margin-bottom: 24px;
        }

        section h2 {
            font-size: 0.75rem;
            text-transform: uppercase;
            letter-spacing: 0.12em;
            color: #888;
            margin-bottom: 20px;
            font-weight: normal;
        }

        section p {
            font-size: 0.97rem;
            color: #3a3a3a;
            margin-bottom: 10px;
        }

        .experiencia-label {
            font-size: 0.75rem;
            text-transform: uppercase;
            letter-spacing: 0.1em;
            color: #888;
            margin-top: 24px;
            margin-bottom: 12px;
            font-weight: normal;
        }

        .experiencia-lista {
            list-style: none;
            display: flex;
            flex-direction: column;
            gap: 8px;
        }

        .experiencia-lista li {
            font-size: 0.95rem;
            color: #3a3a3a;
            padding-left: 14px;
            border-left: 2px solid #c8bfb0;
        }

        footer {
            text-align: center;
            padding: 24px;
            font-size: 0.82rem;
            color: #aaa;
            letter-spacing: 0.05em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Eduardo Bernardo da Silva</h1>
        <nav>
            <ul>
                <li><a href="mailto:eduardo.bernardo@unifebe.edu.br">Email</a></li>
                <li><a href="https://www.linkedin.com/in/eduardo-bernardo-4911603b0/" target="_blank">LinkedIn</a></li>
                <li><a href="https://github.com/eduardobernardo-lab" target="_blank">GitHub</a></li>
                <li><a href="https://wa.me/5548988753923" target="_blank">WhatsApp</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <div class="foto-section">
            <h2>Foto de identificação</h2>
            <div class="fotos">
                <img src="https://media-gru2-2.cdn.whatsapp.net/v/t61.24694-24/611460195_894966853322342_8358259841618987621_n.jpg?ccb=11-4&oh=01_Q5Aa4AG69mj9qJndiWO4Tl8kDKgkJ2K_2frudI8UCYhZ3RTT8w&oe=69C842D4&_nc_sid=5e03e0&_nc_cat=108" alt="Foto Eduardo">
                <img src="https://avatars.githubusercontent.com/u/263482168?v=4" alt="Foto GitHub Eduardo">
            </div>
        </div>

        <section>
            <h2>Sobre mim</h2>
            <p>Tenho 19 anos e atualmente sou estudante de Sistemas de Informação, com interesse em desenvolvimento web.</p>

            <p class="experiencia-label">Experiência profissional</p>
            <ul class="experiencia-lista">
                <li>Auxiliar administrativo</li>
                <li>Frente de caixa em mercado</li>
                <li>Lavador e polidor de automóveis</li>
            </ul>
        </section>
    </main>

    <footer>Eduardo Bernardo da Silva</footer>
</body>
</html>


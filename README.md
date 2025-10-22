<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Abdelrahman Fakhr Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        body {
            background: #18141f;
            color: #d1c2e0;
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background: #221a2c;
            text-align: center;
            padding: 2rem 1rem;
            border-bottom: 1px solid #2d2340;
        }
        header h1 {
            color: #b993fc;
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        header p {
            color: #9e8aad;
            font-size: 1.25rem;
        }
        main {
            max-width: 900px;
            margin: 2rem auto;
            padding: 1rem;
            background: #20182a;
            border-radius: 16px;
            box-shadow: 0 6px 32px #0005;
        }
        section {
            margin-bottom: 2.5rem;
        }
        h2 {
            color: #ad7aff;
            border-bottom: 1px solid #32254a;
            padding-bottom: 0.25rem;
            margin-bottom: 1rem;
        }
        .thumbnail-container {
            display: flex;
            justify-content: center;
            margin-bottom: 1.5rem;
        }
        .thumbnail-container a {
            display: inline-block;
        }
        .thumbnail-container img {
            max-width: 300px;
            border-radius: 12px;
            box-shadow: 0 2px 12px #633b8e44;
            transition: transform 0.2s;
        }
        .thumbnail-container img:hover {
            transform: scale(1.03);
            box-shadow: 0 4px 24px #ad7aff77;
        }
        .figma-embed {
            display: flex;
            justify-content: center;
            margin: 2rem 0;
        }
        a {
            color: #ad7aff;
            text-decoration: none;
            transition: color 0.2s;
        }
        a:hover {
            color: #d1c2e0;
        }
        footer {
            text-align: center;
            color: #7d689e;
            padding: 1.2rem 0;
            margin-top: 2rem;
            background: #221a2c;
            font-size: 1rem;
            border-top: 1px solid #2d2340;
        }
        @media (max-width: 900px) {
            .figma-embed iframe { width: 100%!important; }
            main { max-width: 99vw; }
        }
    </style>
</head>
<body>
    <header>
        <h1>Abdelrahman Fakhr</h1>
        <p>UI/UX Designer & Senior Quality Assurance Specialist</p>
    </header>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>
                Hi! I'm Abdelrahman Fakhr, a passionate UI/UX designer and senior QA specialist.
                I love building beautiful interfaces and ensuring top-notch quality in everything I work on.
            </p>
        </section>
        <section id="portfolio">
            <h2>My Portfolio (Figma)</h2>
            <div class="thumbnail-container">
                 <a href="https://www.figma.com/proto/Piid9OtIxysRsSsPzSciS0/Portfolio--Community---Copy-?node-id=2502-1414&p=f&t=Sqe0BNw7ktLa0Pw8-1&scaling=min-zoom&content-scaling=fixed&page-id=2502%3A1413&starting-point-node-id=2502%3A1414" target="_blank">
                    <img src="C:\Users\Ops85af25\Desktop\index1.html\5779230.jpg" alt="Portfolio Thumbnail">
                </a>
            </div>
            <div class="figma-embed">
                <iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="1500" height="800" src="https://embed.figma.com/proto/Piid9OtIxysRsSsPzSciS0/Portfolio--Community---Copy-?node-id=2502-1414&p=f&scaling=min-zoom&content-scaling=fixed&page-id=2502%3A1413&starting-point-node-id=2502%3A1414&embed-host=share" allowfullscreen></iframe>
            </div>
            <p style="text-align:center;">
                <a href="https://www.figma.com/proto/Piid9OtIxysRsSsPzSciS0/Portfolio--Community---Copy-?node-id=2502-1414&p=f&t=Sqe0BNw7ktLa0Pw8-1&scaling=min-zoom&content-scaling=fixed&page-id=2502%3A1413&starting-point-node-id=2502%3A1414" target="_blank">Open my Figma Portfolio &rarr;</a>
            </p>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Abdelrahman Fakhr</p>
    </footer>
</body>
</html>

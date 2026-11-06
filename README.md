<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Digital Minion</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: #121212;
            color: #ffffff;
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #0066ff, #00c2ff);
            text-align: center;
            padding: 100px 20px;
        }

        header h1 {
            font-size: 4rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.3rem;
            opacity: 0.95;
        }

        .container {
            max-width: 1200px;
            margin: auto;
            padding: 80px 20px;
        }

        .section-title {
            text-align: center;
            margin-bottom: 40px;
        }

        .section-title h2 {
            font-size: 2.2rem;
            color: #00c2ff;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }

        .card {
            background: #1e1e1e;
            border-radius: 12px;
            overflow: hidden;
            transition: 0.3s ease;
        }

        .card:hover {
            transform: translateY(-6px);
            background: #252525;
        }

        .card-content {
            padding: 25px;
        }

        .card h3 {
            color: #00c2ff;
            margin-bottom: 10px;
        }

        .game-image {
            width: 100%;
            height: 180px;
            background: linear-gradient(135deg, #2a2a2a, #444);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.5rem;
            color: #888;
        }

        .about {
            text-align: center;
            margin-top: 80px;
        }

        .about p {
            max-width: 800px;
            margin: 20px auto;
            color: #cccccc;
        }

        .cta {
            text-align: center;
            margin-top: 80px;
        }

        .btn {
            display: inline-block;
            background: #00c2ff;
            color: #121212;
            text-decoration: none;
            font-weight: bold;
            padding: 14px 30px;
            border-radius: 8px;
            margin-top: 20px;
            transition: 0.3s ease;
        }

        .btn:hover {
            background: #ffffff;
        }

        footer {
            background: #0d0d0d;
            padding: 30px;
            text-align: center;
            color: #888;
            margin-top: 80px;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2.8rem;
            }

            header p {
                font-size: 1.1rem;
            }
        }
    </style>
</head>
<body>

    <header>
        <h1>Digital Minion</h1>
        <p>Crafting Worlds. Creating Adventures.</p>
    </header>

    <main class="container">

        <section>
            <div class="section-title">
                <h2>Game Portfolio</h2>
            </div>

            <div class="grid">

                <div class="card">
                    <div class="game-image">
                        Game Screenshot
                    </div>
                    <div class="card-content">
                        <h3>Project Alpha</h3>
                        <p>
                            A fast-paced action adventure featuring
                            exploration, combat, and unique abilities.
                        </p>
                    </div>
                </div>

                <div class="card">
                    <div class="game-image">
                        Game Screenshot
                    </div>
                    <div class="card-content">
                        <h3>Project Beta</h3>
                        <p>
                            A strategy game where players build,
                            manage, and expand their digital empire.
                        </p>
                    </div>
                </div>

                <div class="card">
                    <div class="game-image">
                        Game Screenshot
                    </div>
                    <div class="card-content">
                        <h3>Project Gamma</h3>
                        <p>
                            A retro-inspired RPG with modern gameplay
                            systems and handcrafted worlds.
                        </p>
                    </div>
                </div>

            </div>
        </section>

        <section class="about">
            <div class="section-title">
                <h2>About Digital Minion</h2>
            </div>

            <p>
                Digital Minion is an independent game development studio
                focused on creating engaging interactive experiences.
                From experimental prototypes to full-scale releases,
                we build games driven by creativity, technology, and fun.
            </p>
        </section>

        <section class="cta">
        </section>

    </main>
    <footer>
        &copy; 2026 Digital Minion. All Rights Reserved.
    </footer>

</body>
</html>

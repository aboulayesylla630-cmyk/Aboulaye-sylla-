# Aboulaye-sylla-
officiel de AOMS Technologies - L'Architecture de demain, aujourd'hui. 
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AOMS | L'Architecture de Demain</title>
    <style>
        /* Design Futuriste AOMS */
        :root {
            --cyan: #00E5FF;
            --dark-bg: #050505;
            --card-bg: #111111;
            --text-gray: #888888;
        }

        body {
            background-color: var(--dark-bg);
            color: #ffffff;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            margin: 0;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        /* En-tête */
        nav {
            padding: 25px 50px;
            display: flex;
            justify-content: center;
            border-bottom: 1px solid #1a1a1a;
            letter-spacing: 4px;
            font-weight: bold;
            color: var(--cyan);
        }

        /* Section Principale (Hero) */
        .hero {
            padding: 120px 20px;
            text-align: center;
            background: radial-gradient(circle at center, #001f3f 0%, #050505 70%);
        }

        h1 {
            font-size: clamp(3rem, 10vw, 6rem);
            margin: 0;
            letter-spacing: clamp(10px, 2vw, 20px);
            text-transform: uppercase;
            font-weight: 900;
        }

        .slogan {
            color: var(--text-gray);
            font-style: italic;
            font-size: 1.2rem;
            margin-top: 15px;
            letter-spacing: 2px;
        }

        /* Grille des Produits */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 60px 20px;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }

        .card {
            background: var(--card-bg);
            border: 1px solid #222;
            padding: 40px;
            border-radius: 20px;
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            text-align: left;
            position: relative;
            overflow: hidden;
        }

        .card:hover {
            border-color: var(--cyan);
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0, 229, 255, 0.15);
        }

        .card h3 {
            color: var(--cyan);
            margin-top: 0;
            font-size: 1.8rem;
            letter-spacing: 2px;
        }

        .card p {
            color: #ccc;
            line-height: 1.6;
        }

        .badge {
            display: inline-block;
            padding: 4px 12px;
            background: rgba(0, 229, 255, 0.1);
            color: var(--cyan);
            border-radius: 50px;
            font-size: 0.7rem;
            margin-bottom: 15px;
            text-transform: uppercase;
            font-weight: bold;
        }

        /* Bas de page */
        footer {
            margin-top: auto;
            text-align: center;
            padding: 60px;
            color: #333;
            font-size: 0.8rem;
            border-top: 1px solid #111;
            letter-spacing: 1px;
        }

        /* Animation d'entrée */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .hero, .card {
            animation: fadeIn 1s ease-out forwards;
        }
    </style>
</head>
<body>

    <nav>AOMS TECHNOLOGIES</nav>

    <header class="hero">
        <h1>AOMS</h1>
        <p class="slogan">"L'Architecture de demain, aujourd'hui."</p>
    </header>

    <main class="container">
        <article class="card">
            <div class="badge">Sécurité</div>
            <h3>VT25</h3>
            <p><strong>Sentinelle Autonome.</strong> Protection intelligente des infrastructures critiques par analyse prédictive et intervention drone.</p>
        </article>

        <article class="card">
            <div class="badge">Mobilité</div>
            <h3>VT28</h3>
            <p><strong>Vecteur Aérien.</strong> Le transport urbain redéfini : propulsion eVTOL silencieuse, décollage vertical et zéro émission.</p>
        </article>

        <article class="card">
            <div class="badge">Temps</div>
            <h3>VT35</h3>
            <p><strong>Exploration Quantique.</strong> Briser le cycle du destin. Notre technologie expérimentale de navigation temporelle responsable.</p>
        </article>
    </main>

    <footer>
        AOMS © 2026 | CONAKRY, GUINÉE | DÉPLOIEMENT MONDIAL EN COURS
    </footer>

</body>
</html>


<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Page personnelle dédiée à la couture, partage de créations et contact.">
    <title>Ma Page Personnelle - Couture</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 50px 0;
        }
        h1 {
            margin: 0;
        }
        h2 {
            color: #2c3e50;
        }
        section {
            padding: 20px;
            margin: 20px;
        }
        .portfolio {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .portfolio img {
            width: 300px;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px;
        }
        a {
            color: #1abc9c;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue sur ma page de couture !</h1>
        <p>Passionnée par la couture, je partage ici mes créations et mon univers.</p>
    </header>

    <section id="presentation">
        <h2>À propos de moi</h2>
        <p>Je suis une passionnée de couture depuis plusieurs années. J'aime créer des pièces uniques, alliant confort et style. Que ce soit pour des vêtements, des accessoires ou des objets décoratifs, chaque création est le fruit de ma créativité et de mon savoir-faire.</p>
    </section>

    <section id="portfolio">
        <h2>Mes créations</h2>
        <div class="portfolio">
            <!-- Ajoute ici tes images de créations -->
            <img src="https://via.placeholder.com/300x200" alt="Création 1">
            <img src="https://via.placeholder.com/300x200" alt="Création 2">
            <img src="https://via.placeholder.com/300x200" alt="Création 3">
        </div>
    </section>

    <section id="contact">
        <h2>Contactez-moi</h2>
        <p>Vous pouvez me retrouver sur ma page Facebook pour découvrir plus de créations et échanger avec moi :</p>
        <p><a href="https://www.facebook.com/tonnom" target="_blank">Ma page Facebook</a></p>
        <p>Pour toute question, vous pouvez aussi me contacter par email : <a href="mailto:tonemail@example.com">tonemail@example.com</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Ma Page Couture - Tous droits réservés</p>
    </footer>
</body>
</html>

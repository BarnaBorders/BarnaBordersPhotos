<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BarnaBorders - Artiste</title>
    <style>
        /* Styles pour le design du site */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        h1, h2 {
            margin: 0;
            font-size: 36px;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li:last-child {
            margin-right: 0;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }
        .gallery img:hover {
            transform: scale(1.1);
        }
        .social-links {
            text-align: center;
            margin-top: 20px;
        }
        .social-links a {
            display: inline-block;
            margin: 0 10px;
            color: #333;
            font-size: 20px;
            text-decoration: none;
        }
        .payment-links {
            margin-top: 20px;
            text-align: center;
        }
        .payment-links a {
            display: inline-block;
            margin: 0 10px;
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            margin-top: 40px;
            padding: 20px 0;
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>BarnaBorders - Artiste</h1>
        <nav>
            <ul>
                <li><a href="index.html">Accueil</a></li>
                <li><a href="portfolio.html">Portfolio</a></li>
                <li><a href="biographie.html">Biographie</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <div class="container">
        <h2>Bienvenue sur ma page !</h2>
        <p>Je suis BarnaBorders, un artiste passionné par la photographie, la galerie d'art et le street art.</p>
        <p>Explorez mes créations ci-dessous et suivez-moi sur mes réseaux sociaux pour plus de contenu !</p>

        <div class="gallery">
            <a href="images/oeuvre1.jpg"><img src="images/oeuvre1.jpg" alt="Artwork 1"></a>
            <a href="images/oeuvre2.jpg"><img src="images/oeuvre2.jpg" alt="Artwork 2"></a>
            <a href="images/oeuvre3.jpg"><img src="images/oeuvre3.jpg" alt="Artwork 3"></a>
            <!-- Ajoutez d'autres images -->
        </div>

        <div class="social-links">
            <a href="https://www.instagram.com/barnaborders" target="_blank">Instagram</a>
            <a href="https://www.twitter.com/barnaborders" target="_blank">Twitter</a>
            <a href="https://www.facebook.com/barnaborders" target="_blank">Facebook</a>
        </div>

        <div class="payment-links">
            <h3>Achetez mes œuvres :</h3>
            <a href="lien_de_paiement_paypal">Payer avec PayPal</a>
            <a href="lien_de_paiement_stripe">Payer avec Stripe</a>
        </div>
   

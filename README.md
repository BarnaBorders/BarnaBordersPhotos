<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BarnaBorders - Artiste</title>
    <style>
        /* Styles pour le design du site */
        /* ... */

        /* Styles pour la galerie d'images */
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
            <a href="lien_vers_image1.jpg"><img src="lien_vers_image1.jpg" alt="Artwork 1"></a>
            <a href="lien_vers_image2.jpg"><img src="lien_vers_image2.jpg" alt="Artwork 2"></a>
            <a href="lien_vers_image3.jpg"><img src="lien_vers_image3.jpg" alt="Artwork 3"></a>
            <!-- Ajoutez autant d'images que vous le souhaitez -->
        </div>

        <div class="social-links">
            <a href="https://www.instagram.com/barnaborders_collections" target="_blank">Instagram</a>
            <a href="https://www.twitter.com/barnaborders" target="_blank">Twitter</a>
            <a href="https://www.facebook.com/barnaborders" target="_blank">Facebook</a>
        </div>

        <div class="payment-links">
            <h3>Achetez mes œuvres :</h3>
            <a href="lien_de_paiement_paypal">Payer avec PayPal</a>
            <a href="lien_de_paiement_stripe">Payer avec Stripe</a>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 BarnaBorders. Tous droits réservés.</p>
    </footer>
</body>
</html>


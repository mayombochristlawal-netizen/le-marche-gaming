
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Le Marché Gaming</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>
    <h1>LE MARCHÉ GAMING</h1>
    <p>Ta boutique gaming de confiance</p>

    <nav>
        <a href="#accueil">Accueil</a>
        <a href="#jeux">Jeux</a>
        <a href="#promotions">Nos produits</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="accueil">
    <h2>Bienvenue au Marché Gaming</h2>
    <p>Retrouve tes offres gaming préférées au meilleur prix.</p>
    <a href="#promotions" class="button">Découvrir nos offres</a>
</section>

<section id="jeux">
    <h2>Nos jeux</h2>

    <div class="game-container">
        <div class="game-card">
            <h3>Free Fire</h3>
            <p>Diamants et offres Free Fire.</p>
        </div>

        <div class="game-card">
            <h3>PUBG Mobile</h3>
            <p>De futures offres à découvrir.</p>
        </div>

        <div class="game-card">
            <h3>Call of Duty Mobile</h3>
            <p>De futures offres à découvrir.</p>
        </div>
    </div>
</section>

<section id="promotions">
    <h2>Nos produits</h2>
    <p>Retrouve les diamants Free Fire disponibles dans notre boutique.</p>

    <div class="game-container">

        <div class="game-card product-card">
            <h3>110 💎</h3>
            <p class="price">700 FCFA</p>
            <button class="button buy-button"
            onclick="buyProduct('110 Diamants', 700)">
                Acheter
            </button>
            <button class="button whatsapp-button"
            onclick="orderWhatsApp('110 Diamants', 700)">
                WhatsApp
            </button>
        </div>

        <div class="game-card product-card">
            <h3>230 💎</h3>
            <p class="price">1 400 FCFA</p>
            <button class="button buy-button"
            onclick="buyProduct('230 Diamants', 1400)">
                Acheter
            </button>
            <button class="button whatsapp-button"
            onclick="orderWhatsApp('230 Diamants', 1400)">
                WhatsApp
            </button>
        </div>

        <div class="game-card product-card">
            <h3>581 💎</h3>
            <p class="price">3 300 FCFA</p>
            <button class="button buy-button"
            onclick="buyProduct('581 Diamants', 3300)">
                Acheter
            </button>
            <button class="button whatsapp-button"
            onclick="orderWhatsApp('581 Diamants', 3300)">
                WhatsApp
            </button>
        </div>

        <div class="game-card product-card">
            <h3>1 180 💎</h3>
            <p class="price">7 000 FCFA</p>
            <button class="button buy-button"
            onclick="buyProduct('1180 Diamants', 7000)">
                Acheter
            </button>
            <button class="button whatsapp-button"
            onclick="orderWhatsApp('1180 Diamants', 7000)">
                WhatsApp
            </button>
        </div>

        <div class="game-card product-card">
            <h3>2 360 💎</h3>
            <p class="price">15 000 FCFA</p>
            <button class="button buy-button"
            onclick="buyProduct('2360 Diamants', 15000)">
                Acheter
            </button>
            <button class="button whatsapp-button"
            onclick="orderWhatsApp('2360 Diamants', 15000)">
                WhatsApp
            </button>
        </div>

    </div>

    <div id="commande" class="game-card order-box">
        <h2>Finaliser ma commande</h2>

        <p>Produit :
            <span id="selectedProduct">Aucun</span>
        </p>

        <p>Prix :
            <span id="selectedPrice">0 FCFA</span>
        </p>

        <label for="playerID">ID de ton compte Free Fire :</label>

        <input type="number" id="playerID"
        placeholder="Entre ton ID joueur">

        <button class="button buy-button" type="button"
        id="sendOrder">
            Envoyer ma commande
        </button>

        <p>Une fois ta commande envoyée, tu pourras échanger avec la boutique.</p>
    </div>

</section>

<section id="contact">
    <h2>Contact</h2>
    <p>Une question ? Contacte notre boutique sur WhatsApp.</p>
    <a href="https://wa.me/24160170919" class="button">
        Nous contacter
    </a>
</section>

<footer>
    <p>© 2026 Le Marché Gaming - Tous droits réservés.</p>
</footer>

<script src="script.js"></script>

</body>
</html>


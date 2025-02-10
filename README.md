# Royal_kids_boutique
Magasin de vente d’articles homme femme et enfant 
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ROYAL KIDS AND WOMEN BOUTIQUE</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- En-tête -->
    <header>
        <h1>ROYAL KIDS AND WOMEN BOUTIQUE</h1>
        <nav>
            <ul>
                <li><a href="#catalogue">Catalogue</a></li>
                <li><a href="#espace-client">Espace Client</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Section Catalogue -->
    <section id="catalogue">
        <h2>Nos Produits</h2>
        <div class="catalogue-container">
            <div class="produit">
                <img src="produit1.jpg" alt="Produit 1">
                <p>Robe élégante - 20.000 FCFA</p>
            </div>
            <div class="produit">
                <img src="produit2.jpg" alt="Produit 2">
                <p>Chaussures tendance - 15.000 FCFA</p>
            </div>
            <div class="produit">
                <img src="produit3.jpg" alt="Produit 3">
                <p>Ensemble enfant - 10.000 FCFA</p>
            </div>
        </div>
    </section>

    <!-- Section Espace Client -->
    <section id="espace-client">
        <h2>Connexion Client</h2>
        <form>
            <input type="email" placeholder="Email" required>
            <input type="password" placeholder="Mot de passe" required>
            <button type="submit">Se connecter</button>
        </form>
    </section>

    <!-- Section Contact -->
    <section id="contact">
        <h2>Contactez-nous</h2>
        <p>📍 Yopougon Ananerai Oasis</p>
        <p>📞 +225 07 48 30 10 72</p>
        <p>📧 contact@royalkidswomen.com</p>
    </section>

    <!-- Pied de page -->
    <footer>
        <p>© 2024 ROYAL KIDS AND WOMEN BOUTIQUE - Tous droits réservés.</p>
    </footer>

</body>
</html>
/* Styles généraux */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: #f8f8f8;
}

/* En-tête */
header {
    background-color: #ff5733;
    color: white;
    padding: 15px 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

/* Section Catalogue */
#catalogue {
    padding: 40px 20px;
    background-color: white;
}

.catalogue-container {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.produit {
    background: white;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
}

.produit img {
    width: 150px;
    height: auto;
    border-radius: 5px;
}

/* Espace Client */
#espace-client {
    padding: 40px;
    background-color: #f1f1f1;
}

form {
    display: flex;
    flex-direction: column;
    max-width: 300px;
    margin: auto;
}

input, button {
    margin: 10px 0;
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #ddd;
}

button {
    background-color: #ff5733;
    color: white;
    cursor: pointer;
    border: none;
}

button:hover {
    background-color: #c44129;
}

/* Contact */
#contact {
    padding: 30px;
    background-color: white;
}

/* Pied de page */
footer {
    background-color: #222;
    color: white;
    padding: 15px 0;
}

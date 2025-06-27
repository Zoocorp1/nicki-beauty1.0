<!DOCTYPE html><html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nicki Beauty Class - Boutique</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background: #f9f5fc;
      color: #333;
    }
    header {
      background-color: #6c2eb9;
      color: #fff;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }
    header h1 {
      margin: 0;
      font-size: 1.8rem;
    }
    nav a {
      color: #fff;
      margin-left: 1.5rem;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: linear-gradient(to right, #6c2eb9, #c84ec7);
      color: white;
      text-align: center;
      padding: 3rem 1rem;
    }
    .hero h2 {
      font-size: 2.2rem;
      margin-bottom: 0.5rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      padding: 2rem;
    }
    .product {
      background: white;
      border-radius: 12px;
      padding: 1rem;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      max-width: 100%;
      border-radius: 8px;
    }
    .product h3 {
      color: #6c2eb9;
      margin: 0.5rem 0;
    }
    .product button {
      background: #c84ec7;
      color: white;
      border: none;
      padding: 0.7rem 1.2rem;
      border-radius: 20px;
      cursor: pointer;
      font-weight: bold;
      margin-top: 0.5rem;
      transition: background 0.3s;
    }
    .product button:hover {
      background: #6c2eb9;
    }
    footer {
      text-align: center;
      padding: 2rem 1rem;
      background: #eee;
      font-size: 0.9rem;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 1.4rem;
      }
      .hero h2 {
        font-size: 1.6rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Nicki Beauty Class</h1>
    <nav>
      <a href="#produits">Produits</a>
      <a href="https://wa.me/237699499855">Commander</a>
    </nav>
  </header>  <section class="hero">
    <h2>Beauté, Bien-être & Vitalité 100% Naturelle</h2>
    <p>Découvrez notre sélection de compléments bio pour femmes et hommes</p>
  </section>  <section id="produits" class="products">
    <div class="product">
      <img src="https://via.placeholder.com/250x250.png?text=Collag%C3%A8ne" alt="Collagène Bio" />
      <h3>Collagène Bio</h3>
      <p>Peau ferme et éclat naturel</p>
      <button onclick="payerOrangeMoney('Collagène Bio')">Acheter (10 000 FCFA)</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x250.png?text=Elderberry+C+Zinc" alt="Elderberry C Zinc" />
      <h3>Elderberry + Vitamine C + Zinc</h3>
      <p>Immunité renforcée et énergie</p>
      <button onclick="payerOrangeMoney('Elderberry + C + Zinc')">Acheter (10 000 FCFA)</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/250x250.png?text=Shilajit+Pack" alt="Shilajit Pack" />
      <h3>Duo Shilajit</h3>
      <p>Libido & performance masculine</p>
      <button onclick="payerOrangeMoney('Duo Shilajit')">Acheter (10 000 FCFA)</button>
    </div>
    <!-- Ajoute d'autres produits ici -->
  </section>  <footer>
    📍 Boutique : Douala, Yassa - Centre commercial CIPA<br />
    📞 WhatsApp : +237 699 499 855<br />
    &copy; 2025 Nicki Beauty Class – Service Plus
  </footer>  <script>
    function payerOrangeMoney(produit) {
      const numeroOrange = "+237699499855";
      const message = encodeURIComponent(`Bonjour, je souhaite acheter le produit suivant : ${produit}. Mode de paiement : Orange Money.`);
      const lien = `https://wa.me/237699499855?text=${message}`;
      window.open(lien, '_blank');
    }
  </script></body>
</html>

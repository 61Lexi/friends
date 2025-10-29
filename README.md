<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Meine Digitalen Produkte</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f9f9f9;
      color: #333;
    }
    header {
      background: #2d2d2d;
      color: white;
      padding: 20px;
      text-align: center;
    }
    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }
    .product-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
      gap: 20px;
    }
    .product {
      background: white;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 16px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .product h3 {
      margin-top: 0;
    }
    .product p {
      flex-grow: 1;
    }
    .product button {
      background: #007bff;
      color: white;
      border: none;
      padding: 10px 16px;
      border-radius: 4px;
      cursor: pointer;
      font-size: 1em;
    }
    .product button:hover {
      background: #0056b3;
    }
    footer {
      text-align: center;
      padding: 20px;
      color: #666;
    }
  </style>
</head>
<body>
  <header>
    <h1>Digitale Produkte – Direkt via Krypto bezahlen</h1>
    <p>Einfaches, sicheres Bezahlen mit MaxelPay</p>
  </header>
  <div class="container">
    <div class="product-list">
      <!-- Produkt 1 -->
      <div class="product">
        <h3>Produkt 1: Titel hier</h3>
        <p>Kurze Beschreibung zu Produkt 1. Format: PDF / Bild / Video etc.</p>
        <button onclick="openCheckout('PRODUCT1_CHECKOUT_LINK')">Jetzt kaufen</button>
      </div>
      <!-- Produkt 2 -->
      <div class="product">
        <h3>Produkt 2: Titel hier</h3>
        <p>Kurze Beschreibung zu Produkt 2.</p>
        <button onclick="openCheckout('PRODUCT2_CHECKOUT_LINK')">Jetzt kaufen</button>
      </div>
      <!-- Produkt 3 -->
      <div class="product">
        <h3>Produkt 3: Titel hier</h3>
        <p>Kurze Beschreibung zu Produkt 3.</p>
        <button onclick="openCheckout('PRODUCT3_CHECKOUT_LINK')">Jetzt kaufen</button>
      </div>
      <!-- Produkt 4 -->
      <div class="product">
        <h3>Produkt 4: Titel hier</h3>
        <p>Kurze Beschreibung zu Produkt 4.</p>
        <button onclick="openCheckout('PRODUCT4_CHECKOUT_LINK')">Jetzt kaufen</button>
      </div>
      <!-- Produkt 5 -->
      <div class="product">
        <h3>Produkt 5: Titel hier</h3>
        <p>Kurze Beschreibung zu Produkt 5.</p>
        <button onclick="openCheckout('PRODUCT5_CHECKOUT_LINK')">Jetzt kaufen</button>
      </div>
      <!-- Produkt 6 -->
      <div class="product">
        <h3>Produkt 6: Titel hier</h3>
        <p>Kurze Beschreibung zu Produkt 6.</p>
        <button onclick="openCheckout('PRODUCT6_CHECKOUT_LINK')">Jetzt kaufen</button>
      </div>
      <!-- Produkt 7 -->
      <div class="product">
        <h3>Produkt 7: Titel hier</h3>
        <p>Kurze Beschreibung zu Produkt 7.</p>
        <button onclick="openCheckout('PRODUCT7_CHECKOUT_LINK')">Jetzt kaufen</button>
      </div>
      <!-- Produkt 8 -->
      <div class="product">
        <h3>Produkt 8: Titel hier</h3>
        <p>Kurze Beschreibung zu Produkt 8.</p>
        <button onclick="openCheckout('PRODUCT8_CHECKOUT_LINK')">Jetzt kaufen</button>
      </div>
      <!-- Produkt 9 -->
      <div class="product">
        <h3>Produkt 9: Titel hier</h3>
        <p>Kurze Beschreibung zu Produkt 9.</p>
        <button onclick="openCheckout('PRODUCT9_CHECKOUT_LINK')">Jetzt kaufen</button>
      </div>
      <!-- Produkt 10 -->
      <div class="product">
        <h3>Produkt 10: Titel hier</h3>
        <p>Kurze Beschreibung zu Produkt 10.</p>
        <button onclick="openCheckout('PRODUCT10_CHECKOUT_LINK')">Jetzt kaufen</button>
      </div>
    </div>
  </div>

  <footer>
    &copy; 2025 Dein Name / Marke. Alle Rechte vorbehalten.
  </footer>

  <script>
    function openCheckout(checkoutLink) {
      if (!checkoutLink || checkoutLink === 'PRODUCT1_CHECKOUT_LINK') {
        alert('Checkout-Link noch nicht konfiguriert.');
        return;
      }
      // Öffne den Checkout-Link in neuem Tab oder Fenster
      window.open(checkoutLink, '_blank');
    }
  </script>
</body>
</html>

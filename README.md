<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Digital Products Store</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #222;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 20px;
    }
    .productlist {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px,1fr));
      gap: 20px;
    }
    .product {
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 8px;
      padding: 16px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }
    .product h3 {
      margin: 0 0 10px;
    }
    .product p {
      flex-grow: 1;
    }
    .product button {
      background-color: #007bff;
      color: #fff;
      border: none;
      padding: 10px 16px;
      border-radius: 4px;
      cursor: pointer;
      font-size: 1em;
    }
    .product button:hover {
      background-color: #0056b3;
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
    <h1>Digital Products – Pay Easily with Crypto</h1>
    <p>Browse below and pay securely using MaxelPay via crypto.</p>
  </header>

  <div class="container">
    <div class="productlist">

      <!-- Product 1 -->
      <div class="product">
        <h3>Product 1: Title Here</h3>
        <p>Short description for product 1. Format: PDF / Image / Video etc.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT1')">Buy Now</button>
      </div>

      <!-- Product 2 -->
      <div class="product">
        <h3>Product 2: Title Here</h3>
        <p>Short description for product 2.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT2')">Buy Now</button>
      </div>

      <!-- Product 3 -->
      <div class="product">
        <h3>Product 3: Title Here</h3>
        <p>Short description for product 3.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT3')">Buy Now</button>
      </div>

      <!-- Product 4 -->
      <div class="product">
        <h3>Product 4: Title Here</h3>
        <p>Short description for product 4.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT4')">Buy Now</button>
      </div>

      <!-- Product 5 -->
      <div class="product">
        <h3>Product 5: Title Here</h3>
        <p>Short description for product 5.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT5')">Buy Now</button>
      </div>

      <!-- Product 6 -->
      <div class="product">
        <h3>Product 6: Title Here</h3>
        <p>Short description for product 6.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT6')">Buy Now</button>
      </div>

      <!-- Product 7 -->
      <div class="product">
        <h3>Product 7: Title Here</h3>
        <p>Short description for product 7.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT7')">Buy Now</button>
      </div>

      <!-- Product 8 -->
      <div class="product">
        <h3>Product 8: Title Here</h3>
        <p>Short description for product 8.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT8')">Buy Now</button>
      </div>

      <!-- Product 9 -->
      <div class="product">
        <h3>Product 9: Title Here</h3>
        <p>Short description for product 9.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT9')">Buy Now</button>
      </div>

      <!-- Product 10 -->
      <div class="product">
        <h3>Product 10: Title Here</h3>
        <p>Short description for product 10.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT10')">Buy Now</button>
      </div>

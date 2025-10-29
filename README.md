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
    .media-wrapper {
      margin-bottom: 12px;
      width: 100%;
    }
    .media-wrapper img,
    .media-wrapper video {
      width: 100%;
      height: auto;
      border-radius: 4px;
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

      <!-- Product 1 (Image variant) -->
      <div class="product">
        <h3>Product 1: Title Here</h3>
        <div class="media-wrapper">
          <img src=["PLACEHOLDER_IMAGE_URL_1.jpg"](https://github.com/61Lexi/friends/blob/main/WhatsApp%20Image%202025-10-23%20at%2023.17.12.jpeg) alt="Product 1 preview">
        </div>
        <p>Short description for product 1. Format: PDF / Image / Video etc.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT1')">Buy Now</button>
      </div>

      <!-- Product 2 (Video variant) -->
      <div class="product">
        <h3>Product 2: Title Here</h3>
        <div class="media-wrapper">
          <video controls poster="PLACEHOLDER_THUMB_URL_2.jpg">
            <source src="PLACEHOLDER_VIDEO_URL_2.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video>
        </div>
        <p>Short description for product 2. Format: Video tutorial.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT2')">Buy Now</button>
      </div>

      <!-- Product 3 (Image variant) -->
      <div class="product">
        <h3>Product 3: Title Here</h3>
        <div class="media-wrapper">
          <img src="PLACEHOLDER_IMAGE_URL_3.jpg" alt="Product 3 preview">
        </div>
        <p>Short description for product 3.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT3')">Buy Now</button>
      </div>

      <!-- Product 4 (Video variant) -->
      <div class="product">
        <h3>Product 4: Title Here</h3>
        <div class="media-wrapper">
          <video controls poster="PLACEHOLDER_THUMB_URL_4.jpg">
            <source src="PLACEHOLDER_VIDEO_URL_4.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video>
        </div>
        <p>Short description for product 4.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT4')">Buy Now</button>
      </div>

      <!-- Product 5 (Image variant) -->
      <div class="product">
        <h3>Product 5: Title Here</h3>
        <div class="media-wrapper">
          <img src="PLACEHOLDER_IMAGE_URL_5.jpg" alt="Product 5 preview">
        </div>
        <p>Short description for product 5.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT5')">Buy Now</button>
      </div>

      <!-- Product 6 (Video variant) -->
      <div class="product">
        <h3>Product 6: Title Here</h3>
        <div class="media-wrapper">
          <video controls poster="PLACEHOLDER_THUMB_URL_6.jpg">
            <source src="PLACEHOLDER_VIDEO_URL_6.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video>
        </div>
        <p>Short description for product 6.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT6')">Buy Now</button>
      </div>

      <!-- Product 7 (Image variant) -->
      <div class="product">
        <h3>Product 7: Title Here</h3>
        <div class="media-wrapper">
          <img src="PLACEHOLDER_IMAGE_URL_7.jpg" alt="Product 7 preview">
        </div>
        <p>Short description for product 7.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT7')">Buy Now</button>
      </div>

      <!-- Product 8 (Video variant) -->
      <div class="product">
        <h3>Product 8: Title Here</h3>
        <div class="media-wrapper">
          <video controls poster="PLACEHOLDER_THUMB_URL_8.jpg">
            <source src="PLACEHOLDER_VIDEO_URL_8.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video>
        </div>
        <p>Short description for product 8.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT8')">Buy Now</button>
      </div>

      <!-- Product 9 (Image variant) -->
      <div class="product">
        <h3>Product 9: Title Here</h3>
        <div class="media-wrapper">
          <img src="PLACEHOLDER_IMAGE_URL_9.jpg" alt="Product 9 preview">
        </div>
        <p>Short description for product 9.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT9')">Buy Now</button>
      </div>

      <!-- Product 10 (Video variant) -->
      <div class="product">
        <h3>Product 10: Title Here</h3>
        <div class="media-wrapper">
          <video controls poster="PLACEHOLDER_THUMB_URL_10.jpg">
            <source src="PLACEHOLDER_VIDEO_URL_10.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video>
        </div>
        <p>Short description for product 10.</p>
        <button onclick="openCheckout('CHECKOUT_LINK_PRODUCT10')">Buy Now</button>
      </div>

    </div>
  </div>

  <footer>
    &copy; 2025 Your Name / Brand. All Rights Reserved.
  </footer>

  <script>
    function openCheckout(link) {
      if (!link || link.startsWith('CHECKOUT_LINK_')) {
        alert('Checkout link not configured yet.');
        return;
      }
      window.open(link, '_blank');
    }
  </script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Multimart Enterprises - Online Store</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: Arial, sans-serif; line-height: 1.6; background: #f4f4f4; color: #333; }
    header { background: #222; color: #fff; padding: 1rem; text-align: center; position: relative; }
    nav ul { display: flex; justify-content: center; list-style: none; padding: 0.5rem; }
    nav ul li { margin: 0 15px; }
    nav ul li a { color: #fff; text-decoration: none; font-weight: bold; }
    .hero { background: #ddd; padding: 2rem; text-align: center; }
    .product-section { padding: 2rem; background: #fff; margin: 1rem 0; }
    .product-section h3 { margin-bottom: 1rem; }
    .product-grid { display: flex; flex-wrap: wrap; gap: 1rem; }
    .product-card { background: #f9f9f9; border: 1px solid #ccc; padding: 1rem; flex: 1 1 200px; text-align: center; }
    .product-card img { width: 100%; max-width: 150px; height: auto; }
    button { background: #28a745; color: #fff; padding: 0.5rem 1rem; margin-top: 0.5rem; border: none; cursor: pointer; }
    button:hover { background: #218838; }
    #payment { padding: 2rem; background: #e8f5e9; text-align: center; }
    .payments { list-style: none; display: flex; justify-content: center; gap: 2rem; margin-top: 1rem; }
    .payments img { height: 30px; }
    footer { background: #222; color: #fff; text-align: center; padding: 1rem; }

    #cart-icon {
      position: absolute;
      right: 20px;
      top: 20px;
      cursor: pointer;
    }

    .cart-section {
      display: none;
      background: #fff;
      padding: 2rem;
      border: 1px solid #ccc;
      position: fixed;
      top: 50px;
      right: 20px;
      width: 300px;
      max-height: 80vh;
      overflow-y: auto;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    }

    .cart-section .cart-item {
      display: flex;
      justify-content: space-between;
      margin-bottom: 1rem;
    }

    .cart-section .cart-item img {
      width: 50px;
      height: 50px;
    }

    .cart-section button {
      background: #dc3545;
      color: #fff;
      padding: 0.3rem 0.7rem;
      border: none;
      cursor: pointer;
    }

    .cart-section button:hover {
      background: #c82333;
    }

    /* Contact Section Styles */
    .contact-section {
      background: #fff;
      padding: 2rem;
      margin: 1rem 0;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }

    .contact-section table {
      font-family: Arial, sans-serif;
      font-size: 14px;
      line-height: 1.6;
      width: 100%;
    }

    .contact-section td {
      padding: 10px;
      color: #333;
    }

    .contact-section a {
      color: #007bff;
      text-decoration: none;
    }

    .contact-section a:hover {
      text-decoration: underline;
    }

    .contact-section strong {
      color: #222;
    }

    .contact-section .social-links a {
      margin-right: 10px;
    }

    .contact-section .social-links a:last-child {
      margin-right: 0;
    }
  </style>
</head>
<body>

  <header>
    <h1>Multimart Enterprises</h1>
    <nav>
      <ul>
        <li><a href="#shoes">Shoes</a></li>
        <li><a href="#clothes">Clothes</a></li>
        <li><a href="#electronics">Electronics</a></li>
        <li><a href="#home-items">Home Items</a></li>
        <li><a href="#payment">Payments</a></li>
      </ul>
    </nav>
    <!-- Shopping Cart Icon -->
    <div id="cart-icon">
      <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Shopping_cart_icon.svg/1200px-Shopping_cart_icon.svg.png" alt="Cart" width="30" height="30">
      <span id="cart-count">0</span>
    </div>
  </header>

  <section class="hero">
    <h2>Welcome to Multimart Enterprises</h2>
    <p>Shop quality shoes, clothing, home items, and electronics.</p>
  </section>

  <section id="shoes" class="product-section">
    <h3>Shoes for All</h3>
    <div class="product-grid" id="shoes-grid"></div>
  </section>

  <section id="clothes" class="product-section">
    <h3>Clothes for All Ages</h3>
    <div class="product-grid" id="clothes-grid"></div>
  </section>
  
  <section id="electronics" class="product-section">
    <h3>Electronics</h3>
    <div class="product-grid" id="electronics-grid"></div>
  </section>

  <section id="home-items" class="product-section">
    <h3>Home Items</h3>
    <div class="product-grid" id="home-grid"></div>
  </section>

  <section id="payment">
    <h3>Payment Methods</h3>
    <p>We accept the following payment methods:</p>
    <ul class="payments">
      <li><img src="https://upload.wikimedia.org/wikipedia/commons/4/41/Visa_Logo.png" alt="VISA"></li>
      <li><img src="https://upload.wikimedia.org/wikipedia/commons/0/04/Mastercard-logo.png" alt="MasterCard"></li>
      <li>Bank Transfer</li>
      <li>Mobile Money (e.g., M-Pesa)</li>
    </ul>
    <p>Payments are securely processed via Stripe or Flutterwave.</p>
  </section>

  <!-- New Contact Section -->
  <section class="contact-section">
    <table>
      <tr>
        <td>
          <strong>Malcom</strong><br>
          CEO<br>
          <span style="color: #000;">Multimart Enterprises</span><br>
          📞 <a href="tel:+33-753-832-799" style="color: #000;">+33-753-832-799</a> |
          📧 <a href="mailto:you@multimart.enterprises" style="color: #000;">you@multimart.enterprises</a><br>
          🌐 <a href="https://www.multimart.enterprises" style="color: #000;">www.multimart.enterprises</a><br>
          📍 1 chemin des limites 76700 gonfreville l'orcher (FRANCE )<br>
          <div class="social-links" style="margin-top: 6px;">
            Follow us:
            <a href="[LinkedIn URL]" style="text-decoration: none;">LinkedIn</a> |
            <a href="[Instagram URL]" style="text-decoration: none;">Instagram</a> |
            <a href="[Facebook URL]" style="text-decoration: none;">Facebook</a>
          </div>
        </td>
      </tr>
    </table>
  </section>

  <section id="cart" class="cart-section">
    <h3>Your Cart</h3>
    <div id="cart-content">
      <p>Your cart is empty.</p>
    </div>
    <p id="cart-total">Total: $0.00</p>
    <button id="checkout-btn" disabled>Checkout</button>
  </section>

  <footer>
    <p>&copy; 2025 Multimart Enterprises. All rights reserved.</p>
  </footer>

  <script>
    const products = {
      shoes: [
        { name: "Men's Sneakers", price: "$49.99", img: "https://via.placeholder.com/150", size: "Size 42 - Men's" },
        { name: "Children's Shoes", price: "$29.99", img: "https://via.placeholder.com/150", size: "Size 30 - Kids" }
      ],
      clothes: [
        { name: "Adult Jacket", price: "$59.99", img: "https://via.placeholder.com/150", size: "Large - Unisex" },
        { name: "Kids T-Shirt", price: "$15.99", img: "https://via.placeholder.com/150", size: "Small - Boys" }
      ],
      electronics: [
        { name: "Smartphone", price: "$299.99", img: "https://via.placeholder.com/150", size: "6.1 inch - 128GB" }
      ],
      home: [
        { name: "Cookware Set", price: "$79.99", img: "https://via.placeholder.com/150", size: "10-piece Set - Stainless Steel" }
      ]
    };

    let cart = [];

    function updateCart() {
      const cartCount = document.getElementById("cart-count");
      const cartContent = document.getElementById("cart-content");
      const cartTotal = document.getElementById("cart-total");
      const checkoutBtn = document.getElementById("checkout-btn");

      cartCount.textContent = cart.length;

      // Clear previous cart content
      cartContent.innerHTML = '';

      if (cart.length === 0) {
        cartContent.innerHTML = '<p>Your cart is empty.</p>';
        checkoutBtn.disabled = true;
        cartTotal.textContent = 'Total: $0.00';
        return;
      }

      let total = 0;
      cart.forEach(item => {
        const cartItem = document.createElement('div');
        cartItem.className = 'cart-item';
        cartItem.innerHTML = `
          <img src="${item.img}" alt="${item.name}" width="50" height="50">
          <span>${item.name} - ${item.size}</span>
          <span>${item.price}</span>
          <button onclick="removeFromCart('${item.name}')">Remove</button>
        `;
        cartContent.appendChild(cartItem);
        total += parseFloat(item.price.replace('$', ''));
      });

      cartTotal.textContent = `Total: $${total.toFixed(2)}`;
      checkoutBtn.disabled = false;
    }

    function addToCart(product) {
      cart.push(product);
      updateCart();
    }

    function removeFromCart(productName) {
      cart = cart.filter(item => item.name !== productName);
      updateCart();
    }

    function renderProducts(sectionId, items) {
      const container = document.getElementById(sectionId);
      items.forEach(product => {
        const card = document.createElement("div");
        card.className = "product-card";
        card.innerHTML = `
          <img src="${product.img}" alt="${product.name}">
          <h4>${product.name}</h4>
          <div class="size-type">${product.size}</div>
          <p>${product.price}</p>
          <button onclick="addToCart(${JSON.stringify(product)})">Add to Cart</button>
        `;
        container.appendChild(card);
      });
    }

    // Render products
    renderProducts("shoes-grid", Array(6).fill(products.shoes).flat());
    renderProducts("clothes-grid", Array(6).fill(products.clothes).flat());
    renderProducts("electronics-grid", Array(6).fill(products.electronics).flat());
    renderProducts("home-grid", Array(6).fill(products.home).flat());

    // Cart icon click event to show cart
    document.getElementById("cart-icon").addEventListener("click", function() {
      const cartSection = document.getElementById("cart");
      cartSection.style.display = cartSection.style.display === "block" ? "none" : "block";
    });
  </script>
</body>
</html>

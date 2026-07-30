<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MN MART</title>
  <style>
    * { box-sizing: border-box; font-family: 'Segoe UI', sans-serif; margin: 0; padding: 0; }
    body { background-color: #f4f6f9; color: #333; padding-bottom: 30px; }
    
    /* Header */
    header { background: #111827; color: white; padding: 15px 20px; display: flex; justify-content: space-between; align-items: center; position: sticky; top: 0; z-index: 100; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }
    .logo { font-size: 22px; font-weight: bold; letter-spacing: 2px; color: #f39c12; }
    .cart-btn { background: #f39c12; color: white; border: none; padding: 8px 16px; border-radius: 20px; font-weight: bold; cursor: pointer; }

    /* Hero Banner */
    .hero { background: linear-gradient(135deg, #1e3c72, #2a5298); color: white; padding: 25px 20px; text-align: center; }
    .hero h1 { font-size: 24px; margin-bottom: 5px; }
    .hero p { font-size: 13px; opacity: 0.9; }

    /* Products Section */
    .container { padding: 20px 15px; max-width: 600px; margin: 0 auto; }
    
    .grid { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; }
    .card { background: white; border-radius: 12px; padding: 12px; box-shadow: 0 4px 6px rgba(0,0,0,0.05); text-align: center; display: flex; flex-direction: column; justify-content: space-between; border: 1px solid #eee; }
    .card h3 { font-size: 15px; margin: 8px 0 4px; color: #222; }
    .price { color: #27ae60; font-weight: bold; font-size: 14px; margin-bottom: 10px; }
    .add-btn { background: #111827; color: white; border: none; padding: 8px; border-radius: 6px; font-weight: bold; cursor: pointer; width: 100%; transition: 0.2s; }
    
    /* Cart Summary Section */
    .cart-summary { background: white; border-radius: 12px; padding: 15px; margin-top: 25px; box-shadow: 0 4px 6px rgba(0,0,0,0.05); }
    .cart-summary h3 { border-bottom: 1px solid #eee; padding-bottom: 10px; margin-bottom: 10px; font-size: 16px; }
    .cart-item { display: flex; justify-content: space-between; font-size: 14px; margin-bottom: 8px; }
    .total-price { font-weight: bold; font-size: 16px; color: #e67e22; border-top: 1px solid #eee; margin-top: 10px; display: flex; justify-content: space-between; padding-top: 8px; }

    /* Checkout Button */
    .checkout-btn { background: #27ae60; color: white; border: none; width: 100%; padding: 12px; border-radius: 8px; font-weight: bold; font-size: 15px; margin-top: 12px; cursor: pointer; }

    footer { text-align: center; padding: 20px; font-size: 12px; color: #7f8c8d; margin-top: 20px; }
  </style>
</head>
<body>

  <header>
    <div class="logo">MN MART</div>
    <button class="cart-btn">Cart (<span id="cart-count">0</span>)</button>
  </header>

  <div class="hero">
    <h1>MN MART Store</h1>
    <p>Your Quality, Our Priority</p>
  </div>

  <div class="container">
    
    <div class="grid">
      <!-- Item 1 -->
      <div class="card">
        <div>
          <h3>Grocery Items</h3>
          <p class="price">Rs. 500</p>
        </div>
        <button class="add-btn" onclick="addToCart('Grocery Items', 500)">+ Add Item</button>
      </div>

      <!-- Item 2 -->
      <div class="card">
        <div>
          <h3>Cold Drinks & Juices</h3>
          <p class="price">Rs. 180</p>
        </div>
        <button class="add-btn" onclick="addToCart('Cold Drinks', 180)">+ Add Item</button>
      </div>

      <!-- Item 3 -->
      <div class="card">
        <div>
          <h3>Fresh Dairy & Milk</h3>
          <p class="price">Rs. 220</p>
        </div>
        <button class="add-btn" onclick="addToCart('Fresh Dairy', 220)">+ Add Item</button>
      </div>

      <!-- Item 4 -->
      <div class="card">
        <div>
          <h3>Snack Pack</h3>
          <p class="price">Rs. 150</p>
        </div>
        <button class="add-btn" onclick="addToCart('Snack Pack', 150)">+ Add Item</button>
      </div>
    </div>

    <!-- Live Cart Box -->
    <div class="cart-summary">
      <h3>Your Shopping Cart</h3>
      <div id="cart-list">
        <p style="color: #888; font-size: 13px;">Cart is empty. Tap items to add!</p>
      </div>
      <div class="total-price">
        <span>Total Bill:</span>
        <span>Rs. <span id="total-bill">0</span></span>
      </div>
      <button class="checkout-btn" onclick="checkout()">Confirm Order ▶</button>
    </div>

  </div>

  <footer>
    &copy; 2026 MN MART Enterprises. All rights reserved.
  </footer>

  <script>
    let cartCount = 0;
    let totalBill = 0;
    let cartItems = [];

    function addToCart(itemName, price) {
      cartCount++;
      totalBill += price;
      cartItems.push(itemName + " (Rs. " + price + ")");

      document.getElementById('cart-count').innerText = cartCount;
      document.getElementById('total-bill').innerText = totalBill;

      // Update Cart List Text
      let cartList = document.getElementById('cart-list');
      cartList.innerHTML = "";
      cartItems.forEach(function(item) {
        cartList.innerHTML += "<div class='cart-item'><span>" + item + "</span></div>";
      });
    }

    function checkout() {
      if(cartCount === 0) {
        alert("Pehle cart mein koi item add karein!");
      } else {
        alert("MN MART Order Confirmed!\nTotal Bill: Rs. " + totalBill + "\n\nShukriya shopping karne ka!");
        // Reset Cart
        cartCount = 0;
        totalBill = 0;
        cartItems = [];
        document.getElementById('cart-count').innerText = "0";
        document.getElementById('total-bill').innerText = "0";
        document.getElementById('cart-list').innerHTML = "<p style='color: #888; font-size: 13px;'>Cart is empty. Tap items to add!</p>";
      }
    }
  </script>

</body>
</html>

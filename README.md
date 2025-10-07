# ALANKRITA-
Garments of all use and single solution 
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Your Shop Name — Garments</title>
  <style>
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial;color:#222;margin:0;padding:0}
    header{background:#f8f8f8;padding:18px 16px;border-bottom:1px solid #eee}
    .container{max-width:1000px;margin:18px auto;padding:0 12px}
    h1{margin:0;font-size:1.4rem}
    .products{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;margin-top:14px}
    .card{border:1px solid #e6e6e6;border-radius:8px;padding:10px;display:flex;flex-direction:column}
    .card img{width:100%;height:230px;object-fit:cover;border-radius:6px}
    .card h3{margin:10px 0 6px;font-size:1.05rem}
    .price{font-weight:700;margin-bottom:6px}
    .desc{flex:1;margin-bottom:10px;color:#444;font-size:0.95rem}
    .btn{display:inline-block;padding:8px 10px;border-radius:6px;text-decoration:none;border:1px solid #0b6;padding:color:#fff;background:#25D366;color:#fff}
    footer{margin-top:18px;padding:12px 0;color:#666;border-top:1px solid #f0f0f0}
    @media (max-width:420px){.card img{height:180px}}
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>Your Shop Name — Stylish Garments</h1>
      <div>Contact: +91XXXXXXXXXX (WhatsApp)</div>
    </div>
  </header>

  <main class="container">
    <p>Welcome! Browse our collection. To order, click Buy and message us on WhatsApp with size & qty.</p>

    <div class="products">
      <!-- Product 1 -->
      <div class="card">
        <img src="images/product1.jpg" alt="Blue Cotton Kurta">
        <h3>Blue Cotton Kurta</h3>
        <div class="price">₹799</div>
        <div class="desc">Comfortable cotton kurta. Sizes S M L XL. Machine wash cold.</div>
        <a class="btn" href="https://wa.me/91XXXXXXXXXX?text=I%20want%20to%20buy%20Blue%20Cotton%20Kurta%20-%20Size:%20" target="_blank">Buy via WhatsApp</a>
      </div>

      <!-- Product 2 -->
      <div class="card">
        <img src="images/product2.jpg" alt="Floral Women Kurti">
        <h3>Floral Women Kurti</h3>
        <div class="price">₹599</div>
        <div class="desc">Soft rayon kurti with floral print. Sizes S-XL.</div>
        <a class="btn" href="https://wa.me/91XXXXXXXXXX?text=I%20want%20to%20buy%20Floral%20Women%20Kurti%20-%20Size:" target="_blank">Buy via WhatsApp</a>
      </div>
    </div>

    <footer>
      <div>Payment: UPI / Cash on Delivery. Shipping across [Your City/India].</div>
    </footer>
  </main>
</body>
</html>

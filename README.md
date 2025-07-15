<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Noore Haya</title>
  <style>
    body {
      font-family: sans-serif;
      background: #fff;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background: #8e44ad;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #f1f1f1;
      padding: 10px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #8e44ad;
    }
    section {
      padding: 30px;
      text-align: center;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product-card {
      border: 1px solid #ddd;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    .product-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
    }
    .product-card h3 {
      margin: 10px 0 5px;
    }
    footer {
      background: #8e44ad;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Noore Haya</h1>
    <p>হিজাব, ফেসওয়াশ ও সিরাম — আত্মমর্যাদার পরিচয়</p>
  </header>

  <nav>
    <a href="#">হোম</a>
    <a href="#products">পণ্যসমূহ</a>
    <a href="#">যোগাযোগ</a>
  </nav>

  <section id="products">
    <h2>আমাদের পণ্য</h2>
    <div class="products">
      <div class="product-card">
        <img src="https://i.ibb.co/z8W3Nrb/hijab.jpg" alt="হিজাব">
        <h3>হিজাব</h3>
        <p>দাম: ৳২৫০</p>
      </div>
      <div class="product-card">
        <img src="https://i.ibb.co/dLbMwV5/facewash.jpg" alt="ফেসওয়াশ">
        <h3>ফেসওয়াশ</h3>
        <p>দাম: ৳৪৫০</p>
      </div>
      <div class="product-card">
        <img src="https://i.ibb.co/7rSYhX9/serum.jpg" alt="সিরাম">
        <h3>ভিটামিন সি সিরাম</h3>
        <p>দাম: ৳৫৫০</p>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; ২০২৫ Noore Haya | সর্বস্বত্ব সংরক্ষিত</p>
  </footer>
</body>
</html>

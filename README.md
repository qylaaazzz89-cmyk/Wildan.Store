# Wildan.Store
Wildan Store hadir untuk memenuhi kebutuhan fashionmu! 👚 Kami menyediakan berbagai pilihan baju berkualitas, mulai dari kasual hingga formal. Dengan desain yang selalu up-to-date, Wildan Store siap membuatmu tampil percaya diri setiap hari. Kunjungi toko kami sekarang dan nikmati promo menarik! 🛍️
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Wildan Store 👕</title>
  <style>
    body {
      font-family: "Poppins", sans-serif;
      background-color: #e3f2fd;
      color: #0d47a1;
      margin: 0;
    }
    header {
      background-color: #1976d2;
      color: white;
      text-align: center;
      padding: 25px;
    }
    h1 { margin: 0; }
    .menu {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }
    .item {
      background: #ffffff;
      border-radius: 15px;
      box-shadow: 0 3px 10px rgba(0,0,0,.1);
      text-align: center;
      padding: 15px;
      transition: transform 0.2s ease;
    }
    .item:hover { transform: scale(1.03); }
    .item img {
      width: 200px;
      height: 200px;
      border-radius: 15px;
      object-fit: cover;
    }
    .price {
      color: #1565c0;
      font-weight: bold;
    }
    a.button {
      background: #42a5f5;
      color: white;
      padding: 10px 15px;
      border-radius: 8px;
      text-decoration: none;
      display: inline-block;
      margin-top: 8px;
    }
    a.button:hover { background: #1e88e5; }
    footer {
      background: #1976d2;
      color: white;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Wildan Store 👕</h1>
    <p>Baju Keren, Nyaman, dan Terjangkau!</p>
  </header>

  <div class="menu">
    <div class="item">
      <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?auto=format&fit=crop&w=600&q=80" alt="Kaos Polos">
      <h3>Kaos Polos</h3>
      <p class="price">Rp50.000</p>
      <a class="button" href="https://wa.me/6281234567890?text=Halo%20Wildan!%20Saya%20mau%20pesan%20Kaos%20Polos%20👕" target="_blank">Pesan Sekarang</a>
    </div>
    <div class="item">
      <img src="https://images.unsplash.com/photo-1562158070-57129f4a32c1?auto=format&fit=crop&w=600&q=80" alt="Kemeja Pria">
      <h3>Kemeja Pria</h3>
      <p class="price">Rp120.000</p>
      <a class="button" href="https://wa.me/6281234567890?text=Halo%20Wildan!%20Saya%20mau%20pesan%20Kemeja%20Pria%20👕" target="_blank">Pesan Sekarang</a>
    </div>
    <div class="item">
      <img src="https://images.unsplash.com/photo-1602810318383-e386cc2a3cbe?auto=format&fit=crop&w=600&q=80" alt="Jaket Denim">
      <h3>Jaket Denim</h3>
      <p class="price">Rp200.000</p>
      <a class="button" href="https://wa.me/6281234567890?text=Halo%20Wildan!%20Saya%20mau%20pesan%20Jaket%20Denim%20👕" target="_blank">Pesan Sekarang</a>
    </div>
  </div>

  <footer>
    <p>© 2025 Wildan Store</p>
  </footer>
</body>
</html>

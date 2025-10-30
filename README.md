<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF‑8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TXzs Wallpapers</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans‑serif;
      background-color: #111;
      color: #fff;
    }
    header {
      text-align: center;
      padding: 20px;
      background-color: #000;
      box-shadow: 0 2px 5px rgba(0,0,0,0.5);
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
      color: #FFD700;
    }
    nav {
      display: flex;
      justify-content: center;
      margin: 20px 0;
      gap: 20px;
    }
    nav button {
      padding: 10px 20px;
      font-size: 1em;
      cursor: pointer;
      border: none;
      border-radius: 5px;
      background-color: #222;
      color: #fff;
      transition: 0.3s;
    }
    nav button:hover {
      background-color: #FFD700;
      color: #000;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .card {
      background-color: #1a1a1a;
      border-radius: 10px;
      overflow: hidden;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0,0,0,0.5);
    }
    .card img {
      width: 100%;
      display: block;
    }
    .card a {
      display: inline-block;
      margin: 10px 0 20px 0;
      padding: 8px 15px;
      text-decoration: none;
      color: #fff;
      background-color: #FFD700;
      border-radius: 5px;
      transition: 0.3s;
    }
    .card a:hover {
      background-color: #fff;
      color: #000;
    }
  </style>
</head>
<body>

<header>
  <h1>TXzs Wallpapers</h1>
</header>

<nav>
  <button onclick="showSection('cars')">Cars Wallpapers</button>
  <button onclick="showSection('football')">Football Wallpapers</button>
</nav>

<section id="cars" class="gallery">
  <div class="card">
    <img src="https://images.unsplash.com/photo-1601758173920-9f24b6b13d3d?auto=format&fit=crop&w=800&q=80" alt="BMW Car">
    <a href="https://images.unsplash.com/photo-1601758173920-9f24b6b13d3d?auto=format&fit=crop&w=800&q=80" download>Download</a>
  </div>
  <div class="card">
    <img src="https://images.unsplash.com/photo-1597009361895-81bde6a3a730?auto=format&fit=crop&w=800&q=80" alt="Supercar">
    <a href="https://images.unsplash.com/photo-1597009361895-81bde6a3a730?auto=format&fit=crop&w=800&q=80" download>Download</a>
  </div>
  <div class="card">
    <img src="https://images.unsplash.com/photo-1617137041821-58f2d91168d0?auto=format&fit=crop&w=800&q=80" alt="Luxury Car">
    <a href="https://images.unsplash.com/photo-1617137041821-58f2d91168d0?auto=format&fit=crop&w=800&q=80" download>Download</a>
  </div>
</section>

<section id="football" class="gallery" style="display:none;">
  <div class="card">
    <img src="https://images.unsplash.com/photo-1598335413835-921c134ec11f?auto=format&fit=crop&w=800&q=80" alt="Football Player">
    <a href="https://images.unsplash.com/photo-1598335413835-921c134ec11f?auto=format&fit=crop&w=800&q=80" download>Download</a>
  </div>
  <div class="card">
    <img src="https://images.unsplash.com/photo-1602526214300-0a3e5f6e3c7c?auto=format&fit=crop&w=800&q=80" alt="Football Ball">
    <a href="https://images.unsplash.com/photo-1602526214300-0a3e5f6e3c7c?auto=format&fit=crop&w=800&q=80" download>Download</a>
  </div>
  <div class="card">
    <img src="https://images.unsplash.com/photo-1599058917214-5f057a936f8b?auto=format&fit=crop&w=800&q=80" alt="Football Stadium">
    <a href="https://images.unsplash.com/photo-1599058917214-5f057a936f8b?auto=format&fit=crop&w=800&q=80" download>Download</a>
  </div>
</section>

<script>
  function showSection(section) {
    document.getElementById('cars').style.display = (section === 'cars') ? 'grid' : 'none';
    document.getElementById('football').style.display = (section === 'football') ? 'grid' : 'none';
  }
</script>

</body>
</html>

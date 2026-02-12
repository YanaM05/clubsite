<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DORO Marketplace | Aesthetic Cafe & Bakery</title>
    <link rel="stylesheet" href="{{ url_for('static', filename='style.css') }}">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital@0;1&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>

    <nav>
        <div class="logo">DORO <span>MARKETPLACE</span></div>
        <div class="nav-links">
            <a href="#bakery">Bakery</a>
            <a href="#menu">Menu</a>
            <a href="#locations">Connecticut Locations</a>
        </div>
    </nav>

    <header class="hero">
        <div class="hero-overlay">
            <h1>Nourish to Flourish</h1>
            <p>European Soul in the heart of Connecticut</p>
        </div>
    </header>

    <section id="bakery" class="content-section">
        <h2 class="section-title">The Artisan Bakery</h2>
        <div class="aesthetic-grid">
            <div class="card">
                <img src="https://images.unsplash.com/photo-1555507036-ab1f4038808a?q=80&w=1000" alt="Doro Bakery Interior">
                <p>Hand-crafted sourdough and flaky pastries baked fresh every morning.</p>
            </div>
            <div class="card">
                <img src="https://images.unsplash.com/photo-1509440159596-0249088772ff?q=80&w=1000" alt="Fresh Bread">
                <p>Inspired by the yeast alchemy of the finest European boulangeries.</p>
            </div>
        </div>
    </section>

    <section id="menu" class="menu-system">
        <h2>Explore the Menu</h2>
        <div class="filter-bar">
            <button onclick="filterMenu('all')">All</button>
            <button onclick="filterMenu('bakery')">Bakery</button>
            <button onclick="filterMenu('coffee')">Coffee</button>
            <button onclick="filterMenu('mains')">Mains</button>
        </div>
        <div id="menu-display" class="menu-grid">
            </div>
    </section>

    <script src="{{ url_for('static', filename='script.js') }}"></script>
</body>
</html>

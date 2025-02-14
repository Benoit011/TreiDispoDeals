<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TREI Dispo Deals - Exclusive Real Estate Opportunities</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap">
  <style>
    /* General Styles */
    body {
      font-family: 'Montserrat', sans-serif;
      margin: 0;
      padding: 0;
      color: #333;
      line-height: 1.6;
    }

    h1, h2, h3 {
      margin: 0;
      font-weight: 700;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    .container {
      width: 90%;
      max-width: 1200px;
      margin: 0 auto;
    }

    /* Header */
    header {
      background: #002366;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
    }

    /* Hero Section */
    .hero {
      background: url('https://via.placeholder.com/1500x800') no-repeat center center/cover;
      height: 80vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: #fff;
    }

    .hero h2 {
      font-size: 3rem;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 30px;
    }

    .hero .cta-button {
      background: #FFD700;
      color: #002366;
      padding: 15px 30px;
      font-size: 1.1rem;
      border: none;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .hero .cta-button:hover {
      background: #e6b800;
    }

    /* Property Listings */
    .properties {
      padding: 50px 0;
      background: #f9f9f9;
    }

    .properties h2 {
      text-align: center;
      font-size: 2.5rem;
      margin-bottom: 40px;
    }

    .property-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 20px;
    }

    .property-card {
      background: #fff;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    .property-card:hover {
      transform: translateY(-10px);
    }

    .property-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .property-card .details {
      padding: 20px;
    }

    .property-card h3 {
      font-size: 1.5rem;
      margin-bottom: 10px;
    }

    .property-card p {
      font-size: 1rem;
      margin-bottom: 15px;
    }

    .property-card .cta-button {
      background: #002366;
      color: #fff;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .property-card .cta-button:hover {
      background: #001a4d;
    }

    /* Sticky CTA Bar */
    .sticky-cta {
      position: fixed;
      bottom: 0;
      left: 0;
      width: 100%;
      background: #002366;
      color: #fff;
      padding: 15px 0;
      text-align: center;
      z-index: 1000;
      box-shadow: 0 -2px 10px rgba(0, 0, 0, 0.1);
    }

    .sticky-cta .cta-button {
      background: #FFD700;
      color: #002366;
      padding: 10px 20px;
      font-size: 1rem;
      border: none;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .sticky-cta .cta-button:hover {
      background: #e6b800;
    }

    /* Footer */
    footer {
      background: #002366;
      color: #fff;
      text-align: center;
      padding: 20px 0;
      margin-bottom: 60px; /* Add margin to avoid overlap with sticky CTA */
    }

    footer p {
      margin: 0;
    }

    /* Responsive Design */
    @media (max-width: 768px) {
      .hero h2 {
        font-size: 2rem;
      }

      .hero p {
        font-size: 1rem;
      }

      .properties h2 {
        font-size: 2rem;
      }

      .property-grid {
        grid-template-columns: 1fr;
      }

      .sticky-cta {
        padding: 10px 0;
      }

      .sticky-cta .cta-button {
        font-size: 0.9rem;
        padding: 8px 16px;
      }
    }
  </style>
</head>
<body>
  <!-- Header -->
  <header>
    <h1>TREI Dispo Deals</h1>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <div class="container">
      <h2>Unlock Exclusive Real Estate Opportunities</h2>
      <p>Discover premium properties with high ROI potential.</p>
      <button class="cta-button">View Properties</button>
    </div>
  </section>

  <!-- Property Listings -->
  <section class="properties">
    <div class="container">
      <h2>Featured Properties</h2>
      <div class="property-grid">
        <!-- Property 1 -->
        <div class="property-card">
          <img src="https://via.placeholder.com/400x300" alt="Property 1">
          <div class="details">
            <h3>123 Main St, City</h3>
            <p>4 Beds | 3 Baths | 2,500 sqft</p>
            <p>Price: $350,000 | ROI: 12%</p>
            <button class="cta-button">Learn More</button>
          </div>
        </div>

        <!-- Property 2 -->
        <div class="property-card">
          <img src="https://via.placeholder.com/400x300" alt="Property 2">
          <div class="details">
            <h3>456 Elm St, City</h3>
            <p>3 Beds | 2 Baths | 1,800 sqft</p>
            <p>Price: $275,000 | ROI: 10%</p>
            <button class="cta-button">Learn More</button>
          </div>
        </div>

        <!-- Property 3 -->
        <div class="property-card">
          <img src="https://via.placeholder.com/400x300" alt="Property 3">
          <div class="details">
            <h3>789 Oak St, City</h3>
            <p>5 Beds | 4 Baths | 3,200 sqft</p>
            <p>Price: $450,000 | ROI: 15%</p>
            <button class="cta-button">Learn More</button>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2023 TREI Dispo Deals. All rights reserved.</p>
    </div>
  </footer>

  <!-- Sticky CTA Bar -->
  <div class="sticky-cta">
    <p>Interested in our deals? <button class="cta-button">Contact Us Now</button></p>
  </div>
</body>
</html>

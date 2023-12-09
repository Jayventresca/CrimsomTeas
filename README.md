# CrimsomTeas
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Restaurant</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }

    header {
      background-color: #333;
      color: #fff;
      padding: 1em;
      text-align: center;
    }

    section {
      padding: 20px;
      text-align: center;
    }

    menu-item {
      display: flex;
      flex-direction: column;
      align-items: center;
      margin: 20px;
    }

    menu-item img {
      max-width: 100%;
      border-radius: 8px;
    }

    footer {
      background-color: #333;
      color: #fff;
      padding: 1em;
      text-align: center;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <header>
    <h1>Your Restaurant Name</h1>
  </header>

  <section>
    <h2>Welcome to Our Restaurant</h2>
    <p>Discover a world of delicious flavors and culinary delights.</p>
  </section>

  <section>
    <h2>Our Specialties</h2>
    <p>Indulge in a variety of dishes crafted with passion and expertise.</p>
  </section>

  <section>
    <h2>Experience Excellence</h2>
    <p>Each dish is a masterpiece, prepared with the finest ingredients.</p>
  </section>

  <section>
    <h2>Delivery Menu</h2>

    <menu-item>
      <img src="menu-item-1.jpg" alt="Dish 1">
      <p><a href="link-to-delivery-service-1">Order on Skip The Dishes</a></p>
    </menu-item>

    <menu-item>
      <img src="menu-item-2.jpg" alt="Dish 2">
      <p><a href="link-to-delivery-service-2">Order on Fantuan</a></p>
    </menu-item>

    <!-- Add more menu items as needed -->

  </section>

  <footer>
    <p>&copy; 2023 Your Restaurant Name</p>
  </footer>

</body>
</html>

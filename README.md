<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Photography Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background-color: #fff;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #000;
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
    }

    nav {
      background: #111;
      display: flex;
      justify-content: center;
      padding: 0.5rem;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1rem;
      padding: 0.5rem 1rem;
      transition: background 0.3s;
    }

    nav a:hover {
      background: #444;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1rem;
      padding: 2rem;
    }

    .gallery img {
      width: 100%;
      height: auto;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    footer {
      background: #000;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Photography</h1>
    <p>Capturing life through my lens</p>
  </header>
  <nav>
    <a href="#">Home</a>
    <a href="#">Portfolio</a>
    <a href="#">About</a>
    <a href="#">Contact</a>
  </nav>
  <section class="gallery">
    <img src="https://source.unsplash.com/800x600/?nature" alt="Nature Photo">
    <img src="https://source.unsplash.com/800x600/?portrait" alt="Portrait Photo">
    <img src="https://source.unsplash.com/800x600/?city" alt="City Photo">
    <img src="https://source.unsplash.com/800x600/?animals" alt="Animal Photo">
  </section>
  <footer>
    <p>&copy; 2025 My Photography | All Rights Reserved</p>
  </footer>
</body>
</html>

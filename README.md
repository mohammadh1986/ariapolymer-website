# ariapolymer-website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Aria Polymer Resin</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Montserrat', sans-serif; line-height: 1.6; color: #333; }
    header { background: linear-gradient(135deg, #1a1a1a, #444); color: #fff; padding: 60px 20px; text-align: center; position: relative; }
    header img.logo { max-width: 160px; margin-bottom: 20px; }
    header h1 { font-size: 2.5rem; margin-bottom: 10px; }
    header p { font-size: 1.2rem; opacity: 0.9; }

    nav { background: #222; padding: 15px; text-align: center; position: sticky; top: 0; z-index: 1000; }
    nav a { color: #fff; margin: 0 15px; text-decoration: none; font-weight: 600; transition: color 0.3s ease; }
    nav a:hover { color: #00bfa6; }

    section { padding: 70px 12%; animation: fadeIn 1s ease; }
    h2 { color: #111; font-size: 2rem; margin-bottom: 20px; text-align: center; }
    p { font-size: 1.05rem; margin-bottom: 15px; text-align: justify; }

    .products { background: #f7f7f7; border-radius: 10px; padding: 50px 12%; margin: 40px auto; box-shadow: 0 4px 10px rgba(0,0,0,0.1); }

    footer { background: #111; color: #aaa; text-align: center; padding: 25px; font-size: 0.9rem; }

    @keyframes fadeIn { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }

    /* Responsive */
    @media(max-width: 768px){
      section { padding: 50px 8%; }
      header h1 { font-size: 2rem; }
      nav a { display: inline-block; margin: 10px; }
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Aria Polymer Resin Logo" class="logo">
    <h1>Aria Polymer Resin</h1>
    <p>Innovative Adhesives for Automotive and Industrial Applications</p>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About Us</a>
    <a href="#products">Products</a>
    <a href="#technology">Technology</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="home">
    <h2>Welcome to Aria Polymer Resin</h2>
    <p>We specialize in advanced adhesive technologies, delivering high-performance solutions for rubber-to-metal bonding in automotive, oil & gas, and industrial sectors. Our mission is to provide world-class alternatives to imported adhesives through local innovation and expertise.</p>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p>Aria Polymer Resin is a knowledge-based company with deep roots in polymer science and industrial innovation. Led by experienced chemical engineers and supported by an expert R&D team, we combine academic expertise with industrial know-how to create solutions that meet the most demanding challenges.</p>
  </section>

  <section id="products" class="products">
    <h2>Our Products</h2>
    <p><strong>Rubber-to-Metal Adhesive</strong>: A high-performance adhesive engineered to replace imported brands like Chemosil. It offers superior bonding strength, resistance to extreme conditions, and cost efficiency—tailored for automotive, oil & gas, and heavy industry applications.</p>
  </section>

  <section id="technology">
    <h2>Technology & R&D</h2>
    <p>Our R&D focuses on advanced epoxy-phenolic and chlorinated polymer systems. By leveraging proprietary formulations and patent-pending processes, we ensure reliable performance in harsh industrial conditions. We continuously invest in technology that strengthens our competitive advantage and supports local manufacturing in the UAE market.</p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@ariapolymer.com</p>
    <p>Phone: +98-21-1234-5678</p>
    <p>Address: Tehran, Iran</p>
    <p><a href="https://www.linkedin.com" target="_blank">Find us on LinkedIn</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Aria Polymer Resin. All rights reserved.</p>
  </footer>
</body>
</html>
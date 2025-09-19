<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Digital Marketing Professional</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; font-family: Arial, sans-serif; }
    body { line-height: 1.6; color: #333; background: #f9f9f9; }

    header {
      background: #0d6efd;
      color: #fff;
      padding: 1.5rem;
      text-align: center;
    }
    header h1 { font-size: 2rem; }
    header p { margin-top: 5px; font-size: 1.1rem; }

    nav {
      display: flex;
      justify-content: center;
      background: #fff;
      padding: 0.8rem;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    nav a:hover { color: #0d6efd; }

    section { padding: 3rem 1rem; max-width: 1100px; margin: auto; }
    section h2 { text-align: center; margin-bottom: 2rem; color: #0d6efd; }

    .about, .services, .portfolio, .testimonials, .contact {
      background: #fff;
      margin-bottom: 2rem;
      border-radius: 10px;
      padding: 2rem;
      box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    }

    .services-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .service-card {
      background: #f1f5ff;
      padding: 1.5rem;
      border-radius: 8px;
      text-align: center;
      transition: 0.3s;
    }
    .service-card:hover { background: #e0ebff; }

    .portfolio-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .portfolio-item {
      background: #eee;
      height: 180px;
      border-radius: 8px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #666;
    }

    .testimonials p { font-style: italic; margin-bottom: 10px; }
    .testimonials h4 { text-align: right; margin-bottom: 20px; }

    .contact form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }
    .contact input, .contact textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    .contact button {
      background: #0d6efd;
      color: #fff;
      padding: 12px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 1rem;
    }
    .contact button:hover { background: #084298; }

    footer {
      text-align: center;
      padding: 1.5rem;
      background: #0d6efd;
      color: #fff;
    }
  </style>
</head>
<body>

  <header>
    <h1>John Doe</h1>
    <p>Digital Marketing Professional | SEO | Social Media | Ads</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#testimonials">Testimonials</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="about">
    <h2>About Me</h2>
    <p>Hello! I am John Doe, a digital marketing professional with 5+ years of experience 
    helping brands grow online through SEO, social media, paid advertising, and content marketing. 
    My goal is to create result-driven campaigns that boost visibility and generate leads.</p>
  </section>

  <section id="services" class="services">
    <h2>My Services</h2>
    <div class="services-grid">
      <div class="service-card">
        <h3>SEO Optimization</h3>
        <p>Improve website ranking and organic traffic with smart SEO strategies.</p>
      </div>
      <div class="service-card">
        <h3>Social Media Marketing</h3>
        <p>Engaging campaigns to grow your social presence and connect with your audience.</p>
      </div>
      <div class="service-card">
        <h3>Google & Meta Ads</h3>
        <p>Targeted ad campaigns to increase conversions and maximize ROI.</p>
      </div>
      <div class="service-card">
        <h3>Content Strategy</h3>
        <p>Create engaging content that builds brand authority and trust.</p>
      </div>
    </div>
  </section>

  <section id="portfolio" class="portfolio">
    <h2>Portfolio</h2>
    <div class="portfolio-grid">
      <div class="portfolio-item">Project 1</div>
      <div class="portfolio-item">Project 2</div>
      <div class="portfolio-item">Project 3</div>
      <div class="portfolio-item">Project 4</div>
    </div>
  </section>

  <section id="testimonials" class="testimonials">
    <h2>Testimonials</h2>
    <p>"John helped us increase our website traffic by 200% in 3 months. Amazing results!"</p>
    <h4>- Client A</h4>
    <p>"Professional, creative, and data-driven. Highly recommended for digital growth."</p>
    <h4>- Client B</h4>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 John Doe | Digital Marketing Professional</p>
  </footer>

</body>
</html>

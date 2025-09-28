# brandaxihnk
Landing page 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>BrandAxis Media | Grow with Us</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif;}
    body {background: #fdfdfd; color: #222; line-height: 1.6; scroll-behavior: smooth;}

    /* NAVBAR */
    nav {
      position: sticky; top: 0; background: #111;
      display: flex; justify-content: center; padding: 15px 0;
      z-index: 1000; box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }
    nav a {
      color: #fff; text-decoration: none; margin: 0 20px;
      font-weight: 600; transition: color 0.3s;
    }
    nav a:hover {color: #ff7b00;}

    header {
      background: linear-gradient(135deg, #111, #0a66c2);
      color: #fff; text-align: center; padding: 90px 20px;
    }
    header h1 {font-size: 2.8rem; font-weight: 700;}
    header p {margin-top: 10px; font-size: 1.2rem;}
    header a.cta {
      display: inline-block; margin-top: 25px; padding: 14px 28px;
      background: #ff7b00; color: #fff; text-decoration: none;
      font-weight: 600; border-radius: 8px; font-size: 1rem;
      transition: background 0.3s;
    }
    header a.cta:hover {background: #e86b00;}

    section {padding: 70px 20px; max-width: 1100px; margin: auto;}
    h2 {font-size: 2.2rem; margin-bottom: 20px; color: #0a66c2; text-align: center;}
    p.center {text-align: center; max-width: 800px; margin: auto; margin-bottom: 30px;}

    .grid {
      display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px; margin-top: 40px;
    }
    .card {
      background: #fff; border-radius: 12px; padding: 30px 20px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.08);
      transition: transform 0.3s ease;
    }
    .card:hover {transform: translateY(-8px);}
    .card h3 {margin-bottom: 15px; font-size: 1.4rem; color: #0a66c2;}
    .card p {margin-bottom: 20px; font-size: 0.95rem;}
    .card a {
      display: inline-block; padding: 12px 24px;
      background: #ff7b00; color: #fff; text-decoration: none;
      font-weight: 600; border-radius: 8px;
      transition: background 0.3s;
    }
    .card a:hover {background: #e86b00;}

    /* Process steps */
    .process {display: flex; flex-wrap: wrap; justify-content: center; gap: 20px; margin-top: 40px;}
    .step {
      flex: 1 1 250px; background: #fff; border-radius: 12px;
      padding: 25px; text-align: center; box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    }
    .step span {
      display: inline-block; background: #0a66c2; color: #fff;
      width: 40px; height: 40px; line-height: 40px;
      border-radius: 50%; margin-bottom: 15px; font-weight: bold;
    }

    footer {
      background: #111; color: #ccc; padding: 25px 20px; text-align: center; margin-top: 50px;
    }
    footer a {color: #0a66c2; text-decoration: none;}
  </style>
</head>
<body>

  <!-- NAVIGATION -->
  <nav>
    <a href="#services">Services</a>
    <a href="#case-study">Case Study</a>
    <a href="#process">Process</a>
    <a href="#register">Register</a>
  </nav>

  <!-- HERO -->
  <header>
    <h1>Grow with BrandAxis Media</h1>
    <p>Helping Creators & Businesses connect through impactful content 🚀</p>
    <a href="#register" class="cta">Register Now</a>
  </header>

  <!-- SERVICES -->
  <section id="services">
    <h2>Our Services</h2>
    <p class="center">We provide a complete 360° digital solution for brands and creators.</p>
    <div class="grid">
      <div class="card">
        <h3>Influencer Marketing</h3>
        <p>Connect with top creators and influencers to boost your brand visibility.</p>
      </div>
      <div class="card">
        <h3>Paid Ads & Campaigns</h3>
        <p>Targeted ads on social media platforms for maximum ROI and brand awareness.</p>
      </div>
      <div class="card">
        <h3>Video & Content Creation</h3>
        <p>High-quality reels, shorts, and ad content tailored for your brand identity.</p>
      </div>
    </div>
  </section>

  <!-- CASE STUDY -->
  <section id="case-study" style="background:#f7f9fc;">
    <h2>Case Study</h2>
    <p class="center">See how we helped businesses grow with our strategies.</p>
    <div class="grid">
      <div class="card">
        <h3>Fashion Brand</h3>
        <p>Boosted engagement by 300% with influencer-led Instagram campaigns.</p>
      </div>
      <div class="card">
        <h3>Local Startup</h3>
        <p>Achieved 5x sales growth through targeted paid ad campaigns in 3 months.</p>
      </div>
      <div class="card">
        <h3>Creator Growth</h3>
        <p>Helped a creator gain 50k+ followers with content strategy and brand collabs.</p>
      </div>
    </div>
  </section>

  <!-- PROCESS -->
  <section id="process">
    <h2>Our Process</h2>
    <div class="process">
      <div class="step">
        <span>1</span>
        <h3>Register</h3>
        <p>Choose whether you’re a Creator or Business and fill the form.</p>
      </div>
      <div class="step">
        <span>2</span>
        <h3>Onboarding</h3>
        <p>Our team connects with you to understand your goals and requirements.</p>
      </div>
      <div class="step">
        <span>3</span>
        <h3>Strategy</h3>
        <p>We design a custom marketing plan tailored to your needs.</p>
      </div>
      <div class="step">
        <span>4</span>
        <h3>Execution</h3>
        <p>Campaigns go live with measurable results and continuous growth.</p>
      </div>
    </div>
  </section>

  <!-- REGISTER OPTIONS -->
  <section id="register" style="background:#f7f9fc;">
    <h2>Register Now</h2>
    <div class="grid">
      <div class="card">
        <h3>Creator / Influencer</h3>
        <p>Collaborate with brands and monetize your content.</p>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSer3479f3Gbiosm-0VIc7w5UNUmQMmubkGZbye-8E5hBYydrg/viewform" target="_blank">Register as Creator</a>
      </div>
      <div class="card">
        <h3>Business</h3>
        <p>Promote your brand with influencers, ads, and video content.</p>
        <a href="https://docs.google.com/forms/d/e/1FAIpQLSdZZ30U413P21XdbjageG5qPdb5BzZneqrbQQJeqJawQEm2wg/viewform" target="_blank">Register as Business</a>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>📧 brandaxismedia@gmail.com | 📱 Instagram: <a href="https://instagram.com/brandaxis.media">@brandaxis.media</a></p>
    <p>📍 Nashik, Maharashtra, India</p>
    <p>&copy; 2025 BrandAxis Media</p>
  </footer>

</body>
</html>

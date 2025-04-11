<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Road Planners - Motorhome Rentals</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" integrity="sha512-Fo3rlrZj/k7ujTnHg4CGR2D7kSs0v4LLanwT5ZcM8jm3hBElVdS7nXKXvJXejF0h5jZx0ZB/Avl6RBsU7L2cwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: 'Inter', sans-serif; }
    body { background-color: #fff; color: #333; line-height: 1.6; }
    .social-bar { position: absolute; top: 20px; right: 30px; z-index: 10; display: flex; gap: 15px; }
    .social-bar a { color: white; font-size: 1.2rem; text-decoration: none; transition: opacity 0.2s; }
    .social-bar a:hover { opacity: 0.7; }
    header { background: url('https://source.unsplash.com/1600x900/?motorhome,roadtrip') no-repeat center center/cover; height: 100vh; display: flex; flex-direction: column; align-items: center; justify-content: center; text-align: center; color: white; position: relative; }
    header::before { content: ''; position: absolute; top: 0; left: 0; height: 100%; width: 100%; background-color: rgba(0, 0, 0, 0.4); }
    header .content { position: relative; z-index: 1; max-width: 700px; }
    header img.logo { width: 120px; height: auto; margin-bottom: 1rem; }
    header h1 { font-size: 3rem; margin-bottom: 1rem; }
    header p { font-size: 1.25rem; margin-bottom: 2rem; }
    .btn-primary { background-color: #2e86de; color: white; padding: 0.75rem 2rem; text-decoration: none; border-radius: 8px; font-weight: 600; }
    section { padding: 4rem 2rem; max-width: 1200px; margin: auto; }
    .features, .how-it-works, .testimonials, .vehicles, .lead-form { margin-bottom: 3rem; }
    .features div, .how-it-works div, .vehicles div { margin-bottom: 1.5rem; }
    .features h2, .how-it-works h2, .testimonials h2, .vehicles h2, .lead-form h2 { font-size: 2rem; margin-bottom: 1rem; text-align: center; }
    .testimonial { background-color: #f7f7f7; padding: 1.5rem; border-radius: 8px; margin-bottom: 1rem; }
    form { display: flex; flex-direction: column; gap: 1rem; max-width: 600px; margin: auto; }
    input, textarea, button { padding: 0.75rem; border-radius: 6px; border: 1px solid #ccc; font-size: 1rem; }
    button { background-color: #2e86de; color: white; font-weight: 600; border: none; cursor: pointer; }
    footer { text-align: center; padding: 2rem; background-color: #f1f1f1; }
  </style>
</head>
<body>
  <header>
    <div class="social-bar">
      <a href="#" title="Instagram"><i class="fab fa-instagram"></i></a>
      <a href="#" title="Facebook"><i class="fab fa-facebook-f"></i></a>
      <a href="#" title="Twitter"><i class="fab fa-twitter"></i></a>
    </div>
    <div class="content">
      <img src="https://i.imgur.com/WYnkE0N.png" alt="Road Planners Logo" class="logo" />
      <h1>Your Road Trip, Perfectly Planned</h1>
      <p>Explore freely with a fully-supported motorhome rental</p>
      <a href="#lead" class="btn-primary">Plan Your Trip</a>
    </div>
  </header>

  <section class="features">
    <h2>Not Just a Rental — A Road Trip Designed Around You</h2>
    <div><strong>🗺️ Custom Itineraries:</strong> We help you craft the perfect route.</div>
    <div><strong>🚌 Fully Equipped Motorhomes:</strong> All the comforts of home, on wheels.</div>
    <div><strong>📞 24/7 Roadside Support:</strong> Travel with confidence, we’ve got your back.</div>
  </section>

  <section class="how-it-works">
    <h2>Hit the Road in 4 Easy Steps</h2>
    <div>1. Tell us where you want to go</div>
    <div>2. Pick your perfect motorhome</div>
    <div>3. We plan and prep everything for you</div>
    <div>4. You drive, explore, and enjoy</div>
  </section>

  <section class="testimonials">
    <h2>What Our Travelers Say</h2>
    <div class="testimonial">“We traveled from coast to coast with zero stress. Everything was taken care of!” – The Martins</div>
    <div class="testimonial">“Road Planners made our family road trip unforgettable.” – Olivia R.</div>
  </section>

  <section class="vehicles">
    <h2>Comfort Meets Adventure</h2>
    <div><strong>Compact Van:</strong> Great for couples</div>
    <div><strong>Family Motorhome:</strong> Roomy and reliable</div>
    <div><strong>Luxury Option:</strong> Travel in high-end style</div>
  </section>

  <section class="lead-form" id="lead">
    <h2>Ready to Plan Your Road Trip?</h2>
    <p style="text-align: center; margin-bottom: 2rem;">Fill in a few quick details and we’ll send you a personalized travel plan.</p>
    <form action="https://formspree.io/f/your-id" method="POST">
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <input type="text" name="dates" placeholder="Travel Dates" />
      <input type="text" name="destinations" placeholder="Destination(s)" />
      <textarea name="message" placeholder="What kind of experience are you looking for?"></textarea>
      <button type="submit">Send My Plan</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Road Planners. All rights reserved.</p>
  </footer>
</body>
</html>

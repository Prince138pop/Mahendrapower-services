<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Mahendra power Electrician Service</title>
<style>
  /* Reset and base */
  * {
    margin: 0; padding: 0; box-sizing: border-box;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
  body {
    background: #f6f8fa;
    color: #333;
    line-height: 1.6;
  }
  header {
    background: #0077cc;
    color: #fff;
    padding: 1.5rem 2rem;
    text-align: center;
  }
  header h1 {
    font-size: 2.5rem;
    letter-spacing: 2px;
  }

  nav {
    margin-top: 0.5rem;
  }
  nav a {
    color: #fff;
    margin: 0 1rem;
    text-decoration: none;
    font-weight: 600;
    transition: color 0.3s ease;
  }
  nav a:hover {
    color: #ffdd57;
  }

  .hero {
    background: url('https://images.unsplash.com/photo-1557683316-973673baf926?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
    height: 400px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    text-shadow: 2px 2px 6px rgba(0,0,0,0.7);
  }

  .hero h2 {
    font-size: 3rem;
    background: rgba(0,0,0,0.3);
    padding: 1rem 2rem;
    border-radius: 10px;
  }

  .container {
    max-width: 1100px;
    margin: 2rem auto;
    padding: 0 2rem;
  }

  section {
    margin-bottom: 3rem;
  }

  h3 {
    font-size: 2rem;
    margin-bottom: 1rem;
    color: #0077cc;
    border-bottom: 3px solid #0077cc;
    padding-bottom: 0.2rem;
  }

  .services {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    gap: 1.5rem;
  }

  .service-card {
    background: white;
    padding: 1.5rem;
    border-radius: 12px;
    box-shadow: 0 6px 12px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
  }

  .service-card:hover {
    transform: translateY(-8px);
    box-shadow: 0 12px 24px rgba(0,0,0,0.15);
  }

  .service-card h4 {
    margin-bottom: 0.7rem;
    color: #333;
  }
  .service-card p {
    font-size: 0.95rem;
    color: #555;
  }

  form {
    background: white;
    padding: 2rem;
    border-radius: 12px;
    box-shadow: 0 6px 12px rgba(0,0,0,0.1);
    max-width: 600px;
    margin: auto;
  }

  form label {
    display: block;
    margin-bottom: 0.3rem;
    font-weight: 600;
    color: #0077cc;
  }

  form input, form textarea {
    width: 100%;
    padding: 0.7rem;
    margin-bottom: 1rem;
    border: 1.5px solid #0077cc;
    border-radius: 8px;
    font-size: 1rem;
    transition: border-color 0.3s ease;
  }

  form input:focus, form textarea:focus {
    border-color: #ffdd57;
    outline: none;
  }

  form button {
    background: #0077cc;
    color: white;
    padding: 0.9rem 2rem;
    font-size: 1.1rem;
    border: none;
    border-radius: 10px;
    cursor: pointer;
    font-weight: 700;
    transition: background 0.3s ease;
  }

  form button:hover {
    background: #005fa3;
  }

  footer {
    text-align: center;
    padding: 1.5rem;
    background: #222;
    color: #fff;
    letter-spacing: 1px;
  }
</style>
</head>
<body>

<header>
  <h1> mahendrapower service </h1>
  <nav>
    <a href="#services">Services</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<div class="hero">
  <h2>Your One-Stop Solution for All Electrical Work</h2>
</div>

<div class="container">
  <section id="services">
    <h3>Our Services</h3>
    <div class="services">
      <div class="service-card">
        <h4>Tar Wiring</h4>
        <p>Complete wiring for homes and offices, safe and reliable.</p>
      </div>
      <div class="service-card">
        <h4>Inverter Installation</h4>
        <p>Efficient and fast installation for your power needs.</p>
      </div>
      <div class="service-card">
        <h4>LED Light Fixing</h4>
        <p>High-quality LED lights for energy saving.</p>
      </div>
      <div class="service-card">
        <h4>Repair & Maintenance</h4>
        <p>Comprehensive service to fix electrical faults.</p>
      </div>
    </div>
  </section>

  <section id="about">
    <h3>About Us</h3>
    <p>I am an experienced electrician providing reliable services. I work in homes, offices, and factories. I strive to complete every job quickly and with quality.</p>
  </section>

  <section id="contact">
    <h3>Contact Us</h3>
    <form onsubmit="return submitForm(event)">
      <label for="name">Name</label>
      <input type="text" id="name" name="name" required />
      
      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" name="phone" required pattern="[0-9]{10}" placeholder="10 digit number" />
      
      <label for="message">Message</label>
      <textarea id="message" name="message" rows="4" required></textarea>
      
      <button type="submit">Send</button>
    </form>
  </section>
</div>

<footer>
  &copy; 2025Mahendra power service  | Phone: +91 96484 24445
</footer>

<script>
function submitForm(event) {
  event.preventDefault();
  alert("Thank you! Your form has been submitted successfully. We will contact you soon.");
  event.target.reset();
  return false;
}
</script>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>A1 Meadow Auto Repairs | Mississauga</title>
  <meta name="description" content="A1 Meadow Auto Repairs in Mississauga: repairs, maintenance, tires & rims, modifications, PPF, ceramic coating, and detailing." />
  <link rel="icon" href="assets/img/shop-sign.jpg" />
  <style>
    :root{
      --bg:#0f1115;
      --card:#ffffff;
      --text:#222;
      --muted:#666;
      --brand:#10a37f;
    }
    * { box-sizing: border-box; }
    html, body { margin:0; padding:0; font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif; color: var(--text); background:#f6f7f9; }
    a { color: var(--brand); text-decoration: none; }
    a:hover { text-decoration: underline; }
    header.hero {
      background: var(--bg);
      color: #fff;
      padding: 28px 18px;
    }
    .wrap { max-width: 1100px; margin: 0 auto; padding: 0 12px; }
    .topbar { display:flex; align-items:center; gap:16px; flex-wrap:wrap; }
    .logo-img { height:56px; width:auto; border-radius:6px; object-fit:cover; }
    h1.brand { margin:0; font-size: clamp(26px, 4vw, 40px); letter-spacing: 0.5px; }
    .tagline { margin-top:6px; font-size: clamp(14px, 2.5vw, 18px); color:#d6d6d6; }
    nav { margin-top:18px; display:flex; gap:18px; flex-wrap:wrap; }
    nav a { color:#cfd3d8; padding:8px 10px; border-radius:8px; }
    nav a:hover { background: rgba(255,255,255,0.08); }
    .cta-row { margin-top:18px; display:flex; gap:10px; flex-wrap:wrap; }
    .cta { display:inline-block; background:#ffffff; color:#111; padding:10px 14px; border-radius:10px; font-weight:600; }
    .cta.secondary { background:transparent; color:#fff; border:1px solid rgba(255,255,255,0.25); }

    section { padding: 44px 0; }
    h2 { margin: 0 0 16px; font-size: clamp(22px, 3.5vw, 32px); }
    p.lead { color: var(--muted); max-width: 70ch; }
    .grid { display:grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap:16px; }
    .card { background: var(--card); border-radius:14px; padding:18px; box-shadow: 0 6px 18px rgba(0,0,0,.06); }
    .card h3 { margin:8px 0 6px; }
    .card p { margin:0; color: var(--muted); }

    .contact { background:#fff; border-radius:14px; box-shadow: 0 6px 18px rgba(0,0,0,.06); padding:18px; }
    form input, form textarea { width:100%; padding:12px; margin-top:10px; border:1px solid #e3e6ea; border-radius:10px; }
    form button { margin-top:10px; padding:12px 14px; border:none; border-radius:10px; background: var(--brand); color:#fff; font-weight:700; cursor:pointer; }
    form button:hover { filter:brightness(0.95); }
    .cols { display:grid; grid-template-columns: 1.2fr 1fr; gap:18px; }
    @media (max-width: 880px){ .cols { grid-template-columns: 1fr; } }
    footer { text-align:center; color:#777; padding:20px; }
  </style>
</head>
<body>

<header class="hero">
  <div class="wrap">
    <div class="topbar">
      <img class="logo-img" src="shop-sign.jpeg" alt="A1 Meadow Auto Repairs shop sign logo" />
      <div>
        <h1 class="brand">A1 Meadow Auto Repairs</h1>
        <div class="tagline">Trusted Auto Repairs, Modifications & Detailing in Mississauga</div>
      </div>
    </div>
    <nav aria-label="Primary">
      <a href="#services">Services</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
      <a href="tel:+19059814845">Call: 905-981-4845</a>
    </nav>
    <div class="cta-row">
      <a class="cta" href="tel:+19059814845">📞 Book by Phone</a>
      <a class="cta secondary" href="mailto:a1meadowautorepairs@gmail.com">✉️ Email Us</a>
    </div>
  </div>
</header>

<main class="wrap">
  <section id="services">
    <h2>Our Services</h2>
    <p class="lead">Repairs, maintenance and appearance protection for all makes & models. Performance and aesthetic upgrades available.</p>
    <div class="grid">
      <div class="card"><h3>General Repairs & Maintenance</h3><p>Oil changes, tune‑ups, brakes, diagnostics.</p></div>
      <div class="card"><h3>Tires & Rims</h3><p>Installation, balancing, rotations, performance sets.</p></div>
      <div class="card"><h3>Modifications</h3><p>Custom performance & aesthetic upgrades.</p></div>
      <div class="card"><h3>PPF (Paint Protection Film)</h3><p>High‑grade film to protect your paint.</p></div>
      <div class="card"><h3>Ceramic Coating</h3><p>Long‑lasting protection and gloss.</p></div>
      <div class="card"><h3>Detailing</h3><p>Interior & exterior detailing packages.</p></div>
    </div>
  </section>

  <section id="about">
    <h2>About Us</h2>
    <p class="lead">We’re a local Mississauga shop focused on honest advice, quality workmanship, and fast turnaround. From routine maintenance to premium upgrades, we care for your car like it’s our own.</p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <div class="cols">
      <div class="contact">
        <p><strong>Address:</strong> 66 Thomas St Unit 18, Mississauga, Ontario, Canada L5M 2P3</p>
        <p><strong>Phone:</strong> <a href="tel:+19059814845">+1 905-981-4845</a></p>
        <p><strong>Email:</strong> <a href="mailto:a1meadowautorepairs@gmail.com">a1meadowautorepairs@gmail.com</a></p>
        <form name="contact-form" onsubmit="event.preventDefault(); alert('Thanks! We will contact you shortly.'); this.reset();">
          <input type="text" name="name" placeholder="Your Name" required>
          <input type="email" name="email" placeholder="Your Email" required>
          <input type="tel" name="phone" placeholder="Phone Number">
          <textarea name="message" rows="4" placeholder="How can we help?" required></textarea>
          <button type="submit">Send</button>
        </form>
      </div>
      <div class="card" style="padding:0; overflow:hidden;">
        <iframe
          title="A1 Meadow Auto Repairs on Google Maps"
          width="100%" height="350" style="border:0; display:block;"
          loading="lazy" allowfullscreen
          referrerpolicy="no-referrer-when-downgrade"
          src="https://www.google.com/maps?q=66%20Thomas%20St%20Unit%2018%2C%20Mississauga%2C%20ON%20L5M%202P3&output=embed">
        </iframe>
      </div>
    </div>
  </section>
</main>

<footer>
  © 2025 A1 Meadow Auto Repairs — Mississauga, ON
</footer>
</body>
</html>

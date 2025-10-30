# jake
1<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Business Name — Professional Services</title>
<meta name="description" content="Short business description goes here." />
<style>
  :root{
    --accent:#0b76ef;
    --bg:#f7f9fc;
    --card:#ffffff;
    --text:#0d1721;
    --muted:#5a6b78;
    --radius:12px;
    font-family:Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
  }
  *{box-sizing:border-box}
  body{margin:0;background:var(--bg);color:var(--text);-webkit-font-smoothing:antialiased}
  .container{max-width:1100px;margin:28px auto;padding:20px}
  header{display:flex;align-items:center;justify-content:space-between;gap:16px}
  .brand{display:flex;align-items:center;gap:12px}
  .logo{width:56px;height:56px;border-radius:10px;background:linear-gradient(135deg,var(--accent),#6ad1ff);display:flex;align-items:center;justify-content:center;color:white;font-weight:700;font-size:18px}
  nav a{margin-left:14px;text-decoration:none;color:var(--muted);font-weight:600}
  .hero{display:grid;grid-template-columns:1fr;gap:18px;margin-top:26px;background:transparent}
  .hero-card{background:var(--card);padding:28px;border-radius:var(--radius);box-shadow:0 6px 20px rgba(10,20,30,0.06)}
  h1{margin:0 0 10px;font-size:30px;line-height:1.05}
  p.lead{margin:0;color:var(--muted)}
  .actions{margin-top:18px}
  .btn{display:inline-block;padding:10px 16px;border-radius:10px;text-decoration:none;font-weight:700}
  .btn-primary{background:var(--accent);color:white}
  .btn-ghost{border:1px solid rgba(10,20,30,0.06);background:transparent;color:var(--text)}
  .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-top:18px}
  .card{background:var(--card);padding:16px;border-radius:12px;box-shadow:0 6px 20px rgba(10,20,30,0.04)}
  footer{margin-top:26px;padding:18px 0;color:var(--muted);text-align:center}
  .contact{display:flex;gap:12px;flex-wrap:wrap;align-items:center}
  @media(min-width:800px){
    .hero{grid-template-columns:1fr 420px}
    h1{font-size:40px}
  }
</style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">BN</div>
        <div>
          <div style="font-weight:800">Business Name</div>
          <div style="font-size:12px;color:var(--muted)">Short tagline or location</div>
        </div>
      </div>
      <nav>
        <a href="#services">Services</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <section class="hero">
      <div class="hero-card">
        <h1>Hero headline that explains the main benefit in one line</h1>
        <p class="lead">Two-sentence introduction that describes what you do, who you help, and a clear call to action. Use this space to say why customers should choose you.</p>
        <div class="actions">
          <a class="btn btn-primary" href="#contact">Book a free consult</a>
          <a class="btn btn-ghost" href="#services">See services</a>
        </div>

        <div class="grid" style="margin-top:22px">
          <div class="card"><strong>Service One</strong><p style="margin:8px 0 0;color:var(--muted)">Short description of the first service or product (30-45 words).</p></div>
          <div class="card"><strong>Service Two</strong><p style="margin:8px 0 0;color:var(--muted)">Short description of the second service or product (30-45 words).</p></div>
          <div class="card"><strong>Service Three</strong><p style="margin:8px 0 0;color:var(--muted)">Short description of the third service or product (30-45 words).</p></div>
        </div>
      </div>

      <div style="align-self:center">
        <div style="background:linear-gradient(180deg,#fff,#fafcff);padding:18px;border-radius:12px;box-shadow:0 10px 30px rgba(16,24,40,0.06)">
          <img src="https://images.unsplash.com/photo-1556761175-4b46a572b786?q=80&w=800&auto=format&fit=crop&crop=faces" alt="Hero" style="width:100%;border-radius:8px;display:block" />
          <div style="margin-top:12px">
            <strong>Ready to grow?</strong>
            <p style="margin:6px 0 0;color:var(--muted)">Fast setup, local SEO and a single monthly maintenance option.</p>
            <a class="btn btn-primary" href="#contact" style="margin-top:10px;display:inline-block">Get started</a>
          </div>
        </div>
      </div>
    </section>

    <section id="about" style="margin-top:22px">
      <div class="card">
        <h2 style="margin-top:0">About</h2>
        <p style="margin:6px 0;color:var(--muted)">Short about paragraph (60-90 words). Explain who you are, what you value, and how you help customers. Mention trust signals like years of experience or a satisfaction guarantee if available.</p>
      </div>
    </section>

    <section id="services" style="margin-top:18px">
      <h2>Services</h2>
      <div class="grid" style="margin-top:10px">
        <div class="card"><strong>Service A</strong><p style="margin:8px 0 0;color:var(--muted)">Short description plus a sample price if desired.</p></div>
        <div class="card"><strong>Service B</strong><p style="margin:8px 0 0;color:var(--muted)">Short description plus a sample price if desired.</p></div>
        <div class="card"><strong>Service C</strong><p style="margin:8px 0 0;color:var(--muted)">Short description plus a sample price if desired.</p></div>
      </div>
    </section>

    <section id="contact" style="margin-top:18px">
      <div class="card">
        <h2>Contact</h2>
        <p style="margin:6px 0;color:var(--muted)">Call us: <strong>01234 567890</strong> • Email: <strong>hello@example.com</strong></p>
        <form onsubmit="alert('Form demo — replace with real form or email link');return false;">
          <div style="display:flex;gap:8px;flex-wrap:wrap">
            <input placeholder="Your name" required style="padding:10px;border-radius:8px;border:1px solid #e6eef7;flex:1;min-width:180px" />
            <input placeholder="Email" required style="padding:10px;border-radius:8px;border:1px solid #e6eef7;flex:1;min-width:180px" />
          </div>
          <textarea placeholder="Message" required style="width:100%;margin-top:10px;padding:10px;border-radius:8px;border:1px solid #e6eef7"></textarea>
          <div style="margin-top:10px"><button class="btn btn-primary" type="submit">Send message</button></div>
        </form>
      </div>
    </section>

    <footer>
      <div class="contact">© <span id="year"></span> Business Name &middot; <span style="color:var(--muted)">Made with care • Free preview link</span></div>
    </footer>
  </div>

<script>document.getElementById('year').textContent=new Date().getFullYear();</script>
</body>
</html>

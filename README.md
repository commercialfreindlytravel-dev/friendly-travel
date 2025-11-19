<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Friendly Travel — Transferts & Transports</title>
  <style>
    :root{--primary:#005bbb;--accent:#ff7a00;--bg:#f3f6f9}
    body{margin:0;font-family:Inter,system-ui,Arial,sans-serif;background:var(--bg);color:#222}
    header{background:var(--primary);color:#fff;padding:18px 16px;display:flex;align-items:center;gap:20px}
    header img{height:56px}
    nav{margin-left:auto}
    nav a{color:#fff;text-decoration:none;margin:0 10px;font-weight:600}
    .cta{background:var(--accent);color:#fff;padding:10px 14px;border-radius:8px;text-decoration:none;font-weight:700}
    .hero{background:linear-gradient(0deg,rgba(0,0,0,0.25),rgba(0,0,0,0.25)),url('https://images.unsplash.com/photo-1503376780353-7e6692767b70?auto=format&fit=crop&w=1400&q=80') center/cover;height:380px;display:flex;align-items:center;justify-content:center;color:#fff;text-align:center;padding:24px}
    .hero h1{font-size:2.1rem;margin:0}
    main{max-width:1100px;margin:28px auto;padding:0 16px}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
    .card{background:#fff;border-radius:12px;padding:18px;box-shadow:0 6px 20px rgba(12,30,60,0.06)}
    .card img{width:100%;border-radius:8px;height:160px;object-fit:cover}
    h2{color:var(--primary);margin-top:0}
    .tarif-table{width:100%;border-collapse:collapse;background:#fff;border-radius:12px;overflow:hidden}
    .tarif-table th{background:var(--primary);color:#fff;padding:12px}
    .tarif-table td{padding:12px;border-bottom:1px solid #eee;text-align:center}
    .reservation{display:grid;grid-template-columns:1fr 360px;gap:20px;margin-top:12px}
    form{display:flex;flex-direction:column;gap:10px}
    input,select,textarea{padding:10px;border-radius:8px;border:1px solid #ddd}
    button{background:var(--primary);color:#fff;border:none;padding:12px;border-radius:8px;cursor:pointer;font-weight:700}
    .whatsapp{background:#25d366;color:#fff;padding:12px;border-radius:8px;display:inline-block;text-decoration:none}
    footer{background:var(--primary);color:#fff;padding:18px;text-align:center;margin-top:32px}
    .lang-toggle{font-size:0.9rem}
    @media(max-width:800px){.reservation{grid-template-columns:1fr}}
  </style>
</head>
<body>
  <header style="text-align:center; padding:20px;">
    <img src="logo-friendly-travel.png" alt="Friendly Travel Logo" style="max-width:180px; display:block; margin:0 auto;" />
    <h1>Friendly Travel</h1>
    <p>Transferts privés • Voiture • Minibus • Bus</p>
  </header>

  <div class="hero">
    <div>
      <h1>Transferts & Transport — Confort et sécurité</h1>
      <p style="opacity:0.9;margin-top:8px">Réservez facilement : voiture, minibus ou bus — service fiable 24/7</p>
    </div>
  </div>

  <main>
    <section id="services">
      <h2 data-fr>Nos services</h2>
      <h2 data-en style="display:none">Our services</h2>
      <div class="grid" style="margin-top:12px">
        <div class="card">
          <img src="https://images.unsplash.com/photo-1563729784473-437a0d1d7f9e" alt="Voiture" />
          <h3 data-fr>Voiture privée</h3>
          <h3 data-en style="display:none">Private car</h3>
          <p data-fr>Transfert premium pour 1 à 4 personnes — ponctuel et confortable.</p>
          <p data-en style="display:none">Premium transfer for 1 to 4 passengers — punctual and comfortable.</p>
        </div>
        <div class="card">
          <img src="https://images.unsplash.com/photohttps://www.flouret-tourisme.com/ressources/images/b03f151bf70b.jpg " alt="Minibus" />
          <h3 data-fr>Minibus</h3>
          <h3 data-en style="display:none">Minibus</h3>
          <p data-fr>Idéal pour groupes jusqu'à 12 personnes.</p>
          <p data-en style="display:none">Ideal for groups up to 12 people.</p>
        </div>
        <div class="card">
          <img src="https://images.unsplash.com/photo-1601584115197-04297f1f74f8" alt="Bus" />
          <h3 data-fr>Bus</h3>
          <h3 data-en style="display:none">Bus</h3>
          <p data-fr>Transport pour excursions et grands groupes.</p>
          <p data-en style="display:none">Transport for excursions and large groups.</p>
        </div>
      </div>
    </section>

    <section id="tarifs" style="margin-top:28px">
      <h2 data-fr>Tarifs détaillés</h2>
      <h2 data-en style="display:none">Detailed rates</h2>

      <div style="display:flex;gap:18px;flex-direction:column">
        <table class="tarif-table" aria-label="Tarifs avancés">
          <tr><th data-fr>Service</th><th data-en style="display:none">Service</th><th data-fr>Prix (À partir)</th><th data-en style="display:none">Price (From)</th></tr>
          <tr><td>Voiture privée</td><td style="display:none">Private car</td><td>50 DT</td><td style="display:none">~€15</td></tr>
          <tr><td>Minibus (jusqu'à 12 pers.)</td><td style="display:none">Minibus (up to 12 pax)</td><td>120 DT</td><td style="display:none">~€36</td></tr>
          <tr><td>Bus (groupe)</td><td style="display:none">Bus (group)</td><td>250 DT</td><td style="display:none">~€75</td></tr>
        </table>
        <div class="card">
          <h3 data-fr>Options & suppléments</h3>
          <h3 data-en style="display:none">Options & surcharges</h3>
          <ul>
            <li data-fr>Attente aéroport : 10 DT / 30 min</li>
            <li data-en style="display:none">Airport waiting: 10 DT / 30 min</li>
            <li data-fr>Bagages volumineux : supplément selon véhicule</li>
            <li data-en style="display:none">Oversized luggage: surcharge depending on vehicle</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="reservation" style="margin-top:28px">
      <h2 data-fr>Réservation</h2>
      <h2 data-en style="display:none">Reservation</h2>

      <div class="reservation">
        <div class="card">
          <form id="res-form">
            <input id="name" placeholder="Nom complet / Full name" required />
            <input id="email" type="email" placeholder="Email" />
            <input id="phone" placeholder="Téléphone (ex: +216.. )" required />
            <select id="vehicle">
              <option value="Voiture">Voiture / Car</option>
              <option value="Minibus">Minibus</option>
              <option value="Bus">Bus</option>
            </select>
            <input id="from" placeholder="Lieu de départ / From" />
            <input id="to" placeholder="Destination / To" />
            <input id="date" type="date" />
            <input id="time" type="time" />
            <textarea id="message" placeholder="Message / Détails supplémentaires"></textarea>
            <div style="display:flex;gap:8px">
              <button type="button" onclick="sendEmail()">Envoyer (Email)</button>
              <a id="wa-btn" class="whatsapp" href="#" target="_blank">Réserver via WhatsApp</a>
            </div>
          </form>
        </div>

        <div class="card">
          <h3 data-fr>Contact rapide

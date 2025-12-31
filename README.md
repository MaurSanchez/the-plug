<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Tiered Used Gaming PCs</title>

  <style>
    :root {
      --bg: #0b0e14;
      --card: #151a26;
      --accent: #4da3ff;
      --text: #f2f4f8;
      --muted: #9aa4b2;
    }

    * { box-sizing: border-box; }

    body {
      margin: 0;
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial;
      background: var(--bg);
      color: var(--text);
    }

    header {
      padding: 60px 20px;
      text-align: center;
      background: radial-gradient(circle at top, #1a2140, var(--bg));
    }

    header h1 {
      font-size: 2.6rem;
      margin: 0;
    }

    header p {
      max-width: 700px;
      margin: 15px auto 0;
      color: var(--muted);
      font-size: 1.1rem;
    }

    .container {
      max-width: 1200px;
      margin: auto;
      padding: 40px 20px;
    }

    .tiers {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
    }

    .tier {
      background: var(--card);
      border-radius: 14px;
      padding: 25px;
      border: 1px solid #1f2540;
      transition: transform 0.2s ease, border 0.2s ease;
    }

    .tier:hover {
      transform: translateY(-4px);
      border-color: var(--accent);
    }

    .tier h2 {
      margin-top: 0;
      font-size: 1.4rem;
    }

    .tier ul {
      padding-left: 18px;
      color: var(--muted);
    }

    .price {
      margin-top: 15px;
      font-size: 1.2rem;
      font-weight: bold;
      color: var(--accent);
    }

    .cta {
      margin-top: 50px;
      text-align: center;
      background: #0f1425;
      padding: 40px 20px;
      border-radius: 16px;
    }

    .cta h3 {
      margin-top: 0;
      font-size: 1.6rem;
    }

    .cta p {
      color: var(--muted);
      max-width: 600px;
      margin: 10px auto 20px;
    }

    .button {
      display: inline-block;
      padding: 14px 28px;
      background: var(--accent);
      color: #000;
      text-decoration: none;
      font-weight: 600;
      border-radius: 10px;
    }

    footer {
      text-align: center;
      padding: 25px;
      color: #6f7785;
      font-size: 0.9rem;
    }
  </style>
</head>

<body>

<header>
  <h1>Used Gaming PCs, Done Right</h1>
  <p>
    Performance-tested used gaming PCs organized into clear tiers.
    Honest pricing. No guesswork.
  </p>
</header>

<div class="container">
  <div class="tiers">

    <div class="tier">
      <h2>Low Tier — Entry</h2>
      <ul>
        <li>1080p esports gaming</li>
        <li>Fortnite, Valorant, CS2</li>
        <li>Best budget option</li>
      </ul>
      <div class="price">$400 – $550</div>
    </div>

    <div class="tier">
      <h2>Mid Tier — Sweet Spot</h2>
      <ul>
        <li>1080p high / 1440p medium</li>
        <li>Warzone, GTA V, Apex</li>
        <li>Best value overall</li>
      </ul>
      <div class="price">$600 – $800</div>
    </div>

    <div class="tier">
      <h2>High Tier — Performance</h2>
      <ul>
        <li>1440p high refresh</li>
        <li>Competitive + AAA gaming</li>
        <li>Strong CPU/GPU balance</li>
      </ul>
      <div class="price">$900 – $1200</div>
    </div>

    <div class="tier">
      <h2>Advanced — Enthusiast</h2>
      <ul>
        <li>1440p ultra / 4K capable</li>
        <li>Streaming & creation ready</li>
        <li>Top-end used hardware</li>
      </ul>
      <div class="price">$1300+</div>
    </div>

  </div>

  <div class="cta">
    <h3>Interested in a build?</h3>
    <p>
      Each PC is cleaned, tested, and priced based on real-world performance.
      Message to check availability.
    </p>
    <a class="button" href="#">Contact / Buy</a>
  </div>
</div>

<footer>
  © 2025 Tiered Used Gaming PCs — Built for value & performance
</footer>

</body>
</html>

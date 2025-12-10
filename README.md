<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Torro Aureum 2026 – $TA26 | The Golden Bull of Solana</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta
    name="description"
    content="Torro Aureum 2026 ($TA26) – The Golden Bull of Solana. Community-driven meme token forged for the Year of the Bull."
  />
  <style>
    :root {
      --bg: #050509;
      --bg-soft: #0b0b13;
      --card: #111018;
      --accent: #f4c038;
      --accent-soft: #f4c03822;
      --accent-strong: #ffeb9a;
      --text: #f7f7f7;
      --muted: #a0a0b2;
      --danger: #ff4d4d;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
        sans-serif;
      background: radial-gradient(circle at top, #312445 0, #050509 55%);
      color: var(--text);
      line-height: 1.6;
    }

    a {
      color: inherit;
    }

    .wrapper {
      max-width: 1120px;
      margin: 0 auto;
      padding: 1.5rem;
    }

    header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 1.5rem;
      padding: 0.5rem 0 1.5rem;
    }

    .logo {
      display: flex;
      align-items: center;
      gap: 0.75rem;
    }

    .logo-circle {
      width: 46px;
      height: 46px;
      border-radius: 999px;
      border: 2px solid var(--accent);
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1.8rem;
      box-shadow: 0 0 14px rgba(244, 192, 56, 0.4);
      background: radial-gradient(circle at 30% 20%, #fff4d2 0, #f4c038 40%, #b37a16 100%);
    }

    .logo-text-main {
      font-weight: 600;
      font-size: 1.05rem;
    }

    .logo-text-sub {
      font-size: 0.8rem;
      color: var(--muted);
    }

    nav {
      font-size: 0.9rem;
      display: flex;
      align-items: center;
      flex-wrap: wrap;
      gap: 0.8rem;
    }

    nav a {
      text-decoration: none;
      color: var(--muted);
      padding: 0.25rem 0.3rem;
    }

    nav a:hover {
      color: var(--accent);
    }

    .btn-primary,
    .btn-outline {
      border-radius: 999px;
      border: 1px solid var(--accent);
      padding: 0.55rem 1.4rem;
      font-size: 0.9rem;
      cursor: pointer;
      text-decoration: none;
      transition: transform 0.15s ease, box-shadow 0.15s ease,
        background 0.15s ease;
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
      white-space: nowrap;
    }

    .btn-primary {
      background: linear-gradient(130deg, var(--accent), var(--accent-strong));
      color: #261b07;
      font-weight: 600;
      box-shadow: 0 0 18px rgba(244, 192, 56, 0.5);
    }

    .btn-primary:hover {
      transform: translateY(-1px);
      box-shadow: 0 0 24px rgba(244, 192, 56, 0.8);
    }

    .btn-outline {
      background: transparent;
      color: var(--accent);
    }

    .btn-outline:hover {
      background: var(--accent-soft);
      transform: translateY(-1px);
    }

    main {
      display: grid;
      grid-template-columns: minmax(0, 1.2fr) minmax(0, 1fr);
      gap: 2.3rem;
      align-items: center;
      padding: 1rem 0 2.5rem;
    }

    @media (max-width: 860px) {
      main {
        grid-template-columns: 1fr;
        text-align: center;
      }
      header {
        flex-direction: column;
        align-items: flex-start;
      }
      nav {
        justify-content: flex-start;
      }
      .btn-row {
        justify-content: center;
      }
      .notice {
        margin-inline: auto;
      }
    }

    .badge {
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
      border-radius: 999px;
      padding: 0.25rem 0.9rem;
      background: rgba(0, 0, 0, 0.7);
      border: 1px solid var(--accent-soft);
      color: var(--muted);
      font-size: 0.8rem;
      margin-bottom: 1rem;
    }

    .badge span:nth-child(1) {
      color: var(--accent);
      font-weight: 500;
    }

    h1 {
      font-size: clamp(2.3rem, 4vw, 3.1rem);
      margin-bottom: 0.5rem;
    }

    h1 span {
      background: linear-gradient(120deg, #f4c038, #ffefb0);
      -webkit-background-clip: text;
      color: transparent;
    }

    .subtitle {
      max-width: 38rem;
      color: var(--muted);
      margin-bottom: 1.2rem;
      font-size: 0.98rem;
    }

    .ticker {
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas,
        "Liberation Mono", "Courier New", monospace;
      font-size: 0.9rem;
      color: var(--muted);
      margin-bottom: 0.9rem;
    }

    .ticker strong {
      color: var(--accent-strong);
    }

    .btn-row {
      display: flex;
      flex-wrap: wrap;
      gap: 0.8rem;
      margin-bottom: 1.3rem;
    }

    .notice {
      font-size: 0.8rem;
      color: var(--muted);
      max-width: 32rem;
    }

    .risk {
      color: var(--danger);
      font-weight: 500;
    }

    .hero-card {
      background: radial-gradient(circle at top left, #2b2033 0, #111018 45%);
      border-radius: 1.4rem;
      padding: 1.6rem;
      border: 1px solid rgba(255, 255, 255, 0.05);
      box-shadow: 0 18px 50px rgba(0, 0, 0, 0.7);
    }

    .coin {
      width: 100%;
      aspect-ratio: 1 / 1;
      border-radius: 50%;
      border: 3px solid rgba(244, 192, 56, 0.8);
      background: radial-gradient(circle at 30% 20%, #fff6d9 0, #f4c038 35%, #b37a16 100%);
      display: flex;
      align-items: center;
      justify-content: center;
      position: relative;
      overflow: hidden;
    }

    .coin::before {
      content: "🐂";
      font-size: 4.3rem;
      filter: drop-shadow(0 10px 14px rgba(0, 0, 0, 0.65));
    }

    .coin::after {
      content: "";
      position: absolute;
      inset: 12%;
      border-radius: 50%;
      border: 2px solid rgba(255, 255, 255, 0.35);
      box-shadow: inset 0 0 22px rgba(0, 0, 0, 0.4);
    }

    .coin-label {
      position: absolute;
      bottom: 10%;
      width: 100%;
      text-align: center;
      font-size: 0.75rem;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      color: rgba(34, 19, 0, 0.9);
      font-weight: 600;
    }

    .stat-row {
      display: flex;
      justify-content: space-between;
      margin-top: 1.2rem;
      gap: 0.9rem;
      font-size: 0.85rem;
      color: var(--muted);
    }

    .stat {
      flex: 1;
      background: rgba(0, 0, 0, 0.35);
      border-radius: 0.9rem;
      padding: 0.6rem 0.8rem;
      border: 1px solid rgba(255, 255, 255, 0.06);
    }

    .stat-label {
      font-size: 0.75rem;
      text-transform: uppercase;
      letter-spacing: 0.06em;
      color: var(--muted);
    }

    .stat-value {
      font-size: 0.95rem;
      margin-top: 0.12rem;
      color: var(--text);
    }

    section {
      margin-top: 2.3rem;
      padding: 1.6rem;
      border-radius: 1.2rem;
      background: rgba(8, 8, 16, 0.92);
      border: 1px solid rgba(255, 255, 255, 0.05);
    }

    section h2 {
      font-size: 1.3rem;
      margin-bottom: 0.8rem;
    }

    .section-subtitle {
      font-size: 0.85rem;
      color: var(--muted);
      margin-top: -0.4rem;
      margin-bottom: 0.7rem;
    }

    ul {
      list-style: none;
      margin-top: 0.3rem;
    }

    ul li {
      margin-bottom: 0.4rem;
      color: var(--muted);
      font-size: 0.95rem;
      display: flex;
      gap: 0.4rem;
    }

    ul li::before {
      content: "•";
      color: var(--accent);
      margin-top: 0.1rem;
    }

    .two-cols {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 1.4rem;
    }

    @media (max-width: 720px) {
      .two-cols {
        grid-template-columns: 1fr;
      }
    }

    .how-steps {
      counter-reset: step;
    }

    .how-steps li::before {
      counter-increment: step;
      content: counter(step) ".";
      color: var(--accent);
      font-weight: 600;
      margin-right: 0.2rem;
    }

    footer {
      font-size: 0.8rem;
      color: var(--muted);
      margin: 2.2rem 0 1.2rem;
      text-align: center;
    }

    footer a {
      color: var(--accent);
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="wrapper">
    <!-- HEADER -->
    <header>
      <div class="logo">
        <div class="logo-circle"><img width="1024" height="1024" alt="ChatGPT Image 10 déc  2025, 11_25_51" src="https://github.com/user-attachments/assets/44001ab3-70e9-40ce-9a00-1391f929077c" />
</div>
        <div>
          <div class="logo-text-main">Torro Aureum 2026</div>
          <div class="logo-text-sub">The Golden Bull of Solana · $TA26</div>
        </div>
      </div>
      <nav>
        <a href="#about">About</a>
        <a href="#tokenomics">Tokenomics</a>
        <a href="#roadmap">Roadmap</a>
        <a href="#how-to-buy">How to Buy</a>
        <a href="#community">Community</a>
      </nav>
    </header>

    <!-- HERO -->
    <main>
      <div>
        <div class="badge">
          <span>2026 · Year of the Bull</span>
          <span>Meme token · Community driven</span>
        </div>
        <h1>The <span>Golden Bull</span> of Solana.</h1>
        <p class="subtitle">
          <strong>Torro Aureum 2026 ($TA26)</strong> is a community-driven meme token
          forged for the <strong>Year of the Bull</strong> — a digital totem of strength,
          prosperity and unstoppable momentum on Solana.
        </p>
        <div class="ticker">
          Name: <strong>Torro Aureum 2026</strong><br />
          Ticker: <strong>$TA26</strong><br />
          Chain: Solana
        </div>
        <div class="btn-row">
          <!-- Replace # with your real Pump.fun link when live -->
          <a href="#" class="btn-primary" target="_blank" rel="noopener">
            Launch / Trade on Pump.fun
          </a>
          <!-- Replace with your Twitter / Telegram links -->
          <a href="#" class="btn-outline" target="_blank" rel="noopener">
            Join the Community
          </a>
        </div>
        <p class="notice">
          <span class="risk">Disclaimer:</span>
          Torro Aureum 2026 is a speculative meme token with no financial promises.
          Never invest more than you can afford to lose. This is for fun, culture and community.
        </p>
      </div>

      <!-- COIN SIDE -->
      <div class="hero-card">
        <div class="coin">
          <div class="coin-label">TORRO AUREUM · 2026</div>
        </div>
        <div class="stat-row">
          <div class="stat">
            <div class="stat-label">Total Supply</div>
            <div class="stat-value">1,000,000,000 $TA26</div>
          </div>
          <div class="stat">
            <div class="stat-label">Tax</div>
            <div class="stat-value">0% buy · 0% sell</div>
          </div>
          <div class="stat">
            <div class="stat-label">Launch</div>
            <div class="stat-value">Pump.fun · Fair Launch</div>
          </div>
        </div>
      </div>
    </main>

    <!-- ABOUT -->
    <section id="about">
      <h2>About Torro Aureum 2026</h2>
      <p class="section-subtitle">
        2026 is the Year of the Bull. Torro Aureum is its Golden symbol.
      </p>
      <p class="subtitle" style="margin-bottom: 0.6rem;">
        Torro Aureum 2026 is not just another meme token. It is the
        <strong>Golden Bull of Solana</strong> — a mascot for the Year of the Bull,
        representing strength, prosperity and raw market energy.
      </p>
      <p class="subtitle">
        A 100% community-driven project with no roadmap of financial promises.
        Just a legendary Golden Bull charging into 2026, powered by memes, culture
        and the Solana community.
      </p>
    </section>

    <!-- TOKENOMICS + HOW TO BUY -->
    <section id="tokenomics">
      <div class="two-cols">
        <div>
          <h2>Tokenomics</h2>
          <p class="section-subtitle">
            Simple, transparent and community-first.
          </p>
          <ul>
            <li><strong>Total Supply:</strong> 1,000,000,000 $TA26</li>
            <li><strong>Tax:</strong> 0% buy / 0% sell</li>
            <li><strong>Team Allocation:</strong> 0% (fair launch)</li>
            <li><strong>Liquidity:</strong> Locked automatically via Pump.fun</li>
            <li><strong>Distribution:</strong> 100% market-driven</li>
          </ul>
        </div>
        <div id="how-to-buy">
          <h2>How to Buy $TA26</h2>
          <p class="section-subtitle">
            Simple Solana steps for degens and believers.
          </p>
          <ul class="how-steps">
            <li>
              Install a Solana wallet (Phantom, Solflare, Backpack…)
              and fund it with a small amount of SOL.
            </li>
            <li>
              Go to <strong>Pump.fun</strong> and open the official
              <strong>Torro Aureum 2026 / $TA26</strong> page.
            </li>
            <li>
              Connect your Solana wallet and buy the amount of $TA26 you want.
            </li>
            <li>
              Once launched, you’ll be able to trade it on supported Solana DEXs.
            </li>
          </ul>
          <p class="notice" style="margin-top: 0.4rem;">
            Always double-check contract addresses and links. Beware of clones and scams.
          </p>
        </div>
      </div>
    </section>

    <!-- ROADMAP -->
    <section id="roadmap">
      <h2>Roadmap</h2>
      <p class="section-subtitle">
        Meme-first. Community-powered. No financial promises.
      </p>
      <ul>
        <li>
          <strong>Phase 1 — Birth of the Golden Bull</strong><br />
          Launch on Pump.fun, website online, social channels activated, first wave of memes.
        </li>
        <li>
          <strong>Phase 2 — Year of the Bull Momentum</strong><br />
          Community growth, meme contests, tracker listings (DexScreener, Birdeye, etc.).
        </li>
        <li>
          <strong>Phase 3 — Aureum Expansion</strong><br />
          Collaborations, community-led initiatives, optional merch & digital collectibles.
        </li>
        <li>
          <strong>Phase 4 — Legacy of 2026</strong><br />
          $TA26 becomes a symbolic relic of the Year of the Bull on Solana.
        </li>
      </ul>
    </section>

    <!-- COMMUNITY -->
    <section id="community">
      <h2>Community & Links</h2>
      <p class="section-subtitle">
        Everything starts with the herd. Join the Golden Bull.
      </p>
      <ul>
        <li><strong>Pump.fun:</strong> <a href="#" target="_blank" rel="noopener">coming soon</a></li>
        <li><strong>Twitter / X:</strong> <a href="#" target="_blank" rel="noopener">@YourGoldenBull</a></li>
        <li><strong>Telegram:</strong> <a href="#" target="_blank" rel="noopener">t.me/YourGoldenBull</a></li>
        <li><strong>Solscan / Explorer:</strong> to be added after launch</li>
      </ul>
    </section>

    <!-- FOOTER -->
    <footer>
      Torro Aureum 2026 ($TA26) is a meme token with no intrinsic value and no
      expectation of profit. This website is not financial advice.<br />
      Built by the community · Host this page on
      <a href="https://pages.github.com/" target="_blank" rel="noopener">GitHub Pages</a>.
    </footer>
  </div>
</body>
</html>

---
layout: default
title: "Upkeep — Home care, made easy."
description: "Upkeep helps you stay on top of home maintenance, reminders, warranties, and emergency essentials — all in one calm, private place."
---

<div class="uk">
  <section class="uk-hero">
    <div class="uk-bg"></div>

    <div class="uk-hero-content">
      <img class="uk-icon" src="https://is1-ssl.mzstatic.com/image/thumb/Purple221/v4/53/bc/0c/53bc0c67-020d-e37c-a978-ad70c003b5ff/HomeCareIcon-0-0-1x_U007ephone-0-1-sRGB-85-220.png/1024x1024bb.jpg" alt="Upkeep app icon">

      <p class="uk-kicker">Private home maintenance for iPhone</p>
      <h1>Home care,<br><span>made easy.</span></h1>

      <p class="uk-sub">
        Upkeep helps you manage reminders, warranties, receipts, shutoffs,
        emergency essentials, and home-care routines in one calm place.
      </p>

      <a class="uk-store" href="https://apps.apple.com/au/app/upkeep/id6777450786">
        <img src="/assets/download-on-app-store.svg" alt="Download on the App Store">
      </a>

      <div class="uk-trust">
        <span>✓ No account</span>
        <span>✓ No tracking</span>
        <span>✓ Stored on device</span>
      </div>
    </div>

    <div class="uk-phone">
      <img src="/assets/upkeep-app-preview-1.png" alt="Upkeep app screenshot">
    </div>
  </section>

  <section class="uk-section">
    <p class="uk-kicker dark">Everything organised</p>
    <h2>Built for real homes, not spreadsheets.</h2>

    <div class="uk-grid">
      <article><span>🔔</span><h3>Smart reminders</h3><p>Recurring maintenance tasks, due-today nudges, and overdue alerts.</p></article>
      <article><span>🧩</span><h3>Templates</h3><p>Start fast with ready-made routines for common home-care jobs.</p></article>
      <article><span>⭐</span><h3>Upkeep Score</h3><p>See how on-track your home maintenance is at a glance.</p></article>
      <article><span>🧾</span><h3>Warranties</h3><p>Keep warranty details, receipts, and product records easy to find.</p></article>
      <article><span>🛟</span><h3>Emergency info</h3><p>Save shutoffs, switchboard details, codes, and emergency contacts.</p></article>
      <article><span>🔒</span><h3>Private by design</h3><p>No ads, no profiling, no data brokers, and no account required.</p></article>
    </div>
  </section>

  <section class="uk-band">
    <div>
      <p class="uk-kicker">Privacy first</p>
      <h2>Your home’s data stays yours.</h2>
      <p>Upkeep is designed around local-first storage and simple privacy. Your personal home details stay under your control.</p>
      <a href="/privacy/">Read Privacy Policy →</a>
    </div>
  </section>

  <section class="uk-final">
    <h2>Ready to take care of your home?</h2>
    <p>Free on iPhone. Designed for iOS 26.</p>

    <a class="uk-store" href="https://apps.apple.com/au/app/upkeep/id6777450786">
      <img src="/assets/download-on-app-store.svg" alt="Download on the App Store">
    </a>

    <small>Made by Alex Garbin · © 2026</small>
  </section>
</div>

<style>
.uk{
  --navy:#071E3D;
  --blue:#1178FF;
  --teal:#00B894;
  --green:#25B864;
  --orange:#FF9F1C;
  --pink:#FF5C8A;
  --cream:#FFF8EC;
  --card:#FFFFFF;
  --text:#102033;
  --muted:#667085;
  font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
  color:var(--text);
  overflow:hidden;
}

.uk *{box-sizing:border-box}

.uk-hero{
  position:relative;
  display:grid;
  grid-template-columns:minmax(0,1fr) minmax(300px,440px);
  gap:56px;
  align-items:center;
  min-height:min(820px,100vh);
  padding:clamp(56px,7vw,96px) max(24px,calc((100vw - 1240px)/2));
  background:
    radial-gradient(circle at 12% 12%,rgba(255,255,255,.35),transparent 24%),
    radial-gradient(circle at 85% 22%,rgba(255,159,28,.45),transparent 28%),
    linear-gradient(135deg,#073B5C 0%,#087F8C 42%,#32C766 100%);
}

.uk-bg{
  position:absolute;
  inset:auto -10% -32% -10%;
  height:420px;
  background:radial-gradient(circle,rgba(255,255,255,.28),transparent 65%);
  filter:blur(18px);
}

.uk-hero-content,.uk-phone{position:relative;z-index:1}

.uk-icon{
  width:96px;
  height:96px;
  border-radius:24px;
  box-shadow:0 22px 60px rgba(0,0,0,.28);
  margin-bottom:26px;
}

.uk-kicker{
  display:inline-flex;
  margin:0 0 16px;
  padding:8px 14px;
  border-radius:999px;
  background:rgba(255,255,255,.18);
  color:white;
  font-weight:800;
  font-size:.86rem;
  letter-spacing:.02em;
  backdrop-filter:blur(16px);
}

.uk-kicker.dark{
  background:rgba(17,120,255,.10);
  color:var(--blue);
}

.uk h1{
  margin:0;
  color:white;
  font-size:clamp(3.4rem,7vw,6.4rem);
  line-height:.92;
  letter-spacing:-.07em;
  font-weight:900;
}

.uk h1 span{color:#FFD166}

.uk-sub{
  max-width:600px;
  margin:28px 0 30px;
  color:rgba(255,255,255,.9);
  font-size:1.22rem;
  line-height:1.65;
}

.uk-store{
  display:inline-flex;
  line-height:0;
}

.uk-store img{
  height:54px;
  width:auto;
  display:block;
}

.uk-trust{
  display:flex;
  flex-wrap:wrap;
  gap:12px;
  margin-top:26px;
}

.uk-trust span{
  color:white;
  font-weight:800;
  background:rgba(255,255,255,.16);
  border:1px solid rgba(255,255,255,.24);
  padding:10px 14px;
  border-radius:999px;
  backdrop-filter:blur(16px);
}

.uk-phone{
  justify-self:center;
  width:min(420px,90vw);
}

.uk-phone img{
  width:100%;
  height:auto;
  display:block;
  border-radius:42px;
  box-shadow:0 40px 90px rgba(0,0,0,.38);
}

.uk-section{
  padding:90px max(24px,calc((100vw - 1180px)/2));
  background:linear-gradient(180deg,#FFF8EC,#FFFFFF);
  text-align:center;
}

.uk h2{
  margin:0 auto 18px;
  max-width:760px;
  font-size:clamp(2.2rem,4.6vw,4rem);
  line-height:1;
  letter-spacing:-.05em;
  font-weight:900;
}

.uk-grid{
  margin-top:44px;
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:20px;
  text-align:left;
}

.uk-grid article{
  background:white;
  border:1px solid rgba(16,32,51,.08);
  border-radius:30px;
  padding:30px;
  box-shadow:0 24px 70px rgba(16,32,51,.08);
}

.uk-grid span{
  display:grid;
  place-items:center;
  width:60px;
  height:60px;
  border-radius:20px;
  font-size:1.8rem;
  background:linear-gradient(135deg,#EAF3FF,#DFFBEF);
}

.uk-grid h3{
  margin:20px 0 8px;
  font-size:1.22rem;
}

.uk-grid p{
  margin:0;
  color:var(--muted);
}

.uk-band{
  padding:80px max(24px,calc((100vw - 1180px)/2));
  background:
    radial-gradient(circle at 20% 20%,rgba(255,255,255,.25),transparent 26%),
    linear-gradient(135deg,#102033,#0B7A75 55%,#25B864);
  color:white;
}

.uk-band div{max-width:760px}

.uk-band p{
  font-size:1.16rem;
  color:rgba(255,255,255,.86);
}

.uk-band a{
  color:white;
  font-weight:900;
  text-decoration:none;
}

.uk-final{
  text-align:center;
  padding:90px 24px 70px;
  background:linear-gradient(135deg,#FF9F1C,#FF5C8A 45%,#1178FF);
  color:white;
}

.uk-final p{
  font-size:1.2rem;
  margin-bottom:28px;
}

.uk-final small{
  display:block;
  margin-top:34px;
  opacity:.82;
}

@media(max-width:860px){
  .uk-hero{
    grid-template-columns:1fr;
    text-align:center;
    min-height:auto;
    padding:48px 22px 64px;
  }

  .uk-phone{
    width:min(320px,86vw);
  }

  .uk-sub{
    margin-left:auto;
    margin-right:auto;
  }

  .uk-trust{
    justify-content:center;
  }

  .uk-grid{
    grid-template-columns:1fr;
  }
}
</style>

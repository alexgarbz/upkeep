---
layout: default
title: "Upkeep — Home care, made easy."
description: "Upkeep helps you stay on top of home maintenance, reminders, warranties, and emergency essentials — all in one calm, private place."
---

<div class="upk">
  <nav class="upk-nav">
    <a class="upk-brand" href="/">
      <img src="https://is1-ssl.mzstatic.com/image/thumb/Purple221/v4/53/bc/0c/53bc0c67-020d-e37c-a978-ad70c003b5ff/HomeCareIcon-0-0-1x_U007ephone-0-1-sRGB-85-220.png/1024x1024bb.jpg" alt="Upkeep">
      <span>Upkeep</span>
    </a>

    <a class="upk-nav-link" href="/privacy/">Privacy</a>
  </nav>

  <section class="upk-hero">
    <div class="upk-orb one"></div>
    <div class="upk-orb two"></div>
    <div class="upk-orb three"></div>

    <div class="upk-hero-text">
      <p class="upk-pill">Private home care for iPhone</p>

      <h1>
        Your home,<br>
        beautifully<br>
        <span>under control.</span>
      </h1>

      <p class="upk-sub">
        Upkeep turns home maintenance, warranties, receipts, emergency details,
        and recurring reminders into one calm, private system.
      </p>

      <div class="upk-actions">
        <a class="upk-store" href="https://apps.apple.com/au/app/upkeep/id6777450786" aria-label="Download on the App Store">
          <img src="/assets/download-on-app-store.svg" alt="Download on the App Store">
        </a>
      </div>

      <div class="upk-trust">
        <span>No account</span>
        <span>No tracking</span>
        <span>On-device data</span>
      </div>
    </div>

    <div class="upk-visual">
      <div class="upk-phone-wrap">
        <img class="upk-phone" src="/assets/upkeep-app-preview-1.png" alt="Upkeep app screenshot">
      </div>

      <div class="upk-float card-a">
        <strong>85</strong>
        <span>Upkeep Score</span>
      </div>

      <div class="upk-float card-b">
        <strong>Today</strong>
        <span>3 tasks due</span>
      </div>
    </div>
  </section>

  <section class="upk-section upk-light">
    <p class="upk-pill dark">Everything organised</p>
    <h2>Built for real homes, not spreadsheets.</h2>

    <div class="upk-grid">
      <article><span>🔔</span><h3>Smart reminders</h3><p>Recurring home-care tasks, overdue alerts, and due-today nudges.</p></article>
      <article><span>🧩</span><h3>Ready-made templates</h3><p>Start quickly with common routines for seasonal and household jobs.</p></article>
      <article><span>⭐</span><h3>Upkeep Score</h3><p>See how on-track your home care is without digging through lists.</p></article>
      <article><span>🧾</span><h3>Warranties & receipts</h3><p>Keep purchase details, warranty dates, and receipts easy to find.</p></article>
      <article><span>🛟</span><h3>Emergency essentials</h3><p>Save shutoffs, switchboards, alarm codes, and key contacts.</p></article>
      <article><span>🔒</span><h3>Private by design</h3><p>No ads, no account requirement, no tracking, and no data brokers.</p></article>
    </div>
  </section>

  <section class="upk-privacy">
    <div>
      <p class="upk-pill">Privacy first</p>
      <h2>Your home’s data stays yours.</h2>
      <p>Upkeep is designed around simple, local-first privacy so your home details stay under your control.</p>
      <a href="/privacy/">Read Privacy Policy →</a>
    </div>
  </section>

  <section class="upk-final">
    <h2>Home care, made easy.</h2>
    <p>Free on iPhone. Designed for iOS 26.</p>

    <a class="upk-store" href="https://apps.apple.com/au/app/upkeep/id6777450786" aria-label="Download on the App Store">
      <img src="/assets/download-on-app-store.svg" alt="Download on the App Store">
    </a>

    <small>Made by Alex Garbin · © 2026</small>
  </section>
</div>

<style>
html,body{
  margin:0;
  padding:0;
}

.upk{
  --ink:#07111f;
  --muted:#667085;
  --blue:#1677ff;
  --green:#20c878;
  --mint:#dfffee;
  --orange:#ffb347;
  --pink:#ff5c93;
  --violet:#7c5cff;
  --glass:rgba(255,255,255,.16);
  --line:rgba(255,255,255,.24);
  font-family:-apple-system,BlinkMacSystemFont,"SF Pro Display","Segoe UI",Roboto,Helvetica,Arial,sans-serif;
  color:var(--ink);
  background:#050b18;
  overflow:hidden;
}

.upk *{box-sizing:border-box}

.upk-nav{
  position:fixed;
  z-index:20;
  top:18px;
  left:50%;
  transform:translateX(-50%);
  width:min(1120px,calc(100% - 32px));
  height:58px;
  display:flex;
  align-items:center;
  justify-content:space-between;
  padding:8px 10px;
  border:1px solid rgba(255,255,255,.22);
  border-radius:999px;
  background:rgba(255,255,255,.14);
  backdrop-filter:blur(28px) saturate(160%);
  box-shadow:0 20px 70px rgba(0,0,0,.22);
}

.upk-brand{
  display:flex;
  align-items:center;
  gap:10px;
  color:white;
  font-weight:800;
  text-decoration:none;
}

.upk-brand img{
  width:40px;
  height:40px;
  border-radius:11px;
}

.upk-nav-link{
  color:white;
  text-decoration:none;
  font-weight:700;
  padding:10px 16px;
  border-radius:999px;
  background:rgba(255,255,255,.12);
}

.upk-hero{
  position:relative;
  min-height:100vh;
  display:grid;
  grid-template-columns:minmax(0,1.05fr) minmax(320px,.95fr);
  align-items:center;
  gap:48px;
  padding:118px max(24px,calc((100vw - 1240px)/2)) 70px;
  background:
    radial-gradient(circle at 18% 18%,rgba(255,255,255,.24),transparent 22%),
    radial-gradient(circle at 80% 12%,rgba(255,179,71,.35),transparent 30%),
    linear-gradient(135deg,#08111f 0%,#10385a 36%,#119070 70%,#44d46b 100%);
}

.upk-orb{
  position:absolute;
  border-radius:999px;
  filter:blur(10px);
  opacity:.85;
}

.upk-orb.one{
  width:360px;
  height:360px;
  left:-90px;
  bottom:8%;
  background:radial-gradient(circle,#2df6a1,transparent 68%);
}

.upk-orb.two{
  width:420px;
  height:420px;
  right:-120px;
  top:10%;
  background:radial-gradient(circle,#ffcb5c,transparent 66%);
}

.upk-orb.three{
  width:300px;
  height:300px;
  right:28%;
  bottom:-90px;
  background:radial-gradient(circle,#48a7ff,transparent 65%);
}

.upk-hero-text,
.upk-visual{
  position:relative;
  z-index:2;
}

.upk-pill{
  display:inline-flex;
  align-items:center;
  width:max-content;
  margin:0 0 18px;
  padding:9px 15px;
  border-radius:999px;
  color:white;
  background:rgba(255,255,255,.16);
  border:1px solid rgba(255,255,255,.22);
  backdrop-filter:blur(18px);
  font-size:.88rem;
  font-weight:850;
  letter-spacing:.01em;
}

.upk-pill.dark{
  color:#0b6b45;
  background:rgba(32,200,120,.12);
  border-color:rgba(32,200,120,.18);
}

.upk h1{
  max-width:790px;
  margin:0;
  color:white;
  font-size:clamp(4rem,8.8vw,8.4rem);
  line-height:.82;
  letter-spacing:-.085em;
  font-weight:950;
}

.upk h1 span{
  background:linear-gradient(90deg,#fff0a8,#ffb347,#fff);
  -webkit-background-clip:text;
  background-clip:text;
  color:transparent;
}

.upk-sub{
  max-width:620px;
  margin:30px 0 32px;
  color:rgba(255,255,255,.86);
  font-size:clamp(1.08rem,1.7vw,1.32rem);
  line-height:1.65;
}

.upk-store{
  display:inline-flex;
  line-height:0;
}

.upk-store img{
  height:56px;
  width:auto;
  display:block;
}

.upk-trust{
  display:flex;
  flex-wrap:wrap;
  gap:12px;
  margin-top:28px;
}

.upk-trust span{
  color:white;
  font-weight:800;
  padding:11px 15px;
  border-radius:999px;
  background:rgba(255,255,255,.14);
  border:1px solid rgba(255,255,255,.18);
  backdrop-filter:blur(18px);
}

.upk-visual{
  justify-self:center;
  width:min(460px,88vw);
}

.upk-phone-wrap{
  position:relative;
  padding:12px;
  border-radius:54px;
  background:linear-gradient(145deg,rgba(255,255,255,.35),rgba(255,255,255,.06));
  border:1px solid rgba(255,255,255,.24);
  box-shadow:
    0 50px 120px rgba(0,0,0,.42),
    inset 0 1px 0 rgba(255,255,255,.45);
  backdrop-filter:blur(30px);
}

.upk-phone{
  width:100%;
  height:auto;
  display:block;
  border-radius:42px;
}

.upk-float{
  position:absolute;
  z-index:3;
  min-width:148px;
  padding:17px 18px;
  border-radius:24px;
  color:white;
  background:rgba(255,255,255,.18);
  border:1px solid rgba(255,255,255,.25);
  box-shadow:0 22px 60px rgba(0,0,0,.22);
  backdrop-filter:blur(24px) saturate(160%);
}

.upk-float strong{
  display:block;
  font-size:1.8rem;
  line-height:1;
}

.upk-float span{
  display:block;
  margin-top:5px;
  font-size:.88rem;
  font-weight:750;
  opacity:.9;
}

.card-a{
  left:-58px;
  top:18%;
}

.card-b{
  right:-46px;
  bottom:18%;
}

.upk-section{
  padding:110px max(24px,calc((100vw - 1180px)/2));
}

.upk-light{
  background:
    radial-gradient(circle at 10% 8%,rgba(22,119,255,.10),transparent 30%),
    radial-gradient(circle at 88% 18%,rgba(255,92,147,.12),transparent 28%),
    linear-gradient(180deg,#fbfcff 0%,#fff8ec 100%);
  text-align:center;
}

.upk h2{
  margin:0 auto 20px;
  max-width:850px;
  font-size:clamp(2.5rem,5.2vw,5.3rem);
  line-height:.92;
  letter-spacing:-.07em;
  font-weight:950;
}

.upk-grid{
  margin-top:52px;
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:20px;
  text-align:left;
}

.upk-grid article{
  position:relative;
  min-height:230px;
  padding:28px;
  border-radius:34px;
  background:rgba(255,255,255,.76);
  border:1px solid rgba(16,32,51,.08);
  box-shadow:0 24px 80px rgba(16,32,51,.08);
  backdrop-filter:blur(22px);
}

.upk-grid article:hover{
  transform:translateY(-4px);
  transition:.22s ease;
}

.upk-grid span{
  display:grid;
  place-items:center;
  width:62px;
  height:62px;
  border-radius:22px;
  font-size:1.85rem;
  background:linear-gradient(135deg,#e8f1ff,#e5fff1);
  box-shadow:inset 0 1px 0 rgba(255,255,255,.9);
}

.upk-grid h3{
  margin:22px 0 9px;
  font-size:1.25rem;
  letter-spacing:-.02em;
}

.upk-grid p{
  margin:0;
  color:var(--muted);
  line-height:1.55;
}

.upk-privacy{
  padding:120px max(24px,calc((100vw - 1180px)/2));
  background:
    radial-gradient(circle at 82% 18%,rgba(255,255,255,.22),transparent 28%),
    linear-gradient(135deg,#07111f 0%,#113f5f 44%,#168f72 100%);
  color:white;
}

.upk-privacy div{
  max-width:820px;
}

.upk-privacy p{
  max-width:660px;
  color:rgba(255,255,255,.84);
  font-size:1.2rem;
  line-height:1.65;
}

.upk-privacy a{
  color:white;
  font-weight:900;
  text-decoration:none;
  font-size:1.05rem;
}

.upk-final{
  min-height:62vh;
  display:grid;
  place-items:center;
  text-align:center;
  padding:90px 24px;
  color:white;
  background:
    radial-gradient(circle at 22% 20%,rgba(255,255,255,.28),transparent 25%),
    radial-gradient(circle at 78% 25%,rgba(255,255,255,.20),transparent 22%),
    linear-gradient(135deg,#ff9f1c 0%,#ff5c93 45%,#1677ff 100%);
}

.upk-final h2{
  color:white;
}

.upk-final p{
  margin:0 0 30px;
  font-size:1.22rem;
  color:rgba(255,255,255,.88);
}

.upk-final small{
  display:block;
  margin-top:34px;
  opacity:.82;
}

@media(max-width:980px){
  .upk-hero{
    grid-template-columns:1fr;
    text-align:center;
    gap:42px;
    padding:104px 24px 70px;
  }

  .upk-pill,
  .upk-trust,
  .upk-actions{
    margin-left:auto;
    margin-right:auto;
    justify-content:center;
  }

  .upk-sub{
    margin-left:auto;
    margin-right:auto;
  }

  .upk-visual{
    width:min(360px,86vw);
  }

  .card-a{
    left:-18px;
    top:12%;
  }

  .card-b{
    right:-18px;
    bottom:12%;
  }

  .upk-grid{
    grid-template-columns:1fr;
  }
}

@media(max-width:560px){
  .upk-nav{
    top:12px;
    width:calc(100% - 24px);
  }

  .upk-nav-link{
    padding:9px 13px;
  }

  .upk-hero{
    min-height:auto;
    padding:96px 18px 58px;
  }

  .upk h1{
    font-size:clamp(3.4rem,17vw,5.4rem);
  }

  .upk-sub{
    font-size:1.02rem;
  }

  .upk-store img{
    height:48px;
  }

  .upk-trust{
    gap:8px;
  }

  .upk-trust span{
    font-size:.86rem;
    padding:9px 12px;
  }

  .upk-visual{
    width:min(310px,88vw);
  }

  .upk-phone-wrap{
    border-radius:44px;
    padding:9px;
  }

  .upk-phone{
    border-radius:35px;
  }

  .upk-float{
    display:none;
  }

  .upk-section,
  .upk-privacy{
    padding:76px 18px;
  }

  .upk-grid article{
    min-height:auto;
    padding:24px;
    border-radius:28px;
  }

  .upk-final{
    min-height:auto;
    padding:80px 18px;
  }
}
</style>

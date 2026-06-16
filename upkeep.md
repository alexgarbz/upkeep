.upk-hero{
  position:relative;
  min-height:100vh;
  display:grid;
  grid-template-columns:minmax(0,1fr) minmax(320px,520px);
  align-items:center;
  gap:clamp(56px,7vw,110px);
  padding:132px max(28px,calc((100vw - 1280px)/2)) 86px;
  background:
    radial-gradient(circle at 18% 18%,rgba(255,255,255,.22),transparent 24%),
    radial-gradient(circle at 82% 14%,rgba(255,214,102,.35),transparent 28%),
    linear-gradient(135deg,#07111f 0%,#12395a 42%,#168f72 100%);
}

.upk h1{
  max-width:780px;
  margin:0;
  color:white;
  font-size:clamp(3.8rem,7.4vw,7.2rem);
  line-height:.96;
  letter-spacing:-.065em;
  font-weight:900;
}

.upk h1 span{
  display:block;
  margin-top:10px;
  background:linear-gradient(90deg,#fff7bf,#ffbf69,#ffffff);
  -webkit-background-clip:text;
  background-clip:text;
  color:transparent;
}

.upk-sub{
  max-width:620px;
  margin:34px 0 34px;
  color:rgba(255,255,255,.82);
  font-size:clamp(1.08rem,1.55vw,1.28rem);
  line-height:1.75;
}

.upk-pill{
  margin-bottom:28px;
}

.upk-actions{
  margin-top:4px;
}

.upk-trust{
  margin-top:30px;
}

@media(max-width:980px){
  .upk-hero{
    grid-template-columns:1fr;
    text-align:center;
    gap:58px;
    padding:118px 24px 72px;
  }

  .upk h1{
    margin:auto;
    line-height:1;
  }
}

@media(max-width:560px){
  .upk-hero{
    padding:108px 20px 64px;
  }

  .upk h1{
    font-size:clamp(3rem,14.5vw,4.7rem);
    letter-spacing:-.055em;
  }

  .upk-sub{
    margin-top:28px;
    font-size:1.03rem;
    line-height:1.65;
  }
}

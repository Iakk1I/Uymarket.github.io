<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>UY Market CRM — Платформа для застройщиков и риэлторов</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@300;400;500;600;700;800&family=Syne:wght@400;700;800&display=swap" rel="stylesheet">
<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{
  --c1:#0A0F1E;
  --c2:#0F1830;
  --c3:#162040;
  --accent:#2563FF;
  --accent2:#00C98D;
  --accent3:#FF6B35;
  --gold:#F4B942;
  --text:#F0F4FF;
  --muted:#6B7FA3;
  --border:rgba(255,255,255,0.07);
  --glass:rgba(255,255,255,0.03);
}
html{scroll-behavior:smooth;font-size:16px}
body{font-family:'Manrope',sans-serif;background:var(--c1);color:var(--text);overflow-x:hidden;line-height:1.65}

/* CURSOR GLOW */
#cursor-glow{pointer-events:none;position:fixed;width:400px;height:400px;border-radius:50%;background:radial-gradient(circle,rgba(37,99,255,0.08) 0%,transparent 70%);transform:translate(-50%,-50%);z-index:0;transition:transform .1s linear}

/* TOPBAR */
.topbar{background:linear-gradient(90deg,var(--accent),var(--accent2));padding:.55rem 0;text-align:center;font-size:.78rem;font-weight:600;letter-spacing:.03em;color:#fff}
.topbar span{opacity:.7;margin:0 .5rem}

/* NAV */
nav{position:sticky;top:0;z-index:200;padding:0 6%;height:68px;display:flex;align-items:center;justify-content:space-between;background:rgba(10,15,30,0.9);backdrop-filter:blur(24px);border-bottom:1px solid var(--border)}
.logo{display:flex;align-items:center;gap:10px;text-decoration:none}
.logo-svg{display:block}
.logo-name{font-family:'Syne',sans-serif;font-size:1.15rem;font-weight:800;color:#fff;letter-spacing:-.01em}
.logo-name small{color:var(--accent2);font-size:.65rem;display:block;font-family:'Manrope',sans-serif;font-weight:500;letter-spacing:.1em;text-transform:uppercase;margin-top:-2px}
.nav-menu{display:flex;gap:2rem;list-style:none}
.nav-menu a{color:var(--muted);font-size:.88rem;font-weight:500;text-decoration:none;transition:color .2s}
.nav-menu a:hover{color:#fff}
.nav-right{display:flex;gap:.75rem;align-items:center}
.btn-ghost{background:transparent;border:1px solid var(--border);color:var(--muted);padding:.5rem 1.2rem;border-radius:8px;font-family:'Manrope',sans-serif;font-size:.85rem;cursor:pointer;transition:all .2s}
.btn-ghost:hover{color:#fff;border-color:rgba(255,255,255,0.2)}
.btn-nav{background:var(--accent);color:#fff;padding:.5rem 1.3rem;border-radius:8px;font-family:'Manrope',sans-serif;font-size:.85rem;font-weight:600;border:none;cursor:pointer;transition:all .25s;position:relative;overflow:hidden}
.btn-nav::after{content:'';position:absolute;inset:0;background:linear-gradient(135deg,rgba(255,255,255,.15),transparent);opacity:0;transition:.3s}
.btn-nav:hover{transform:translateY(-1px);box-shadow:0 8px 25px rgba(37,99,255,.4)}
.btn-nav:hover::after{opacity:1}

/* === HERO === */
.hero{min-height:100vh;display:grid;grid-template-columns:1fr 1fr;align-items:center;gap:4rem;padding:100px 6% 60px;position:relative;overflow:hidden}
.hero-bg{position:absolute;inset:0;z-index:0}
.hero-bg canvas{position:absolute;inset:0;width:100%;height:100%}
.hero-orb1{position:absolute;top:-20%;right:-10%;width:700px;height:700px;background:radial-gradient(circle,rgba(37,99,255,.12) 0%,transparent 65%);border-radius:50%}
.hero-orb2{position:absolute;bottom:-20%;left:-5%;width:500px;height:500px;background:radial-gradient(circle,rgba(0,201,141,.08) 0%,transparent 65%);border-radius:50%}
.hero-grid-lines{position:absolute;inset:0;background-image:linear-gradient(rgba(37,99,255,.04) 1px,transparent 1px),linear-gradient(90deg,rgba(37,99,255,.04) 1px,transparent 1px);background-size:80px 80px;mask-image:radial-gradient(ellipse 90% 90% at 60% 40%,black 20%,transparent 100%)}
.hero-left{position:relative;z-index:1}
.hero-chip{display:inline-flex;align-items:center;gap:.5rem;padding:.35rem .9rem;border-radius:50px;border:1px solid rgba(37,99,255,.35);background:rgba(37,99,255,.08);font-size:.73rem;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:var(--accent2);margin-bottom:2rem}
.hero-chip i{width:6px;height:6px;background:var(--accent2);border-radius:50%;display:inline-block;animation:blink 2s ease infinite}
@keyframes blink{0%,100%{opacity:1}50%{opacity:.2}}
h1{font-family:'Syne',sans-serif;font-size:clamp(2.4rem,4.5vw,4rem);font-weight:800;line-height:1.08;letter-spacing:-.03em;margin-bottom:1.5rem}
h1 em{font-style:normal;position:relative;display:inline;color:#fff;white-space:nowrap}
h1 em::after{content:'';position:absolute;left:-.1em;right:-.1em;bottom:.05em;height:.32em;background:linear-gradient(90deg,var(--accent),var(--accent2));z-index:-1;border-radius:4px;opacity:.55}
@keyframes flow{to{background-position:200% center}}
.hero-desc{color:var(--muted);font-size:1.05rem;max-width:480px;margin-bottom:2.5rem;line-height:1.7}
.hero-actions{display:flex;gap:1rem;flex-wrap:wrap;margin-bottom:3rem}
.btn-hero{padding:.9rem 2rem;border-radius:10px;font-family:'Manrope',sans-serif;font-size:.95rem;font-weight:700;cursor:pointer;transition:all .3s;border:none;display:flex;align-items:center;gap:.5rem}
.btn-hero.primary{background:linear-gradient(135deg,var(--accent),#1a4fd8);color:#fff;box-shadow:0 0 0 0 rgba(37,99,255,.4)}
.btn-hero.primary:hover{transform:translateY(-2px);box-shadow:0 12px 30px rgba(37,99,255,.4)}
.btn-hero.secondary{background:var(--glass);border:1px solid var(--border);color:var(--text)}
.btn-hero.secondary:hover{background:rgba(255,255,255,.06);border-color:rgba(255,255,255,.15)}
.hero-trust{display:flex;align-items:center;gap:1rem;font-size:.82rem;color:var(--muted)}
.hero-avatars{display:flex}
.hero-avatars span{width:32px;height:32px;border-radius:50%;border:2px solid var(--c1);display:flex;align-items:center;justify-content:center;font-size:.7rem;font-weight:700;color:#fff;margin-left:-8px}
.hero-avatars span:first-child{margin-left:0}

/* HERO RIGHT - LIVE DASHBOARD */
.hero-right{position:relative;z-index:1}
.dashboard-card{background:rgba(15,24,48,.85);border:1px solid var(--border);border-radius:20px;padding:1.5rem;backdrop-filter:blur(20px);box-shadow:0 30px 80px rgba(0,0,0,.5);animation:floatDash 6s ease-in-out infinite}
@keyframes floatDash{0%,100%{transform:translateY(0) rotate(0deg)}50%{transform:translateY(-8px) rotate(.3deg)}}
.dash-header{display:flex;justify-content:space-between;align-items:center;margin-bottom:1.25rem}
.dash-title{font-size:.82rem;font-weight:700;color:var(--muted);text-transform:uppercase;letter-spacing:.07em}
.dash-live{display:flex;align-items:center;gap:.4rem;font-size:.72rem;color:var(--accent2);font-weight:600}
.dash-live::before{content:'';width:6px;height:6px;background:var(--accent2);border-radius:50%;animation:blink 1.5s ease infinite}
.kpi-row{display:grid;grid-template-columns:repeat(3,1fr);gap:.75rem;margin-bottom:1.25rem}
.kpi{background:rgba(255,255,255,.03);border:1px solid var(--border);border-radius:12px;padding:.85rem;text-align:center}
.kpi-val{font-family:'Syne',sans-serif;font-size:1.3rem;font-weight:700;color:#fff;display:block}
.kpi-val.green{color:var(--accent2)}
.kpi-val.blue{color:#60A5FA}
.kpi-lbl{font-size:.68rem;color:var(--muted);margin-top:.15rem;display:block}
.mini-chart{margin-bottom:1.25rem}
.chart-label{font-size:.72rem;color:var(--muted);margin-bottom:.6rem;display:flex;justify-content:space-between}
.bars{display:flex;gap:5px;align-items:flex-end;height:60px}
.bar{flex:1;border-radius:4px 4px 0 0;background:rgba(37,99,255,.25);transition:all .3s;position:relative;cursor:pointer}
.bar.active,.bar:hover{background:var(--accent)}
.bar .tip{position:absolute;top:-22px;left:50%;transform:translateX(-50%);font-size:.65rem;color:#fff;white-space:nowrap;opacity:0;transition:.2s}
.bar:hover .tip{opacity:1}
.deals-list{display:flex;flex-direction:column;gap:.5rem}
.deal-row{display:flex;align-items:center;gap:.75rem;padding:.5rem .6rem;border-radius:8px;background:rgba(255,255,255,.02);border:1px solid transparent;transition:.2s;cursor:pointer}
.deal-row:hover{background:rgba(255,255,255,.05);border-color:var(--border)}
.deal-dot{width:8px;height:8px;border-radius:50%;flex-shrink:0}
.deal-name{font-size:.82rem;font-weight:600;flex:1}
.deal-stage{font-size:.7rem;color:var(--muted)}
.deal-amount{font-size:.8rem;font-weight:700;font-family:'Syne',sans-serif}
.notification{position:absolute;bottom:-16px;right:20px;background:linear-gradient(135deg,var(--c3),rgba(37,99,255,.2));border:1px solid rgba(37,99,255,.3);border-radius:12px;padding:.65rem 1rem;display:flex;align-items:center;gap:.6rem;font-size:.78rem;backdrop-filter:blur(12px);animation:slideUp .5s 1s both}
@keyframes slideUp{from{opacity:0;transform:translateY(10px)}to{opacity:1;transform:translateY(0)}}
.notif-icon{width:28px;height:28px;background:rgba(0,201,141,.15);border-radius:8px;display:flex;align-items:center;justify-content:center;color:var(--accent2);font-size:.9rem;flex-shrink:0}

/* METRICS STRIP */
.metrics{padding:1.5rem 6%;background:var(--c2);border-top:1px solid var(--border);border-bottom:1px solid var(--border);display:flex;justify-content:space-around;flex-wrap:wrap;gap:1rem}
.metric{text-align:center;padding:.5rem 1rem}
.metric-num{font-family:'Syne',sans-serif;font-size:2rem;font-weight:800;color:#fff;display:block;line-height:1}
.metric-num b{color:var(--accent2)}
.metric-lbl{font-size:.75rem;color:var(--muted);text-transform:uppercase;letter-spacing:.06em;margin-top:.3rem}
.metric-delta{font-size:.72rem;color:var(--accent2);font-weight:600;margin-top:.15rem}

/* SECTION COMMONS */
section{padding:6rem 6%}
.s-tag{font-size:.72rem;font-weight:700;letter-spacing:.12em;text-transform:uppercase;color:var(--accent2);margin-bottom:.75rem;display:block}
.s-title{font-family:'Syne',sans-serif;font-size:clamp(1.7rem,3vw,2.8rem);font-weight:800;line-height:1.12;letter-spacing:-.025em;margin-bottom:1rem}
.s-sub{color:var(--muted);font-size:.98rem;max-width:540px;line-height:1.7}
.center{text-align:center}
.center .s-sub{margin:0 auto 3rem}

/* FEATURES BENTO */
.bento{display:grid;grid-template-columns:repeat(3,1fr);grid-template-rows:auto auto;gap:1.25rem;margin-top:3.5rem}
.bento-card{background:var(--glass);border:1px solid var(--border);border-radius:18px;padding:2rem;position:relative;overflow:hidden;transition:all .35s;cursor:default}
.bento-card::after{content:'';position:absolute;inset:0;opacity:0;transition:.35s;border-radius:18px}
.bento-card:hover{transform:translateY(-4px)}
.bento-card:hover::after{opacity:1}
.bento-card.accent1:hover{border-color:rgba(37,99,255,.4);box-shadow:0 20px 50px rgba(37,99,255,.15)}
.bento-card.accent1::after{background:radial-gradient(circle at 30% 50%,rgba(37,99,255,.07),transparent 70%)}
.bento-card.accent2:hover{border-color:rgba(0,201,141,.3);box-shadow:0 20px 50px rgba(0,201,141,.1)}
.bento-card.accent2::after{background:radial-gradient(circle at 70% 50%,rgba(0,201,141,.05),transparent 70%)}
.bento-card.accent3:hover{border-color:rgba(255,107,53,.3);box-shadow:0 20px 50px rgba(255,107,53,.1)}
.bento-card.accent3::after{background:radial-gradient(circle at 50% 70%,rgba(255,107,53,.05),transparent 70%)}
.bento-card.wide{grid-column:span 2}
.bento-card.tall{grid-row:span 2}
.bento-icon{width:44px;height:44px;border-radius:12px;display:flex;align-items:center;justify-content:center;margin-bottom:1.25rem;font-size:1.2rem}
.ic-blue{background:rgba(37,99,255,.15);color:#60A5FA}
.ic-green{background:rgba(0,201,141,.15);color:var(--accent2)}
.ic-orange{background:rgba(255,107,53,.15);color:var(--accent3)}
.ic-gold{background:rgba(244,185,66,.15);color:var(--gold)}
.ic-purple{background:rgba(167,139,250,.15);color:#A78BFA}
.bento-card h3{font-family:'Syne',sans-serif;font-size:1.05rem;font-weight:700;margin-bottom:.6rem;line-height:1.3}
.bento-card p{font-size:.87rem;color:var(--muted);line-height:1.65}
.bento-badge{display:inline-block;margin-top:1rem;font-size:.7rem;font-weight:700;padding:.3rem .8rem;border-radius:20px;letter-spacing:.04em;text-transform:uppercase}
.bb-blue{background:rgba(37,99,255,.12);color:#60A5FA;border:1px solid rgba(37,99,255,.2)}
.bb-green{background:rgba(0,201,141,.12);color:var(--accent2);border:1px solid rgba(0,201,141,.2)}
.bb-orange{background:rgba(255,107,53,.12);color:var(--accent3);border:1px solid rgba(255,107,53,.2)}

/* CHESS BOARD SECTION */
.chess-section{background:var(--c2)}
.chess-wrap{display:grid;grid-template-columns:1fr 1.1fr;gap:4rem;align-items:start}
.chess-info{padding-top:1rem}
.chess-legend{display:flex;flex-wrap:wrap;gap:.6rem;margin:2rem 0}
.leg-item{display:flex;align-items:center;gap:.4rem;font-size:.78rem;color:var(--muted)}
.leg-dot{width:12px;height:12px;border-radius:3px;flex-shrink:0}
.chess-stats{display:grid;grid-template-columns:1fr 1fr;gap:.75rem;margin-top:1.5rem}
.cs-box{background:var(--glass);border:1px solid var(--border);border-radius:12px;padding:1rem}
.cs-num{font-family:'Syne',sans-serif;font-size:1.5rem;font-weight:700;display:block}
.cs-lbl{font-size:.75rem;color:var(--muted);margin-top:.15rem}
.chess-board{background:var(--glass);border:1px solid var(--border);border-radius:18px;padding:1.25rem}
.board-header{display:flex;justify-content:space-between;align-items:center;margin-bottom:1rem}
.board-title{font-size:.8rem;font-weight:700;color:var(--muted);text-transform:uppercase;letter-spacing:.06em}
.floor-select{display:flex;gap:.4rem}
.floor-btn{padding:.3rem .7rem;border-radius:6px;font-size:.7rem;font-weight:600;border:1px solid var(--border);background:transparent;color:var(--muted);cursor:pointer;transition:.2s;font-family:'Manrope',sans-serif}
.floor-btn.active,.floor-btn:hover{background:var(--accent);border-color:var(--accent);color:#fff}
.apt-grid{display:grid;gap:4px}
.apt{border-radius:5px;display:flex;align-items:center;justify-content:center;font-size:.58rem;font-weight:700;cursor:pointer;transition:all .2s;position:relative;aspect-ratio:1.4}
.apt:hover{transform:scale(1.08);z-index:10}
.apt.free{background:rgba(0,201,141,.18);border:1px solid rgba(0,201,141,.35);color:var(--accent2)}
.apt.booked{background:rgba(244,185,66,.15);border:1px solid rgba(244,185,66,.35);color:var(--gold)}
.apt.sold{background:rgba(37,99,255,.15);border:1px solid rgba(37,99,255,.3);color:#60A5FA}
.apt.reserved{background:rgba(255,107,53,.15);border:1px solid rgba(255,107,53,.3);color:var(--accent3)}
.apt-tooltip{position:absolute;bottom:calc(100% + 6px);left:50%;transform:translateX(-50%);background:var(--c3);border:1px solid var(--border);border-radius:8px;padding:.5rem .75rem;font-size:.7rem;white-space:nowrap;pointer-events:none;opacity:0;transition:.2s;z-index:20;color:var(--text)}
.apt:hover .apt-tooltip{opacity:1}

/* ROI CALCULATOR */
.calc-section{}
.calc-wrap{display:grid;grid-template-columns:1fr 1fr;gap:4rem;align-items:center}
.calc-box{background:var(--c2);border:1px solid var(--border);border-radius:20px;padding:2.5rem}
.calc-row{margin-bottom:1.5rem}
.calc-row label{display:flex;justify-content:space-between;font-size:.82rem;color:var(--muted);margin-bottom:.6rem;font-weight:500}
.calc-row label span{color:#fff;font-weight:700;font-family:'Syne',sans-serif}
.range-wrap{position:relative}
input[type=range]{width:100%;-webkit-appearance:none;height:4px;border-radius:2px;background:rgba(255,255,255,.1);outline:none;cursor:pointer}
input[type=range]::-webkit-slider-thumb{-webkit-appearance:none;width:18px;height:18px;border-radius:50%;background:var(--accent);cursor:pointer;border:2px solid var(--c1);box-shadow:0 0 0 3px rgba(37,99,255,.25);transition:.2s}
input[type=range]:hover::-webkit-slider-thumb{box-shadow:0 0 0 5px rgba(37,99,255,.2)}
.calc-divider{height:1px;background:var(--border);margin:1.5rem 0}
.result-block{background:linear-gradient(135deg,rgba(37,99,255,.15),rgba(0,201,141,.08));border:1px solid rgba(37,99,255,.25);border-radius:14px;padding:1.5rem;text-align:center}
.result-label{font-size:.8rem;color:var(--muted);text-transform:uppercase;letter-spacing:.07em;margin-bottom:.5rem}
.result-big{font-family:'Syne',sans-serif;font-size:2.6rem;font-weight:800;color:#fff;line-height:1}
.result-big b{color:var(--accent2)}
.result-sub{font-size:.8rem;color:var(--muted);margin-top:.4rem}
.result-row{display:flex;justify-content:space-between;margin-top:.75rem;padding-top:.75rem;border-top:1px solid var(--border)}
.rr-item{text-align:center}
.rr-val{font-family:'Syne',sans-serif;font-size:1rem;font-weight:700;color:#fff}
.rr-lbl{font-size:.7rem;color:var(--muted);margin-top:.1rem}
.calc-right{}
.benefit-list{margin-top:2rem;display:flex;flex-direction:column;gap:1rem}
.benefit{display:flex;gap:1rem;align-items:flex-start}
.benefit-icon{width:40px;height:40px;border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:1rem;flex-shrink:0}
.benefit h4{font-size:.92rem;font-weight:700;margin-bottom:.25rem}
.benefit p{font-size:.82rem;color:var(--muted);line-height:1.5}

/* TIMELINE */
.timeline-section{background:var(--c2)}
.timeline{position:relative;margin-top:3rem;max-width:800px;margin-left:auto;margin-right:auto}
.timeline::before{content:'';position:absolute;left:50%;top:0;bottom:0;width:1px;background:linear-gradient(to bottom,transparent,var(--border),var(--border),transparent);transform:translateX(-50%)}
.tl-item{display:grid;grid-template-columns:1fr 40px 1fr;gap:1rem;align-items:center;margin-bottom:2.5rem}
.tl-item:last-child{margin-bottom:0}
.tl-left{text-align:right}
.tl-right{text-align:left}
.tl-dot{width:40px;height:40px;border-radius:50%;background:var(--c3);border:2px solid var(--accent);display:flex;align-items:center;justify-content:center;font-family:'Syne',sans-serif;font-size:.85rem;font-weight:700;color:var(--accent);z-index:1;position:relative;margin:0 auto}
.tl-card{background:var(--glass);border:1px solid var(--border);border-radius:14px;padding:1.25rem;transition:.3s}
.tl-card:hover{border-color:rgba(37,99,255,.3);background:rgba(37,99,255,.04)}
.tl-card h4{font-size:.92rem;font-weight:700;margin-bottom:.3rem}
.tl-card p{font-size:.8rem;color:var(--muted);line-height:1.5}

/* TESTIMONIALS */
.testi-wrap{margin-top:3rem;display:grid;grid-template-columns:repeat(3,1fr);gap:1.25rem}
.tcard{background:var(--glass);border:1px solid var(--border);border-radius:18px;padding:1.75rem;transition:.3s;position:relative}
.tcard:hover{transform:translateY(-4px);border-color:rgba(37,99,255,.25)}
.tcard-stars{color:var(--gold);font-size:.9rem;margin-bottom:1rem;letter-spacing:.1em}
.tcard-text{font-size:.88rem;color:var(--muted);line-height:1.7;margin-bottom:1.5rem;font-style:italic}
.tcard-text::before{content:'\201C';font-size:2rem;color:var(--accent);line-height:0;vertical-align:-.4em;margin-right:.2rem}
.tcard-author{display:flex;align-items:center;gap:.75rem}
.tcard-av{width:38px;height:38px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:.78rem;font-weight:700;color:#fff;flex-shrink:0}
.tcard-name{font-size:.88rem;font-weight:700}
.tcard-role{font-size:.73rem;color:var(--muted)}
.tcard-result{position:absolute;top:1rem;right:1rem;background:rgba(0,201,141,.12);border:1px solid rgba(0,201,141,.2);border-radius:20px;padding:.25rem .7rem;font-size:.68rem;font-weight:700;color:var(--accent2)}

/* PRICING */
.pricing-section{}
.price-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1.25rem;margin-top:3.5rem}
.pcard{background:var(--glass);border:1px solid var(--border);border-radius:20px;padding:2.25rem;position:relative;transition:.35s}
.pcard:hover{transform:translateY(-4px)}
.pcard.star{background:linear-gradient(160deg,rgba(37,99,255,.12),rgba(0,201,141,.06));border-color:rgba(37,99,255,.35)}
.pcard.star:hover{box-shadow:0 25px 60px rgba(37,99,255,.2)}
.pbadge{position:absolute;top:-14px;left:50%;transform:translateX(-50%);background:linear-gradient(90deg,var(--accent),var(--accent2));color:#fff;font-size:.68rem;font-weight:700;padding:.3rem 1rem;border-radius:20px;text-transform:uppercase;letter-spacing:.06em;white-space:nowrap}
.pname{font-size:.75rem;font-weight:700;letter-spacing:.1em;text-transform:uppercase;color:var(--muted);margin-bottom:1rem}
.pprice{font-family:'Syne',sans-serif;font-size:2.8rem;font-weight:800;color:#fff;line-height:1}
.pprice sup{font-size:1.2rem;vertical-align:super;color:var(--muted)}
.pperiod{font-size:.78rem;color:var(--muted);margin:.5rem 0 1.75rem}
.pfeats{list-style:none;margin-bottom:2rem;display:flex;flex-direction:column;gap:.65rem}
.pfeats li{font-size:.85rem;color:var(--muted);display:flex;align-items:flex-start;gap:.5rem;line-height:1.4}
.pfeats li::before{content:'✓';color:var(--accent2);font-weight:700;flex-shrink:0;margin-top:.05rem}
.pfeats li.dim{opacity:.45}
.pfeats li.dim::before{content:'—';color:var(--muted)}
.pbtn{width:100%;padding:.85rem;border-radius:10px;font-family:'Manrope',sans-serif;font-size:.9rem;font-weight:700;cursor:pointer;transition:.3s}
.pbtn.outline{background:transparent;border:1px solid var(--border);color:var(--text)}
.pbtn.outline:hover{background:rgba(255,255,255,.06);border-color:rgba(255,255,255,.2)}
.pbtn.filled{background:var(--accent);border:none;color:#fff}
.pbtn.filled:hover{background:#1a4fd8;box-shadow:0 8px 25px rgba(37,99,255,.4)}

/* CTA */
.cta-band{margin:0 6% 6rem;border-radius:24px;overflow:hidden;position:relative;padding:5rem 4rem;text-align:center}
.cta-band::before{content:'';position:absolute;inset:0;background:linear-gradient(135deg,var(--c3),rgba(37,99,255,.25),rgba(0,201,141,.15));z-index:0}
.cta-band::after{content:'';position:absolute;inset:0;background-image:radial-gradient(rgba(37,99,255,.15) 1px,transparent 1px);background-size:30px 30px;z-index:0}
.cta-inner{position:relative;z-index:1}
.cta-band h2{font-family:'Syne',sans-serif;font-size:clamp(1.8rem,3.5vw,3rem);font-weight:800;letter-spacing:-.02em;margin-bottom:1rem}
.cta-band p{color:var(--muted);margin-bottom:2.5rem;font-size:1rem}
.cta-btns{display:flex;gap:1rem;justify-content:center;flex-wrap:wrap}
.form-inline{display:flex;gap:.75rem;justify-content:center;flex-wrap:wrap;max-width:500px;margin:0 auto 1rem}
.form-inline input{flex:1;min-width:220px;padding:.85rem 1.2rem;border-radius:10px;border:1px solid rgba(255,255,255,.15);background:rgba(255,255,255,.07);color:#fff;font-family:'Manrope',sans-serif;font-size:.9rem;outline:none;backdrop-filter:blur(10px)}
.form-inline input::placeholder{color:rgba(255,255,255,.35)}
.form-inline input:focus{border-color:var(--accent)}
.cta-note{font-size:.75rem;color:rgba(255,255,255,.4)}

/* FOOTER */
footer{border-top:1px solid var(--border);padding:3rem 6% 2rem}
.footer-top{display:grid;grid-template-columns:2fr 1fr 1fr 1fr;gap:3rem;margin-bottom:3rem}
.footer-brand p{font-size:.85rem;color:var(--muted);margin-top:.75rem;line-height:1.65;max-width:260px}
.footer-socials{display:flex;gap:.6rem;margin-top:1.25rem}
.fsoc{width:34px;height:34px;border-radius:8px;border:1px solid var(--border);display:flex;align-items:center;justify-content:center;color:var(--muted);font-size:.85rem;cursor:pointer;transition:.2s;text-decoration:none}
.fsoc:hover{border-color:rgba(255,255,255,.2);color:#fff}
.footer-col h5{font-size:.78rem;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:var(--muted);margin-bottom:1rem}
.footer-col ul{list-style:none;display:flex;flex-direction:column;gap:.55rem}
.footer-col ul a{font-size:.85rem;color:var(--muted);text-decoration:none;transition:.2s}
.footer-col ul a:hover{color:#fff}
.footer-bottom{display:flex;justify-content:space-between;align-items:center;padding-top:1.5rem;border-top:1px solid var(--border);font-size:.8rem;color:var(--muted)}

/* ANIMATIONS */
.reveal{opacity:0;transform:translateY(28px);transition:opacity .65s ease,transform .65s ease}
.reveal.in{opacity:1;transform:none}
.reveal-delay-1{transition-delay:.1s}
.reveal-delay-2{transition-delay:.2s}
.reveal-delay-3{transition-delay:.3s}

/* RESPONSIVE */
@media(max-width:900px){
  .hero{grid-template-columns:1fr;padding-top:90px}
  .hero-right{display:none}
  .chess-wrap,.calc-wrap{grid-template-columns:1fr}
  .bento{grid-template-columns:1fr 1fr}
  .bento-card.wide{grid-column:span 1}
  .testi-wrap,.price-grid{grid-template-columns:1fr}
  .footer-top{grid-template-columns:1fr 1fr}
  .nav-menu{display:none}
  .timeline::before{left:20px}
  .tl-item{grid-template-columns:30px 1fr}
  .tl-left{display:none}
}
@media(max-width:600px){
  .bento{grid-template-columns:1fr}
  .cta-band{margin:0 1rem 3rem;padding:3rem 1.5rem}
  .kpi-row{grid-template-columns:1fr 1fr}
}
</style>
</head>
<body>

<div id="cursor-glow"></div>

<!-- TOPBAR -->
<div class="topbar">🎁 Специальное предложение: первые 3 месяца со скидкой 40% — для застройщиков и риэлторов<span>|</span>Подключить сейчас →</div>

<!-- NAV -->
<nav>
  <a class="logo" href="#">
    <svg class="logo-svg" width="38" height="38" viewBox="0 0 60 60" fill="none">
      <path d="M6 32L30 10L54 32" stroke="#2563FF" stroke-width="7" stroke-linecap="round" stroke-linejoin="round"/>
      <rect x="8" y="37" width="14" height="14" rx="3" fill="#00C98D"/>
      <rect x="24" y="37" width="14" height="14" rx="3" fill="#00C98D"/>
      <rect x="16" y="52" width="14" height="7" rx="2" fill="#00C98D"/>
    </svg>
    <div class="logo-name">UY MARKET<small>для застройщиков и риэлторов</small></div>
  </a>
  <ul class="nav-menu">
    <li><a href="#features">Функции</a></li>
    <li><a href="#shakhmtka">Шахматка</a></li>
    <li><a href="#roi">Калькулятор ROI</a></li>
    <li><a href="#pricing">Тарифы</a></li>
  </ul>
  <div class="nav-right">
    <button class="btn-ghost">Войти</button>
    <button class="btn-nav">Начать бесплатно →</button>
  </div>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-bg">
    <div class="hero-orb1"></div>
    <div class="hero-orb2"></div>
    <div class="hero-grid-lines"></div>
  </div>
  <div class="hero-left">
    <div class="hero-chip"><i></i>CRM для застройщиков и риэлторов · Ташкент</div>
    <h1>CRM для <em>застройщиков</em><br>и <em>риэлторов</em>,<br>которая продаёт</h1>
    <p class="hero-desc">Шахматка квартир, воронка сделок, WhatsApp-интеграция и AI-аналитика в одном окне. Работает для девелоперов и агентств недвижимости.</p>
    <div class="hero-actions">
      <button class="btn-hero primary">Попробовать 14 дней бесплатно <span>→</span></button>
      <button class="btn-hero secondary">▶ Смотреть демо</button>
    </div>
    <div class="hero-trust">
      <div class="hero-avatars">
        <span style="background:linear-gradient(135deg,#2563FF,#1a4fd8)">АС</span>
        <span style="background:linear-gradient(135deg,#00C98D,#0a9e6e)">МЖ</span>
        <span style="background:linear-gradient(135deg,#FF6B35,#cc4f22)">НТ</span>
        <span style="background:linear-gradient(135deg,#A78BFA,#7c5cbf)">+</span>
      </div>
      <div><strong style="color:#fff">1 200+</strong> застройщиков и риэлторов используют UY Market</div>
    </div>
  </div>

  <!-- LIVE MINI-DASHBOARD -->
  <div class="hero-right">
    <div class="dashboard-card" style="position:relative">
      <div class="dash-header">
        <span class="dash-title">Дашборд продаж</span>
        <span class="dash-live">LIVE</span>
      </div>
      <div class="kpi-row">
        <div class="kpi"><span class="kpi-val green" id="kpi1">74</span><span class="kpi-lbl">Сделок / мес</span></div>
        <div class="kpi"><span class="kpi-val blue" id="kpi2">342</span><span class="kpi-lbl">Лидов</span></div>
        <div class="kpi"><span class="kpi-val" id="kpi3">22%</span><span class="kpi-lbl">Конверсия</span></div>
      </div>
      <div class="mini-chart">
        <div class="chart-label"><span>Продажи за месяц</span><span style="color:var(--accent2)">+18%</span></div>
        <div class="bars" id="bars">
          <div class="bar" style="height:38%"><div class="tip">Янв</div></div>
          <div class="bar" style="height:52%"><div class="tip">Фев</div></div>
          <div class="bar" style="height:45%"><div class="tip">Мар</div></div>
          <div class="bar" style="height:68%"><div class="tip">Апр</div></div>
          <div class="bar active" style="height:80%"><div class="tip">Май</div></div>
          <div class="bar" style="height:60%"><div class="tip">Июн</div></div>
          <div class="bar" style="height:72%"><div class="tip">Июл</div></div>
        </div>
      </div>
      <div class="deals-list">
        <div class="deal-row"><div class="deal-dot" style="background:var(--accent2)"></div><div><div class="deal-name">Asyl Tower 4А, 3-комн.</div><div class="deal-stage">Переговоры</div></div><div class="deal-amount" style="color:var(--accent2)">₸ 28.5М</div></div>
        <div class="deal-row"><div class="deal-dot" style="background:var(--gold)"></div><div><div class="deal-name">Green Park, студия</div><div class="deal-stage">Бронирование</div></div><div class="deal-amount" style="color:var(--gold)">₸ 12.1М</div></div>
        <div class="deal-row"><div class="deal-dot" style="background:#60A5FA"></div><div><div class="deal-name">Орион ЖК, 2-комн.</div><div class="deal-stage">Договор</div></div><div class="deal-amount" style="color:#60A5FA">₸ 19.8М</div></div>
      </div>
      <div class="notification">
        <div class="notif-icon">✓</div>
        <div><strong style="color:#fff">Новая сделка закрыта!</strong><br><span style="color:var(--muted);font-size:.7rem">Asyl Tower 4А · 2 мин назад</span></div>
      </div>
    </div>
  </div>
</section>

<!-- METRICS -->
<div class="metrics">
  <div class="metric"><span class="metric-num">1<b>,200+</b></span><div class="metric-lbl">Застройщиков и риэлторов</div><div class="metric-delta">↑ +340 за год</div></div>
  <div class="metric"><span class="metric-num"><b>₸</b>48 млрд</span><div class="metric-lbl">Сделок закрыто</div><div class="metric-delta">↑ +62% г/г</div></div>
  <div class="metric"><span class="metric-num">94<b>%</b></span><div class="metric-lbl">Довольных клиентов</div><div class="metric-delta">NPS 71</div></div>
  <div class="metric"><span class="metric-num">+<b>40%</b></span><div class="metric-lbl">Рост конверсии</div><div class="metric-delta">В среднем за 3 мес</div></div>
  <div class="metric"><span class="metric-num"><b>3</b> дня</span><div class="metric-lbl">До запуска</div><div class="metric-delta">Без IT-специалиста</div></div>
</div>

<!-- FEATURES BENTO -->
<section id="features">
  <div class="reveal center" style="margin-bottom:0">
    <span class="s-tag">Возможности платформы</span>
    <h2 class="s-title">Весь цикл продаж<br>в одной системе</h2>
    <p class="s-sub">От первого обращения до закрытия сделки — для застройщиков и риэлторских агентств.</p>
  </div>
  <div class="bento reveal">
    <div class="bento-card accent1 wide">
      <div class="bento-icon ic-blue">🏗️</div>
      <h3>Шахматка в реальном времени</h3>
      <p>Интерактивная карта всех квартир с мгновенным обновлением статусов. Никаких двойных броней — система блокирует квартиру в момент бронирования. Поддержка нескольких ЖК и очередей строительства.</p>
      <span class="bento-badge bb-blue">Живые данные</span>
    </div>
    <div class="bento-card accent2">
      <div class="bento-icon ic-green">📊</div>
      <h3>Воронка и Kanban</h3>
      <p>Визуальная доска сделок, автоматические напоминания и AI-скоринг лидов по вероятности покупки.</p>
      <span class="bento-badge bb-green">AI-скоринг</span>
    </div>
    <div class="bento-card accent3">
      <div class="bento-icon ic-orange">📞</div>
      <h3>Омниканал</h3>
      <p>WhatsApp, Telegram, Instagram, email, звонки — всё в одном окне. Ни одного пропущенного лида.</p>
      <span class="bento-badge bb-orange">WhatsApp + TG</span>
    </div>
    <div class="bento-card accent2">
      <div class="bento-icon ic-gold">📄</div>
      <h3>Электронные договоры</h3>
      <p>ДДУ, ипотечные пакеты, акты приёма-передачи — генерация за 2 минуты с подписью через ЭЦП.</p>
    </div>
    <div class="bento-card accent1">
      <div class="bento-icon ic-purple">🤖</div>
      <h3>AI-аналитика</h3>
      <p>Прогноз продаж, рекомендации по ценообразованию, автоматическое распределение лидов между менеджерами. Для риэлторов — подбор объектов под запрос клиента за секунды.</p>
      <span class="bento-badge bb-blue">GPT-powered</span>
    </div>
    <div class="bento-card accent3">
      <div class="bento-icon ic-orange">📈</div>
      <h3>Отчёты для руководителя</h3>
      <p>Ключевые показатели в реальном времени, экспорт в Excel и PDF, еженедельные сводки на email.</p>
    </div>
  </div>
</section>

<!-- SHAKHMTKA -->
<section id="shakhmtka" class="chess-section">
  <div class="chess-wrap">
    <div class="chess-info reveal">
      <span class="s-tag">Шахматка квартир</span>
      <h2 class="s-title">Вся шахматка<br>как на ладони</h2>
      <p class="s-sub">Кликните на квартиру чтобы увидеть детали. Переключайте этажи, фильтруйте по статусу.</p>
      <div class="chess-legend">
        <div class="leg-item"><div class="leg-dot" style="background:rgba(0,201,141,.5);border:1px solid var(--accent2)"></div>Свободна</div>
        <div class="leg-item"><div class="leg-dot" style="background:rgba(244,185,66,.4);border:1px solid var(--gold)"></div>Забронирована</div>
        <div class="leg-item"><div class="leg-dot" style="background:rgba(37,99,255,.4);border:1px solid var(--accent)"></div>Продана</div>
        <div class="leg-item"><div class="leg-dot" style="background:rgba(255,107,53,.4);border:1px solid var(--accent3)"></div>Резерв</div>
      </div>
      <div class="chess-stats">
        <div class="cs-box"><span class="cs-num" style="color:var(--accent2)">48</span><span class="cs-lbl">Свободных</span></div>
        <div class="cs-box"><span class="cs-num" style="color:var(--gold)">12</span><span class="cs-lbl">Забронировано</span></div>
        <div class="cs-box"><span class="cs-num" style="color:#60A5FA">29</span><span class="cs-lbl">Продано</span></div>
        <div class="cs-box"><span class="cs-num" style="color:var(--accent3)">5</span><span class="cs-lbl">В резерве</span></div>
      </div>
    </div>
    <div class="chess-board reveal reveal-delay-2">
      <div class="board-header">
        <span class="board-title">ЖК «Asyl Tower» · Корпус 1</span>
        <div class="floor-select" id="floorSel">
          <button class="floor-btn active" data-f="1">1-5</button>
          <button class="floor-btn" data-f="2">6-10</button>
          <button class="floor-btn" data-f="3">11-16</button>
        </div>
      </div>
      <div class="apt-grid" id="aptGrid" style="grid-template-columns:repeat(8,1fr)"></div>
    </div>
  </div>
</section>

<!-- ROI CALCULATOR -->
<section id="roi">
  <div class="calc-wrap">
    <div class="reveal">
      <span class="s-tag">Калькулятор ROI</span>
      <h2 class="s-title">Посчитайте<br>свою выгоду</h2>
      <p class="s-sub">Узнайте сколько дополнительной выручки принесёт UY Market CRM именно вашей компании.</p>
      <div class="benefit-list">
        <div class="benefit">
          <div class="benefit-icon ic-green">📈</div>
          <div><h4>Рост конверсии лидов</h4><p>Средний менеджер закрывает на 40% больше сделок благодаря AI-напоминаниям и скорингу.</p></div>
        </div>
        <div class="benefit">
          <div class="benefit-icon ic-blue">⚡</div>
          <div><h4>Скорость обработки</h4><p>Время ответа на лид снижается с 4 часов до 7 минут — конверсия горячих лидов вырастает x3.</p></div>
        </div>
        <div class="benefit">
          <div class="benefit-icon ic-gold">💰</div>
          <div><h4>Экономия на персонале</h4><p>Автоматизация рутины освобождает 2-3 часа каждого менеджера ежедневно — эквивалент 0.5 ставки.</p></div>
        </div>
      </div>
    </div>
    <div class="calc-box reveal reveal-delay-2">
      <h3 style="font-family:'Syne',sans-serif;font-size:1.1rem;margin-bottom:1.75rem;font-weight:700">Введите данные вашего отдела продаж</h3>
      <div class="calc-row">
        <label>Менеджеров в отделе<span id="mgrLabel">5</span></label>
        <input type="range" min="1" max="50" value="5" step="1" id="mgrRange">
      </div>
      <div class="calc-row">
        <label>Средний чек квартиры (млн ₸)<span id="priceLabel">18</span></label>
        <input type="range" min="5" max="100" value="18" step="1" id="priceRange">
      </div>
      <div class="calc-row">
        <label>Сделок в месяц сейчас<span id="dealsLabel">12</span></label>
        <input type="range" min="1" max="200" value="12" step="1" id="dealsRange">
      </div>
      <div class="calc-row">
        <label>Текущая конверсия лидов (%)<span id="convLabel">8</span></label>
        <input type="range" min="1" max="30" value="8" step="1" id="convRange">
      </div>
      <div class="calc-divider"></div>
      <div class="result-block">
        <div class="result-label">Дополнительная выручка в год</div>
        <div class="result-big">+ <b id="roiResult">₸ 1.9 млрд</b></div>
        <div class="result-sub">при росте конверсии на 40%</div>
        <div class="result-row">
          <div class="rr-item"><div class="rr-val" id="extraDeals">+5</div><div class="rr-lbl">Доп. сделок / мес</div></div>
          <div class="rr-item"><div class="rr-val" id="savedHours">+150 ч</div><div class="rr-lbl">Сэкономлено / мес</div></div>
          <div class="rr-item"><div class="rr-val" id="roiMult">12×</div><div class="rr-lbl">Окупаемость</div></div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- HOW IT WORKS TIMELINE -->
<section class="timeline-section">
  <div class="reveal center" style="margin-bottom:0">
    <span class="s-tag">Запуск за 3 дня</span>
    <h2 class="s-title">Как начать работать</h2>
  </div>
  <div class="timeline">
    <div class="tl-item reveal">
      <div class="tl-card tl-left"><h4>Регистрация аккаунта</h4><p>2 минуты — email и номер телефона. Никаких договоров на старте.</p></div>
      <div class="tl-dot">1</div>
      <div></div>
    </div>
    <div class="tl-item reveal reveal-delay-1">
      <div></div>
      <div class="tl-dot">2</div>
      <div class="tl-card tl-right"><h4>Импорт базы объектов</h4><p>Загрузите Excel-файл с квартирами — шахматка заполнится автоматически за 30 секунд.</p></div>
    </div>
    <div class="tl-item reveal reveal-delay-2">
      <div class="tl-card tl-left"><h4>Подключение каналов</h4><p>WhatsApp Business, Telegram-бот, форма с сайта — по пошаговой инструкции, без программиста.</p></div>
      <div class="tl-dot">3</div>
      <div></div>
    </div>
    <div class="tl-item reveal">
      <div></div>
      <div class="tl-dot">4</div>
      <div class="tl-card tl-right"><h4>Онбординг команды</h4><p>Персональный менеджер UY Market проводит обучение — обычно хватает 2 часов.</p></div>
    </div>
    <div class="tl-item reveal reveal-delay-1">
      <div class="tl-card tl-left" style="border-color:rgba(0,201,141,.3)"><h4 style="color:var(--accent2)">Первые результаты</h4><p>Уже на первой неделе команда видит прирост скорости обработки лидов. Через месяц — рост конверсии.</p></div>
      <div class="tl-dot" style="border-color:var(--accent2);color:var(--accent2)">✓</div>
      <div></div>
    </div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section style="background:var(--c1)">
  <div class="reveal center">
    <span class="s-tag">Отзывы клиентов</span>
    <h2 class="s-title">Говорят застройщики<br>и риэлторы</h2>
    <p class="s-sub">Реальные результаты из реальных компаний.</p>
  </div>
  <div class="testi-wrap reveal">
    <div class="tcard">
      <div class="tcard-result">+38% конверсия</div>
      <div class="tcard-stars">★★★★★</div>
      <p class="tcard-text">За 3 месяца конверсия выросла с 8% до 14%. Менеджеры больше не забывают о клиентах — система сама напоминает о каждом шаге.</p>
      <div class="tcard-author"><div class="tcard-av" style="background:linear-gradient(135deg,#2563FF,#48A8D6)">АС</div><div><div class="tcard-name">Арман Сейткали</div><div class="tcard-role">Директор продаж, BI Group · Застройщик</div></div></div>
    </div>
    <div class="tcard">
      <div class="tcard-result">0 двойных броней</div>
      <div class="tcard-stars">★★★★★</div>
      <p class="tcard-text">Наше агентство работает с 12 застройщиками сразу. UY Market объединил все шахматки в одном окне — риэлторы видят реальный остаток квартир в моменте.</p>
      <div class="tcard-author"><div class="tcard-av" style="background:linear-gradient(135deg,#00C98D,#1a9e6a)">МЖ</div><div><div class="tcard-name">Мадина Жумабаева</div><div class="tcard-role">CEO, Asyl Realty · Риэлторское агентство</div></div></div>
    </div>
    <div class="tcard">
      <div class="tcard-result">×3 скорость ответа</div>
      <div class="tcard-stars">★★★★★</div>
      <p class="tcard-text">WhatsApp-интеграция изменила всё. Клиенты получают ответы мгновенно, а все переписки хранятся в одном месте — никаких потерь.</p>
      <div class="tcard-author"><div class="tcard-av" style="background:linear-gradient(135deg,#A78BFA,#673ab7)">НТ</div><div><div class="tcard-name">Нуржан Тасбеков</div><div class="tcard-role">Коммерческий директор, Orion Dev · Застройщик</div></div></div>
    </div>
  </div>
</section>

<!-- PRICING -->
<section id="pricing" class="pricing-section">
  <div class="reveal center">
    <span class="s-tag">Тарифы</span>
    <h2 class="s-title">Честное ценообразование</h2>
    <p class="s-sub">14 дней бесплатно без привязки карты. Отмена в любой момент.</p>
  </div>
  <div class="price-grid reveal">
    <div class="pcard">
      <div class="pname">Старт</div>
      <div class="pprice"><sup>₸</sup>49 000</div>
      <div class="pperiod">в месяц · до 3 менеджеров</div>
      <ul class="pfeats">
        <li>1 жилой комплекс</li>
        <li>Шахматка (до 200 квартир)</li>
        <li>WhatsApp интеграция</li>
        <li>Воронка продаж</li>
        <li>Базовые отчёты</li>
        <li class="dim">AI-аналитика</li>
        <li class="dim">Электронные договоры</li>
      </ul>
      <button class="pbtn outline">Начать бесплатно</button>
    </div>
    <div class="pcard star">
      <div class="pbadge">Самый популярный</div>
      <div class="pname">Бизнес</div>
      <div class="pprice"><sup>₸</sup>149 000</div>
      <div class="pperiod">в месяц · до 15 менеджеров</div>
      <ul class="pfeats">
        <li>До 5 жилых комплексов</li>
        <li>Шахматка без ограничений</li>
        <li>Все мессенджеры + Instagram</li>
        <li>AI-скоринг и прогнозы</li>
        <li>Электронные договоры (ЭЦП)</li>
        <li>Расширенная аналитика</li>
        <li>Приоритетная поддержка 24/7</li>
      </ul>
      <button class="pbtn filled">Начать бесплатно</button>
    </div>
    <div class="pcard">
      <div class="pname">Энтерпрайз</div>
      <div class="pprice" style="font-size:2rem">Индивид.</div>
      <div class="pperiod">по запросу · без ограничений</div>
      <ul class="pfeats">
        <li>Неограниченные объекты</li>
        <li>Кастомные интеграции (1С, SAP)</li>
        <li>White-label версия</li>
        <li>On-premise развёртывание</li>
        <li>SLA 99.9% · персональный менеджер</li>
        <li>Обучение команды на месте</li>
        <li>Приоритетная разработка фичей</li>
      </ul>
      <button class="pbtn outline">Связаться с нами</button>
    </div>
  </div>
</section>

<!-- CTA -->
<div class="cta-band">
  <div class="cta-inner">
    <h2>Начните прямо сейчас —<br>для застройщиков и риэлторов</h2>
    <p>Оставьте номер — наш менеджер свяжется за 15 минут и настроит демо под ваш бизнес.</p>
    <div class="form-inline">
      <input type="tel" placeholder="+7 или +998 · Ваш номер">
      <button class="btn-nav" style="padding:.85rem 1.75rem;font-size:.95rem;white-space:nowrap">Получить демо →</button>
    </div>
    <div class="cta-note">Никакого спама. Только один звонок от менеджера UY Market.</div>
  </div>
</div>

<!-- FOOTER -->
<footer>
  <div class="footer-top">
    <div class="footer-brand">
      <a class="logo" href="#" style="margin-bottom:.5rem;display:inline-flex">
        <svg width="32" height="32" viewBox="0 0 60 60" fill="none"><path d="M6 32L30 10L54 32" stroke="#2563FF" stroke-width="7" stroke-linecap="round" stroke-linejoin="round"/><rect x="8" y="37" width="14" height="14" rx="3" fill="#00C98D"/><rect x="24" y="37" width="14" height="14" rx="3" fill="#00C98D"/><rect x="16" y="52" width="14" height="7" rx="2" fill="#00C98D"/></svg>
        <span class="logo-name" style="margin-left:8px">UY MARKET<small>CRM платформа</small></span>
      </a>
      <p>Профессиональная CRM для застройщиков и риэлторов. Автоматизируйте продажи и растите быстрее рынка.</p>
      <div class="footer-socials">
        <a class="fsoc" href="#">TG</a>
        <a class="fsoc" href="#">WA</a>
        <a class="fsoc" href="#">IG</a>
        <a class="fsoc" href="#">YT</a>
      </div>
    </div>
    <div class="footer-col">
      <h5>Продукт</h5>
      <ul>
        <li><a href="#">Шахматка</a></li>
        <li><a href="#">Воронка продаж</a></li>
        <li><a href="#">AI-аналитика</a></li>
        <li><a href="#">Договоры (ЭЦП)</a></li>
        <li><a href="#">Интеграции</a></li>
      </ul>
    </div>
    <div class="footer-col">
      <h5>Компания</h5>
      <ul>
        <li><a href="#">О нас</a></li>
        <li><a href="#">Кейсы</a></li>
        <li><a href="#">Блог</a></li>
        <li><a href="#">Вакансии</a></li>
        <li><a href="#">Партнёры</a></li>
      </ul>
    </div>
    <div class="footer-col">
      <h5>Поддержка</h5>
      <ul>
        <li><a href="#">Документация</a></li>
        <li><a href="#">Видеоуроки</a></li>
        <li><a href="#">Статус системы</a></li>
        <li><a href="#">Написать нам</a></li>
        <li><a href="#">+998 71 200-00-00</a></li>
      </ul>
    </div>
  </div>
  <div class="footer-bottom">
    <span>© 2025 UY Market CRM. Все права защищены.</span>
    <div style="display:flex;gap:1.5rem">
      <a href="#" style="color:var(--muted);text-decoration:none;font-size:.8rem">Политика конфиденциальности</a>
      <a href="#" style="color:var(--muted);text-decoration:none;font-size:.8rem">Пользовательское соглашение</a>
    </div>
  </div>
</footer>

<script>
// CURSOR GLOW
const glow = document.getElementById('cursor-glow');
document.addEventListener('mousemove', e => {
  glow.style.left = e.clientX + 'px';
  glow.style.top = e.clientY + 'px';
});

// SCROLL REVEAL
const ro = new IntersectionObserver(entries => {
  entries.forEach(e => { if(e.isIntersecting) e.target.classList.add('in'); });
}, {threshold: 0.1});
document.querySelectorAll('.reveal').forEach(el => ro.observe(el));

// LIVE KPI ANIMATION
const counters = [
  {el: 'kpi1', target: 74, suffix: ''},
  {el: 'kpi2', target: 342, suffix: ''},
];
counters.forEach(({el, target, suffix}) => {
  const node = document.getElementById(el);
  let v = 0;
  const tick = () => {
    v = Math.min(v + Math.ceil(target / 40), target);
    node.textContent = v + suffix;
    if(v < target) requestAnimationFrame(tick);
  };
  setTimeout(tick, 600);
});

// LIVE PULSING KPI
setInterval(() => {
  const delta = Math.floor(Math.random() * 3) - 1;
  const el = document.getElementById('kpi2');
  if(el) el.textContent = Math.max(340, parseInt(el.textContent) + delta);
}, 3000);

// SHAKHMTKA
const aptData = [
  ['sold','booked','free','free','reserved','sold','free','free'],
  ['free','sold','sold','free','free','booked','sold','free'],
  ['booked','free','free','sold','free','free','free','sold'],
  ['sold','free','booked','free','sold','reserved','free','booked'],
  ['free','free','sold','free','free','sold','free','free'],
];
const typeNames = ['Свободна','Забронирована','Продана','В резерве'];
const prices = {free:'от ₸14.5M',booked:'₸21.8M',sold:'Продана',reserved:'₸18.2M (резерв)'};
const rooms = ['1-комн','2-комн','3-комн','Студия'];

function buildGrid(floor) {
  const grid = document.getElementById('aptGrid');
  grid.innerHTML = '';
  const rows = aptData;
  rows.forEach((row, ri) => {
    row.forEach((type, ci) => {
      const div = document.createElement('div');
      div.className = 'apt ' + type;
      const aptNum = (floor * 100) + (ri + 1) * 10 + ci + 1;
      const room = rooms[(ri + ci) % 4];
      div.innerHTML = `${aptNum}<div class="apt-tooltip">${room}<br>${prices[type]}<br>Этаж ${floor * 5 + ri + 1}</div>`;
      grid.appendChild(div);
    });
  });
}
buildGrid(1);

document.getElementById('floorSel').addEventListener('click', e => {
  const btn = e.target.closest('.floor-btn');
  if(!btn) return;
  document.querySelectorAll('.floor-btn').forEach(b => b.classList.remove('active'));
  btn.classList.add('active');
  buildGrid(parseInt(btn.dataset.f));
});

// ROI CALCULATOR
const inputs = {
  mgr: {range: 'mgrRange', label: 'mgrLabel'},
  price: {range: 'priceRange', label: 'priceLabel'},
  deals: {range: 'dealsRange', label: 'dealsLabel'},
  conv: {range: 'convRange', label: 'convLabel'},
};
function calcROI() {
  const mgr = parseInt(document.getElementById('mgrRange').value);
  const price = parseInt(document.getElementById('priceRange').value);
  const deals = parseInt(document.getElementById('dealsRange').value);
  const conv = parseInt(document.getElementById('convRange').value);
  const extraDeals = Math.round(deals * 0.4);
  const annualExtra = extraDeals * price * 12;
  const savedH = mgr * 2.5 * 22;
  const tariff = mgr <= 3 ? 49 : mgr <= 15 ? 149 : 299;
  const roiMult = Math.round(annualExtra / (tariff * 1000 * 12));
  document.getElementById('roiResult').textContent = annualExtra >= 1000 
    ? '₸ ' + (annualExtra / 1000).toFixed(1) + ' млрд'
    : '₸ ' + annualExtra + ' млн';
  document.getElementById('extraDeals').textContent = '+' + extraDeals;
  document.getElementById('savedHours').textContent = '+' + Math.round(savedH) + ' ч';
  document.getElementById('roiMult').textContent = roiMult + '×';
}
Object.keys(inputs).forEach(key => {
  const r = document.getElementById(inputs[key].range);
  const l = document.getElementById(inputs[key].label);
  r.addEventListener('input', () => { l.textContent = r.value; calcROI(); });
});
calcROI();

// BAR CHART INTERACTION
document.querySelectorAll('.bar').forEach((bar, i) => {
  bar.addEventListener('mouseenter', () => {
    document.querySelectorAll('.bar').forEach(b => b.classList.remove('active'));
    bar.classList.add('active');
  });
});
</script>
</body>
</html>

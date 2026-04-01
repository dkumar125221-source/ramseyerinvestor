[Uploading index.html…]()
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>U.S. Investment Immigration — Ramseyer & Associates PC</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;1,300;1,400&family=Jost:wght@200;300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
  --ink: #0D1B2A;
  --paper: #F8F7F3;
  --deep: #0A3161;
  --navy: #0A3161;
  --navy-2: #153E75;
  --navy-pale: #EEF3FA;
  --red: #B31942;
  --red-deep: #8C1233;
  --red-pale: #FEF4F6;
  --gold: #C8A96B;
  --gold-lt: #DFC59A;
  --gold-pale: #F5EDE3;
  --muted: #4B5A6A;
  --rule: rgba(10,49,97,0.14);
  --serif: 'Cormorant Garamond', Georgia, serif;
  --sans: 'Jost', 'Helvetica Neue', sans-serif;
}

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  html { scroll-behavior: smooth; }

  body {
    background: var(--paper);
    color: var(--ink);
    font-family: var(--sans);
    font-weight: 300;
    font-size: 15px;
    line-height: 1.75;
    -webkit-font-smoothing: antialiased;
  }

  /* ── UTILITY ─────────────────────────────── */
  .rule-gold       { display:block;width:48px;height:1px;background:var(--gold);margin:0 auto 2rem; }
  .rule-gold.left  { margin-left:0; }
  .label           { font-family:var(--sans);font-size:10px;font-weight:500;letter-spacing:.25em;text-transform:uppercase;color:var(--gold); }
  .section-number  { font-family:var(--serif);font-size:11px;font-weight:300;letter-spacing:.18em;color:var(--gold);display:block;margin-bottom:.5rem; }

  /* ── TOPBAR ──────────────────────────────── */
  #topbar {
    background: transparent;
    color: var(--ink);
    padding: .65rem 3rem;
    font-size: 11px;
    letter-spacing: .08em;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 1rem;
    flex-wrap: wrap;
    border-bottom: 1px solid rgba(0,0,0,.08);
  }
  #topbar a { color: var(--ink); text-decoration: none; }
  .topbar-left { display:flex; gap:2rem; flex-wrap:wrap; }
  .topbar-item { display:flex; align-items:center; gap:.5rem; }

  /* ── COVER ───────────────────────────────── */
  #cover {
    background: transparent;
    color: var(--ink);
    min-height: auto;
    display: block;
    padding: 3rem 3rem 2.5rem;
    position: relative;
    overflow: visible;
  }

  #cover::before,
  #cover::after {
    display: none;
  }

  /* Logo header inside cover */
  .cover-top {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    position: relative;
    z-index: 1;
  }

  .cover-logo img {
    height: 56px;
    filter: none;
    opacity: .95;
  }

  .cover-meta {
    font-size: 10px;
    letter-spacing: .18em;
    text-transform: uppercase;
    color: var(--muted);
    text-align: right;
    line-height: 1.9;
  }

  .cover-body { position:relative;z-index:1;max-width:700px; }

  .cover-eyebrow {
    font-family:var(--sans);font-size:10px;font-weight:400;
    letter-spacing:.3em;text-transform:uppercase;
    color:var(--gold);margin-bottom:2rem;
  }

  .cover-h1 {
    font-family:var(--serif);
    font-size:clamp(42px,5.8vw,70px);
    font-weight:300;line-height:1.1;color:var(--deep);margin-bottom:2rem;
  }
  .cover-h1 em { font-style:italic;color:var(--gold-lt); }

  .cover-tagline {
    font-size:14px;font-weight:300;
    color:var(--muted);letter-spacing:.04em;
    max-width:480px;line-height:1.85;
    border-left:1px solid var(--gold);padding-left:1.25rem;
  }

  .cover-bottom {
    position:relative;z-index:1;
    display:flex;justify-content:space-between;align-items:flex-end;
    flex-wrap:wrap;gap:1.5rem;
  }

  .cover-pills { display:flex;gap:1rem;flex-wrap:wrap; }
  .pill {
    border:1px solid rgba(184,149,106,.4);
    padding:.3rem .9rem;font-size:10px;letter-spacing:.2em;
    text-transform:uppercase;color:var(--gold-lt);border-radius:2px;
  }
  .cover-conf { font-size:10px;letter-spacing:.2em;text-transform:uppercase;color:var(--muted); }

  /* ── NAV / TOC ───────────────────────────── */
  nav#toc {
    background: transparent;
    color: var(--ink);
    padding:1.5rem 3rem;
    border-top:1px solid rgba(0,0,0,.08);
  }
  .toc-grid { display:flex;gap:1.75rem;flex-wrap:wrap; }
  .toc-item {
    display:flex;align-items:baseline;gap:.65rem;
    font-size:10.5px;letter-spacing:.15em;text-transform:uppercase;
    color:var(--ink);text-decoration:none;
  }
  .toc-item:hover { color:var(--gold); }
  .toc-num { color:var(--gold);font-family:var(--serif);font-size:13px;font-style:italic; }

  /* ── GENERAL SECTION ─────────────────────── */
  .section { padding:3rem 3rem;max-width:900px;margin:0 auto; }
  .section-header { margin-bottom:3.5rem; }
  .section-h2 {
    font-family:var(--serif);font-size:clamp(30px,4vw,50px);
    font-weight:300;line-height:1.15;color:var(--deep);margin-bottom:1.25rem;
  }
  .section-h2 em { font-style:italic;color:var(--gold); }
  .section-intro { font-size:16px;font-weight:300;color:var(--muted);max-width:640px;line-height:1.85; }

  /* ── DARK SECTION ────────────────────────── */
  .section-dark { background:var(--paper);color:var(--ink);padding:3rem 3rem;border:1px solid rgba(0,0,0,.08); }
  .section-dark .section-h2 { color:var(--deep); }
  .section-dark .section-intro { color:var(--muted); }
  .section-dark .section-inner { max-width:900px;margin:0 auto; }

  /* ── CARDS ───────────────────────────────── */
  .cards {
    display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:0;border:1.5px solid var(--rule);margin-top:3rem;
  }
  .card {
    padding:2.25rem 2rem;border-right:1.5px solid var(--rule);
    border-bottom:1.5px solid var(--rule);background:#fff;
  }
  .card:last-child { border-right:none; }
  .card h3 { font-family:var(--serif);font-size:21px;font-weight:400;color:var(--deep);margin-bottom:.75rem;line-height:1.3; }
  .card p { font-size:13.5px;color:var(--muted);line-height:1.8; }

  .cards-dark .card { background:#fff;border-color:rgba(0,0,0,.08); }
  .cards-dark .card h3 { color:var(--deep); }
  .cards-dark .card p { color:var(--muted); }

  /* ── TWO-COL DETAIL ──────────────────────── */
  .detail-block {
    display:grid;grid-template-columns:1fr 1fr;
    gap:4rem;margin-top:3.5rem;padding-top:3.5rem;
    border-top:1px solid var(--rule);
  }
  @media(max-width:768px){
    .detail-block{grid-template-columns:1fr;gap:2rem;}
    #cover,.section,.section-dark{padding-left:1.75rem;padding-right:1.75rem;}
    nav#toc{padding-left:1.75rem;padding-right:1.75rem;}
    #topbar{padding-left:1.75rem;padding-right:1.75rem;}
    .cover-bottom{flex-direction:column;}
    .toc-grid{gap:1.25rem;}
  }

  .detail-col h4 {
    font-family:var(--serif);font-size:19px;font-weight:400;
    color:var(--deep);margin-bottom:1rem;
  }
  .section-dark .detail-col h4 { color:var(--gold-lt); }

  .detail-list { list-style:none;display:flex;flex-direction:column;gap:.6rem; }
  .detail-list li { display:flex;gap:.75rem;font-size:13.5px;color:var(--muted);line-height:1.7; }
  .section-dark .detail-list li { color:var(--muted); }
  .detail-list li::before { content:'—';color:var(--gold);flex-shrink:0;margin-top:.05em; }

  /* ── PULL QUOTE ──────────────────────────── */
  .pull-quote {
    margin:4rem 0;padding:2.5rem 3rem;
    border-left:3px solid var(--gold);background:var(--gold-pale);
  }
  .pull-quote p {
    font-family:var(--serif);font-size:22px;font-weight:300;
    font-style:italic;color:var(--deep);line-height:1.55;
  }

  /* ── PROCESS STEPS ───────────────────────── */
  .steps {
    margin-top:3rem;display:flex;flex-direction:column;
    border-left:1px solid var(--rule);padding-left:2.5rem;
    position:relative;margin-left:1.5rem;
  }
  .step { position:relative;padding-bottom:2.5rem; }
  .step:last-child { padding-bottom:0; }
  .step::before {
    content:attr(data-n);
    position:absolute;left:calc(-2.5rem - 0.9rem);top:.1rem;
    width:1.8rem;height:1.8rem;border-radius:50%;
    background:var(--deep);color:var(--gold);
    font-family:var(--serif);font-size:13px;font-style:italic;
    display:flex;align-items:center;justify-content:center;
    border:1px solid var(--gold);
  }
  .section-dark .steps { border-color:rgba(184,149,106,.25); }
  .section-dark .step::before { background:var(--gold-pale); color:var(--deep); border-color:var(--gold); }
  .step h4 { font-family:var(--serif);font-size:19px;font-weight:400;color:var(--deep);margin-bottom:.4rem; }
  .section-dark .step h4 { color:var(--gold-lt); }
  .step p { font-size:13.5px;color:var(--muted);line-height:1.75;max-width:600px; }
  .section-dark .step p { color:var(--muted); }

  /* ── COMPARISON TABLE ────────────────────── */
  .table-wrap { overflow-x:auto;margin-top:3rem;border:1px solid var(--rule); }
  table { width:100%;border-collapse:collapse;font-size:13px;min-width:700px; }
  thead tr { background:var(--deep);color:var(--gold-lt); }
  thead th {
    padding:1rem 1.25rem;text-align:left;
    font-family:var(--sans);font-weight:400;font-size:10px;
    letter-spacing:.2em;text-transform:uppercase;
    border-right:1px solid rgba(184,149,106,.15);
  }
  thead th:last-child { border-right:none; }
  tbody tr { border-bottom:1px solid var(--rule);transition:background .15s; }
  tbody tr:hover { background:var(--gold-pale); }
  tbody td { padding:1rem 1.25rem;vertical-align:top;border-right:1px solid var(--rule);color:var(--ink);line-height:1.65; }
  tbody td:last-child { border-right:none; }
  tbody td:first-child { font-family:var(--serif);font-weight:400;font-size:15px;color:var(--deep);white-space:nowrap; }
  td .badge { display:inline-block;padding:.15rem .55rem;border-radius:2px;font-size:10px;letter-spacing:.12em;text-transform:uppercase;font-weight:400; }
  .badge-green { background:#d4edda;color:#1a5c30; }
  .badge-amber { background:#fff3cd;color:#6d4c00; }

  /* ── HIGHLIGHT BOX ───────────────────────── */
  .highlight-box { border:1px solid var(--gold);padding:1.75rem 2rem;margin:2.5rem 0;background:rgba(184,149,106,.04); }
  .highlight-box p { font-size:13.5px;color:var(--muted);line-height:1.8; }
  .section-dark .highlight-box { background:rgba(184,149,106,.06); }
  .section-dark .highlight-box p { color:var(--muted); }

  hr.section-rule { border:none;border-top:1px solid var(--rule);margin:3.5rem 0; }
  .section-dark hr.section-rule { border-color:rgba(184,149,106,.2); }

  /* ── TREATY COUNTRIES GRID ───────────────── */
  .treaty-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(175px, 1fr));
    gap: 1px;
    margin-top: 2.5rem;
    background: var(--rule);
    border: 1px solid var(--rule);
  }
  .treaty-item {
    display: flex;
    align-items: center;
    gap: .85rem;
    padding: .85rem 1.1rem;
    background: #fff;
    transition: background .15s;
    cursor: default;
  }
  .treaty-item:hover { background: var(--gold-pale); }
  .treaty-flag {
    font-size: 22px;
    line-height: 1;
    flex-shrink: 0;
    width: 28px;
    text-align: center;
  }
  .treaty-name {
    font-family: var(--sans);
    font-size: 12px;
    font-weight: 400;
    letter-spacing: .06em;
    color: var(--deep);
    line-height: 1.3;
  }
  .treaty-note {
    font-size: 11px;
    color: var(--muted);
    margin-top: 1.5rem;
    line-height: 1.75;
    padding-left: .5rem;
    border-left: 2px solid var(--gold);
  }

  /* UAE callout in E-2 */
  .uae-note {
    background: rgba(184,149,106,.08);
    border: 1px solid rgba(184,149,106,.35);
    padding: 1.25rem 1.5rem;
    margin-top: 2rem;
    font-size: 13px;
    color: var(--muted);
    line-height: 1.8;
  }
  .uae-note strong { color: var(--deep); }

  /* ── SERVICE GRID ────────────────────────── */
  .service-grid {
    display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:1.5px;margin-top:3rem;background:rgba(0,0,0,.04);
    border:1px solid rgba(0,0,0,.08);
  }
  .service-item { padding:1.75rem;background:#fff; }
  .service-item h4 { font-family:var(--serif);font-size:19px;font-weight:400;color:var(--gold-lt);margin-bottom:.6rem; }
  .service-item p { font-size:13.5px;color:var(--muted);line-height:1.75; }

  /* ── TAGLINES ────────────────────────────── */
  .taglines { list-style:none;margin-top:1.5rem;display:flex;flex-direction:column;gap:.6rem; }
  .taglines li {
    font-family:var(--serif);font-size:19px;font-style:italic;
    color:var(--deep);padding-left:1.5rem;border-left:2px solid var(--gold);line-height:1.4;
  }

  /* ── TITLE OPTIONS ───────────────────────── */
  .title-options { display:flex;flex-direction:column;gap:1rem;margin-top:2rem; }
  .title-opt { display:flex;gap:1.5rem;align-items:baseline; }
  .title-opt .num { font-family:var(--serif);font-size:18px;font-style:italic;color:var(--gold);flex-shrink:0;width:1.5rem; }
  .title-opt .t { font-family:var(--serif);font-size:21px;font-weight:300;color:var(--deep);line-height:1.3; }

  /* ── CTA ─────────────────────────────────── */
  #cta {
    background: transparent;
    padding:3.5rem 3rem;text-align:center;
    position:relative;overflow:visible;
  }
  #cta::before {
    display: none;
  }
  .cta-inner { position:relative;z-index:1;max-width:640px;margin:0 auto; }
  .cta-h2 { font-family:var(--serif);font-size:clamp(34px,5vw,56px);font-weight:300;color:var(--deep);line-height:1.15;margin-bottom:1.5rem; }
  .cta-h2 em { font-style:italic;color:var(--gold-lt); }
  .cta-body { font-size:15px;color:var(--muted);line-height:1.85;margin-bottom:2.5rem; }
  .btn-gold {
    display:inline-block;padding:1rem 2.5rem;
    background:var(--gold);color:var(--deep);
    font-family:var(--sans);font-size:11px;font-weight:500;
    letter-spacing:.25em;text-transform:uppercase;
    text-decoration:none;border:none;cursor:pointer;
    transition:background .2s,transform .15s;
  }
  .btn-gold:hover { background:var(--gold-lt);transform:translateY(-1px); }
  .cta-note { margin-top:1.5rem;font-size:11px;letter-spacing:.1em;color:var(--muted);text-transform:uppercase; }

  /* ── FOOTER ──────────────────────────────── */
  footer {
    background: transparent;
    color: var(--muted);
    padding:2.5rem 3rem;font-size:11px;letter-spacing:.06em;
    display:flex;justify-content:space-between;align-items:center;
    flex-wrap:wrap;gap:1.5rem;
  }
  footer a { color:var(--gold);text-decoration:none; }
  .footer-logo img { height:30px;filter:none;opacity:.85; }

  /* ── ANIMATED ENTRY ──────────────────────── */
  @keyframes fadeUp { from{opacity:0;transform:translateY(20px)} to{opacity:1;transform:translateY(0)} }
  .fade-up { opacity:0;animation:fadeUp .7s ease forwards; }
  .fade-up.d1{animation-delay:.15s}.fade-up.d2{animation-delay:.35s}
  .fade-up.d3{animation-delay:.55s}.fade-up.d4{animation-delay:.75s}

  /* ── DIVIDER ─────────────────────────────── */
  .page-rule { border:none;border-top:1px solid var(--rule);max-width:1100px;margin:0 auto; }

  @media print {
    @page { size: A4 portrait; margin: 18mm; }
    html, body { background: white !important; color: #111 !important; font-size: 12pt !important; line-height: 1.5 !important; }
    body { background: white !important; }
    * { transition: none !important; animation: none !important; }
    a { color: #111 !important; text-decoration: none !important; }
    img { filter: none !important; }
    #topbar, nav#toc, .section, .section-dark, #cta, footer { background: white !important; color: #111 !important; border: none !important; padding: 18px !important; }
    .section { padding: 18px 0 !important; }
    .section-dark { padding: 18px 0 !important; border: none !important; }
    #cover { padding: 18px 0 0 !important; }
    .cards, .detail-block, .treaty-grid, .service-grid, .table-wrap { page-break-inside: avoid !important; }
    .card { page-break-inside: avoid !important; }
    .toc-grid { gap: 1rem !important; }
    .toc-item:hover, tbody tr:hover, .treaty-item:hover, .btn-gold:hover { background: transparent !important; color: inherit !important; transform: none !important; }
    thead tr { background: #111 !important; color: #fff !important; }
    .cover-h1, .section-h2, .section-number, .cover-meta, .cover-tagline, .cover-conf, .cta-h2, .cta-body, .cta-note, .section-intro, .detail-list li, .pull-quote p, .highlight-box p, .step p { color: #111 !important; }
    .cover-tagline, .cover-meta, .cover-conf, .cta-body, .cta-note { color: #555 !important; }
    .section-dark .detail-list li, .section-dark .step p, .section-dark .highlight-box p { color: #555 !important; }
    .section-dark .detail-col h4, .section-dark .step h4 { color: #111 !important; }
    .cover-logo img, .footer-logo img { filter: none !important; }
    footer a { color: #111 !important; }
    .page-rule { border-color: rgba(0,0,0,.12) !important; }
  }

/* ════════════════════════════════════════════════════════
   AMERICAN PATRIOTIC THEME — Red, White & Blue
   All text colors chosen for WCAG AA contrast (≥4.5:1)
   ════════════════════════════════════════════════════════ */

/* TOPBAR */
#topbar {
  background: linear-gradient(90deg, #0A3161 0%, #153E75 100%);
  color: #fff;
  border-bottom: 3px solid #B31942;
}
#topbar a { color: #fff; }
#topbar a:hover { color: #DFC59A; }
#topbar .topbar-item,
#topbar .topbar-left span { color: rgba(255,255,255,.80); }
#topbar div[style] { color: rgba(255,255,255,.65) !important; }

/* COVER — 2-column layout with flag on right */
#cover {
  display: grid;
  grid-template-columns: 1fr 420px;
  min-height: 88vh;
  padding: 0;
  overflow: hidden;
  background: var(--paper);
}
.cover-left {
  padding: 3rem 3rem 2.5rem;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  gap: 2rem;
  background: var(--paper);
  position: relative;
  z-index: 2;
}
.cover-flag-panel {
  position: relative;
  overflow: hidden;
  flex-shrink: 0;
}
.cover-flag-panel img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  object-position: center center;
  display: block;
}
.cover-flag-panel::after {
  content: '';
  position: absolute;
  inset: 0;
  background: linear-gradient(90deg, var(--paper) 0%, rgba(248,247,243,.22) 22%, transparent 50%);
  pointer-events: none;
}
/* subtle patriotic stripe accent on left edge of flag panel */
.cover-flag-panel::before {
  content: '';
  position: absolute;
  top: 0; left: 0;
  width: 5px; height: 100%;
  background: linear-gradient(180deg, #B31942 33%, #fff 33% 66%, #0A3161 66%);
  z-index: 3;
  opacity: .55;
}

/* COVER CONTENT COLORS */
.cover-h1 { color: #0A3161 !important; }
.cover-h1 em { color: #B31942 !important; font-style: italic; }
.cover-eyebrow { color: #B31942 !important; letter-spacing: .28em; }
.cover-tagline {
  color: #4B5A6A !important;
  border-left: 1px solid #B31942 !important;
  padding-left: 1.25rem;
}
.cover-meta { color: #4B5A6A !important; }
.cover-conf { color: #4B5A6A !important; }
.pill {
  border: 1px solid rgba(10,49,97,.22) !important;
  color: #0A3161 !important;
  background: rgba(255,255,255,.88) !important;
  border-radius: 2px !important;
}

/* NAV / TOC */
#toc {
  background: #0A3161 !important;
  border-top: none !important;
  border-bottom: 3px solid #B31942 !important;
  padding-top: 1.25rem;
  padding-bottom: 1.25rem;
}
.toc-item { color: rgba(255,255,255,.76) !important; }
.toc-item:hover { color: #fff !important; }
.toc-num { color: #DFC59A !important; }

/* GLOBAL HEADING + ACCENT COLORS */
.section-h2 { color: #0A3161 !important; }
.section-h2 em { color: #B31942 !important; }
.section-number { color: #B31942 !important; }
.label { color: #B31942 !important; }
.rule-gold { background: #B31942 !important; }
.section-intro { color: #4B5A6A !important; }

/* CARD COLORS */
.card h3 { color: #0A3161 !important; }
.card p { color: #4B5A6A !important; }
.detail-col h4 { color: #0A3161 !important; }
.detail-list li { color: #4B5A6A !important; }
.detail-list li::before { color: #B31942 !important; }
.step h4 { color: #0A3161 !important; }
.step p { color: #4B5A6A !important; }

/* SECTION DARK → light blue-white wash for readability */
.section-dark {
  background: linear-gradient(180deg, #F0F5FC 0%, #E9EFF8 100%) !important;
  color: #0D1B2A !important;
  border: 1px solid rgba(10,49,97,.09) !important;
}
.section-dark .section-h2 { color: #0A3161 !important; }
.section-dark .section-h2 em { color: #B31942 !important; }
.section-dark .section-number { color: #B31942 !important; }
.section-dark .rule-gold { background: #B31942 !important; }
.section-dark .section-intro { color: #4B5A6A !important; }
.section-dark .detail-col h4 { color: #0A3161 !important; }
.section-dark .step h4 { color: #0A3161 !important; }
.section-dark .detail-list li { color: #4B5A6A !important; }
.section-dark .step p { color: #4B5A6A !important; }
.section-dark .highlight-box p { color: #4B5A6A !important; }
.section-dark .step::before {
  background: #0A3161 !important;
  color: #DFC59A !important;
  border-color: #C8A96B !important;
}
.section-dark .steps { border-left-color: rgba(10,49,97,.28) !important; }
.section-dark .card { background: #fff !important; }
.section-dark .card h3 { color: #0A3161 !important; }
.section-dark .card p { color: #4B5A6A !important; }
.section-dark .cards { border-color: rgba(10,49,97,.12) !important; }
.section-dark .card { border-right-color: rgba(10,49,97,.12) !important; border-bottom-color: rgba(10,49,97,.12) !important; }
.section-dark hr.section-rule { border-top-color: rgba(10,49,97,.15) !important; }
.section-dark .highlight-box {
  background: rgba(10,49,97,.04) !important;
  border-color: rgba(10,49,97,.18) !important;
}
.section-dark .detail-block { border-top-color: rgba(10,49,97,.15) !important; }
.section-dark h4[style] { color: #0A3161 !important; }
.section-dark .label { color: #B31942 !important; }
.section-dark .detail-list li::before { color: #B31942 !important; }

/* PULL QUOTE */
.pull-quote {
  background: linear-gradient(135deg, #EEF3FA, rgba(179,25,66,.04)) !important;
  border-left: 3px solid #B31942 !important;
}
.pull-quote p { color: #0A3161 !important; }

/* HIGHLIGHT BOX */
.highlight-box {
  border: 1px solid rgba(179,25,66,.22) !important;
  background: rgba(179,25,66,.03) !important;
}
.highlight-box p { color: #4B5A6A !important; }
.highlight-box strong { color: #0A3161 !important; }

/* PROCESS STEPS */
.steps { border-left-color: rgba(10,49,97,.25) !important; }
.step::before {
  background: #0A3161 !important;
  color: #DFC59A !important;
  border-color: #C8A96B !important;
}

/* COMPARISON TABLE */
thead tr { background: #0A3161 !important; color: #fff !important; }
thead th { color: #fff !important; border-right-color: rgba(255,255,255,.12) !important; }
tbody tr:hover { background: #EEF3FA !important; }
tbody td:first-child { color: #0A3161 !important; }
.table-wrap { border-color: rgba(10,49,97,.15) !important; }
.badge-green { background: #d4edda !important; color: #155724 !important; }
.badge-amber { background: #fff3cd !important; color: #856404 !important; }

/* TREATY COUNTRIES */
.treaty-grid { border-color: rgba(10,49,97,.12) !important; background: rgba(10,49,97,.07) !important; }
.treaty-item { background: #fff !important; }
.treaty-item:hover { background: #EEF3FA !important; }
.treaty-name { color: #0A3161 !important; font-weight: 500; }
.treaty-note { color: #4B5A6A !important; border-left-color: #B31942 !important; }
.uae-note { border-color: rgba(10,49,97,.2) !important; background: rgba(10,49,97,.04) !important; color: #4B5A6A !important; }
.uae-note strong { color: #0A3161 !important; }

/* SERVICE GRID */
.service-grid { background: rgba(10,49,97,.04) !important; border-color: rgba(10,49,97,.08) !important; }
.service-item { background: #fff !important; }
.service-item h4 { color: #0A3161 !important; }
.service-item p { color: #4B5A6A !important; }

/* TAGLINES */
.taglines li { color: #0A3161 !important; border-left-color: #B31942 !important; }

/* TITLE OPTIONS */
.title-opt .num { color: #B31942 !important; }
.title-opt .t { color: #0A3161 !important; }

/* CTA SECTION */
#cta {
  background: var(--paper) !important;
  border-top: 1px solid rgba(10,49,97,.1);
  border-bottom: 1px solid rgba(10,49,97,.1);
}
#cta .cta-h2 { color: #0A3161 !important; }
#cta .cta-h2 em { color: #B31942 !important; }
#cta .cta-body { color: #4B5A6A !important; }
#cta .cta-note { color: #4B5A6A !important; }

/* CTA BUTTON — American Red */
.btn-gold {
  background: linear-gradient(90deg, #B31942 0%, #8C1233 100%) !important;
  color: #fff !important;
  box-shadow: 0 8px 24px rgba(179,25,66,.20) !important;
  border-radius: 2px !important;
}
.btn-gold:hover {
  background: linear-gradient(90deg, #C41D4D 0%, #A3163C 100%) !important;
  transform: translateY(-1px) !important;
  box-shadow: 0 12px 32px rgba(179,25,66,.28) !important;
}

/* FIRM SECTION */
#firm { background: var(--paper) !important; }
#firm .section-h2 { color: #0A3161 !important; }
#firm .section-h2 em { color: #B31942 !important; }
#firm .card h3 { color: #0A3161 !important; }
#firm .card p { color: #4B5A6A !important; }
#firm .detail-col h4 { color: #0A3161 !important; }
#firm .detail-list li { color: #4B5A6A !important; }
#firm .highlight-box strong { color: #0A3161 !important; }
#firm .highlight-box p { color: #4B5A6A !important; }
#firm .section-intro { color: #4B5A6A !important; }
#firm em { color: #4B5A6A; font-style: italic; }

/* PAGE DIVIDERS */
.page-rule { border-top-color: rgba(10,49,97,.12) !important; }
hr.section-rule { border-top-color: rgba(10,49,97,.12) !important; }

/* FOOTER */
footer {
  background: #0A3161 !important;
  color: rgba(255,255,255,.65) !important;
  border-top: 3px solid #B31942 !important;
}
footer a { color: #DFC59A !important; }
footer a:hover { color: #fff !important; }
.footer-logo img { filter: brightness(0) invert(1) !important; opacity: .85 !important; }

/* FADE-UP ANIMATION — keep original */
@keyframes fadeUp {
  from { opacity: 0; transform: translateY(20px); }
  to   { opacity: 1; transform: translateY(0); }
}

/* PRINT */
@media print {
  #topbar, #toc { background: #0A3161 !important; -webkit-print-color-adjust: exact; print-color-adjust: exact; }
  .section-dark { background: #F0F5FC !important; }
  footer { background: #0A3161 !important; -webkit-print-color-adjust: exact; print-color-adjust: exact; }
  .cover-flag-panel { display: block !important; height: 400px !important; }
  #cover { grid-template-columns: 1fr 380px !important; }
}

/* RESPONSIVE */
@media (max-width: 960px) {
  #cover {
    grid-template-columns: 1fr !important;
    min-height: auto !important;
  }
  .cover-flag-panel {
    height: 300px;
    order: -1;
  }
  .cover-flag-panel::after {
    background: linear-gradient(180deg, transparent 55%, var(--paper) 100%) !important;
  }
  .cover-left {
    padding: 2rem 1.75rem !important;
  }
}
@media (max-width: 600px) {
  .cover-flag-panel { height: 210px; }
  .cover-left { padding: 1.5rem !important; }
}

</style>
</head>
<body>

<!-- ══ TOPBAR ══════════════════════════════════════════ -->
<div id="topbar">
  <div class="topbar-left">
    <span class="topbar-item">📍 <a href="https://ramseyerattorneys.com/map-find-our-location" target="_blank">14 Penn Plaza, 34th Street, New York, NY</a></span>
    <span class="topbar-item">✉ <a href="mailto:info@ramseyerattorneys.com">info@ramseyerattorneys.com</a></span>
    <span class="topbar-item">📞 <a href="tel:13477124488">+1 347 712 4488</a></span>
  </div>
  <div style="font-size:10px;letter-spacing:.18em;text-transform:uppercase;color:var(--muted);">
    Confidential Investor Brochure &nbsp;·&nbsp; 
  </div>
</div>

<!-- ══ COVER ════════════════════════════════════════════ -->
<section id="cover">
<div class="cover-left">

  <div class="cover-top fade-up">
    <div class="cover-logo">
      <img src="https://img1.wsimg.com/isteam/ip/94b29341-0380-49bf-944f-0d379ab4e949/logo-horizontal-transparent.png/:/rs=h:170,cg:true,m/qt=q:95" alt="Ramseyer & Associates PC Attorneys">
    </div>
    <div class="cover-meta">
      Founded 2002 &nbsp;·&nbsp; New York, NY<br>
      Investor Immigration Practice<br>
      For Qualified Clients Only
    </div>
  </div>

  <div class="cover-body">
    <p class="cover-eyebrow fade-up d1">Strategic U.S. Immigration for Global Investors &amp; Founders</p>
    <h1 class="cover-h1 fade-up d2">
      <em>Investing in America: <br> EB-5 & E-2 Pathways for Global Entrepreneurs and Family Offices. 
    </h1>
    <p class="cover-tagline fade-up d3">
      A strategic guide to U.S. investment immigration pathways — designed for internationally mobile investors, entrepreneurs, and family office principals considering a long-term U.S. presence. Prepared by Ramseyer &amp; Associates PC, Attorneys at Law, New York.
    </p>
  </div>
</div><br>
  <div class="cover-bottom fade-up d4">
    <div class="cover-pills">
      <div class="pill">EB-5 Immigrant Investor</div>
      <div class="pill">E-2 Treaty Investor</div>
      <div class="pill">Strategic Pathway Planning</div>
      <div class="pill">Family Office Advisory</div>
    </div>
    <div class="cover-conf">2026 Edition &nbsp;·&nbsp; Subject to Current Government Regulations</div>
  </div>

</div>
<div class="cover-flag-panel">
  <img
    src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Flag_of_the_United_States.svg/1280px-Flag_of_the_United_States.svg.png"
    alt="United States of America Flag"
    width="1280"
    height="674"
    loading="eager"
    style="object-fit:cover;width:100%;height:100%;">
</div>
</section>
<nav id="toc">
  <div class="toc-grid">
    <a href="#exec"    class="toc-item"><span class="toc-num">I.</span> Executive Overview</a>
    <a href="#eb5"     class="toc-item"><span class="toc-num">II.</span> EB-5 Immigrant Investor</a>
    <a href="#e2"      class="toc-item"><span class="toc-num">III.</span> E-2 Treaty Investor</a>
    <a href="#compare" class="toc-item"><span class="toc-num">IV.</span> Side-by-Side Comparison</a>
    <a href="#firm"    class="toc-item"><span class="toc-num">V.</span> How Our Firm Helps</a>
    <a href="#cta"     class="toc-item"><span class="toc-num">VI.</span> Request a Consultation</a>
  </div>
</nav>


<!-- ══ I. EXECUTIVE OVERVIEW ════════════════════════════ -->
<section class="section" id="exec">
  <div class="section-header">
    <span class="section-number">Section I</span>
    <span class="rule-gold left"></span>
    <h2 class="section-h2">Executive <em>Overview</em></h2>
    <p class="section-intro">The United States remains one of the world's most consequential destinations for investors, entrepreneurs, and globally mobile families. Understanding your immigration options — before capital is committed — is not a formality. It is sound strategy.</p>
  </div>

  <div class="cards">
    <div class="card">
      <h3>Why the U.S. Remains Compelling</h3>
      <p>The United States offers unparalleled access to capital markets, consumer scale, legal stability, and institutional infrastructure. For internationally mobile investors, a secure U.S. immigration status unlocks not merely a right of residence — it opens the door to business formation, generational wealth planning, educational access, and long-term optionality across the world's largest economy.</p>
    </div>
    <div class="card">
      <h3>Pathway Selection Is a Strategic Decision</h3>
      <p>There is no universal best pathway. The right immigration strategy depends on your nationality, investment capacity, business model, timeline, family structure, and long-term residence objectives. A strategy well-suited to a European entrepreneur may be unavailable or impractical for an investor from a non-treaty country. Immigration strategy must be calibrated — not assumed.</p>
    </div>
    <div class="card">
      <h3>Structure Before Capital</h3>
      <p>The most consequential immigration decisions are made before the investment is executed. Source-of-funds documentation, corporate structuring, investment vehicle selection, and business ownership design all carry lasting immigration implications. Engaging qualified immigration counsel prior to committing capital is not merely cautious — it is essential due diligence.</p>
    </div>
  </div>

  <div class="pull-quote">
    <p>"The question is never simply which visa. It is which pathway best serves your capital, your family, and the life you intend to build — now and a decade from now."</p>
  </div>

  <div class="detail-block">
    <div class="detail-col">
      <h4>About Ramseyer &amp; Associates PC</h4>
      <ul class="detail-list">
        <li>Founded in 2002 — over two decades of high-quality legal representation across New York and internationally</li>
        <li>Practice areas include Immigration Law, Corporate Law, Real Estate, Family Law, Taxation, and Estate Planning</li>
        <li>Partnered with law firms in the United Kingdom, United Arab Emirates, India, Africa, South America, and North America</li>
        <li>A team of Ivy League-educated legal scholars committed to elite jurisprudence and strategic advocacy</li>
        <li>Conveniently located in midtown Manhattan — 14 Penn Plaza, 34th Street, New York, NY</li>
      </ul>
    </div>
    <div class="detail-col">
      <h4>What This Guide Covers</h4>
      <ul class="detail-list">
        <li>The EB-5 Immigrant Investor category — the primary U.S. permanent residence pathway for qualifying investors</li>
        <li>The E-2 Treaty Investor category — a renewable nonimmigrant option for treaty-country nationals</li>
        <li>A structured side-by-side comparison to guide strategic decision-making</li>
        <li>Practical guidance on next steps and how to begin a confidential strategy consultation</li>
      </ul>
    </div>
  </div>
</section>


<!-- ══ II. EB-5 ══════════════════════════════════════════ -->
<div class="section-dark" id="eb5">
<div class="section-inner">
  <div class="section-header">
    <span class="section-number">Section II</span>
    <span class="rule-gold left"></span>
    <h2 class="section-h2">EB-5 <em>Immigrant Investor</em></h2>
    <p class="section-intro">The most direct pathway to U.S. permanent residence through qualifying investment — and the most structurally significant decision an international investor can make.</p>
  </div>

  <div class="cards cards-dark">
    <div class="card">
      <h3>What Is EB-5?</h3>
      <p>The EB-5 Immigrant Investor Program provides a pathway to U.S. lawful permanent residence — commonly known as a green card — for qualifying investors who make a capital investment in a U.S. commercial enterprise and create a minimum number of full-time jobs for U.S. workers. It is a congressionally established program administered by U.S. Citizenship and Immigration Services (USCIS), and it represents the only major U.S. immigration category principally defined by investment rather than by employment or family relationship.</p>
    </div>
    <div class="card">
      <h3>Who Is EB-5 Best Suited For?</h3>
      <p>EB-5 is generally the most appropriate pathway for investors whose primary objective is U.S. permanent residence and who meet the capital and documentation requirements. It is particularly well-suited for investors from countries where employment-based visa backlogs are less pronounced, those who prefer a passive or regional center investment structure over active business management, and families prioritizing long-term U.S. stability and generational optionality.</p>
    </div>
    <div class="card">
      <h3>Permanent vs. Temporary Objectives</h3>
      <p>EB-5 is a permanent residence pathway — not a temporary visa. A successful EB-5 petition results in conditional permanent resident status, initially granted for two years, which is subsequently converted to full lawful permanent residence upon satisfaction of relevant conditions. Investors whose primary objective is temporary business presence or work authorization should consider the E-2 or other nonimmigrant alternatives discussed in this guide.</p>
    </div>
  </div>

  <hr class="section-rule">

  <div class="detail-block">
    <div class="detail-col">
      <h4>Investment Thresholds</h4>
      <ul class="detail-list">
        <li>The standard EB-5 investment minimum is set by regulation. As of current market guidance, the standard threshold is approximately $1,050,000 for non-TEA projects.</li>
        <li>For investments in Targeted Employment Areas (TEAs) — rural areas or high-unemployment zones — the commonly cited minimum is approximately $800,000.</li>
        <li>These thresholds are subject to periodic regulatory adjustment. All figures must be confirmed against current USCIS regulations at time of filing.</li>
        <li>All capital must be demonstrably "at risk" in the commercial enterprise and lawfully sourced — a fundamental requirement of the program.</li>
      </ul>
    </div>
    <div class="detail-col">
      <h4>Job Creation Requirement</h4>
      <ul class="detail-list">
        <li>Each EB-5 investor is generally required to demonstrate the creation of at least 10 full-time positions for qualifying U.S. workers.</li>
        <li>In direct investments, these are typically direct employees within the funded enterprise.</li>
        <li>In regional center investments, job creation may include indirect and induced economic employment, calculated through approved economic methodologies.</li>
        <li>Satisfying this requirement is a critical condition for the removal of conditions on residence and the path to unconditional permanent resident status.</li>
      </ul>
    </div>
  </div>

  <hr class="section-rule">

  <h4 style="font-family:var(--serif);font-size:22px;font-weight:400;color:var(--gold-lt);margin-bottom:1.5rem;">Direct Investment vs. Regional Center</h4>
  <div class="cards cards-dark" style="grid-template-columns:1fr 1fr;">
    <div class="card">
      <h3>Direct EB-5</h3>
      <p>The investor funds a commercial enterprise directly — typically a business they own or control. Active involvement in policy-making or managerial capacity is required. Job creation must be direct and documented through verifiable payroll records. This path offers greater operational control but places a higher documentary and management burden on the investor.</p>
    </div>
    <div class="card">
      <h3>Regional Center EB-5</h3>
      <p>The investor contributes capital to a USCIS-designated Regional Center — an approved pooled investment vehicle, typically funding real estate development or infrastructure. The investor takes a passive role; job creation may include indirect and induced employment. This is the most commonly utilized structure for international investors. Thorough due diligence on the regional center sponsor, project structure, and capital terms is essential.</p>
    </div>
  </div>

  <hr class="section-rule">

  <h4 style="font-family:var(--serif);font-size:22px;font-weight:400;color:var(--gold-lt);margin-bottom:2rem;">Typical EB-5 Process Stages</h4>
  <div class="steps">
    <div class="step" data-n="1">
      <h4>Legal Strategy &amp; Eligibility Assessment</h4>
      <p>Evaluate investor nationality, source-of-funds documentation, family objectives, and investment vehicle. Select direct or regional center approach. Retain immigration counsel and begin document compilation well in advance of filing.</p>
    </div>
    <div class="step" data-n="2">
      <h4>Source of Funds Documentation</h4>
      <p>Document the lawful origin of all EB-5 capital through banking records, tax filings, corporate records, and notarized evidence as applicable. This is typically the most documentation-intensive phase and should begin early in the process.</p>
    </div>
    <div class="step" data-n="3">
      <h4>Capital Investment &amp; I-526E Petition</h4>
      <p>Execute the qualifying investment. File Form I-526E (Immigrant Petition by Regional Center Investor) or I-526 (direct), demonstrating eligibility and qualifying investment through comprehensive supporting evidence.</p>
    </div>
    <div class="step" data-n="4">
      <h4>Consular Processing or Adjustment of Status</h4>
      <p>Depending on whether the investor is inside or outside the United States, proceed through immigrant visa processing at a U.S. consulate or file for adjustment of status domestically. Timing is subject to visa availability based on the investor's country of birth.</p>
    </div>
    <div class="step" data-n="5">
      <h4>Conditional Permanent Residence</h4>
      <p>Upon approval, the investor and qualifying family members receive conditional green cards, generally valid for two years. The investor must demonstrate that job creation conditions have been fulfilled before conditions are removed.</p>
    </div>
    <div class="step" data-n="6">
      <h4>I-829 Petition &amp; Unconditional Residence</h4>
      <p>File Form I-829 to remove conditions and obtain unconditional lawful permanent resident status — a full U.S. green card for the investor and eligible family members, with eventual eligibility for U.S. citizenship.</p>
    </div>
  </div>

  <hr class="section-rule">

  <div class="detail-block">
    <div class="detail-col">
      <h4>Key Advantages of EB-5</h4>
      <ul class="detail-list">
        <li>Direct path to U.S. permanent residence — no employer sponsor required</li>
        <li>Available to investors of virtually any nationality — no treaty country requirement</li>
        <li>Spouse and unmarried children under 21 are included as principal beneficiaries</li>
        <li>Passive investment option available via the regional center model</li>
        <li>Leads to eligibility for U.S. citizenship after the required lawful permanent residence period</li>
        <li>No specific education, age, or English language requirement for the investor</li>
      </ul>
    </div>
    <div class="detail-col">
      <h4>Key Risks &amp; Considerations</h4>
      <ul class="detail-list">
        <li>Capital is at risk — returns and capital preservation are not guaranteed by immigration law</li>
        <li>Processing timelines can be lengthy, particularly for investors born in high-demand countries subject to visa retrogression</li>
        <li>Source-of-funds scrutiny is rigorous — documentation complexity should not be underestimated</li>
        <li>Job creation conditions must be demonstrated, not merely projected</li>
        <li>Regional center sponsor due diligence is the investor's responsibility</li>
        <li>U.S. tax obligations arise upon receipt of lawful permanent resident status — pre-immigration tax planning is strongly advisable</li>
      </ul>
    </div>
  </div>

  <div class="highlight-box">
    <p><strong style="color:var(--gold-lt);">Important note on figures:</strong> Investment minimums and program requirements under the EB-5 program are governed by federal regulation and are subject to change. The amounts referenced in this brochure reflect current general market guidance and should be confirmed against applicable USCIS rules at the time of any filing. Nothing herein constitutes legal advice or a guarantee of immigration outcome.</p>
  </div>
</div>
</div><!-- /section-dark -->


<!-- ══ III. E-2 ══════════════════════════════════════════ -->
<section class="section" id="e2">
  <div class="section-header">
    <span class="section-number">Section III</span>
    <span class="rule-gold left"></span>
    <h2 class="section-h2">E-2 <em>Treaty Investor</em></h2>
    <p class="section-intro">A compelling nonimmigrant option for active investors from treaty countries — offering speed, renewability, and proportionate entry into the U.S. market.</p>
  </div>

  <div class="cards">
    <div class="card">
      <h3>What Is E-2?</h3>
      <p>The E-2 Treaty Investor visa is a nonimmigrant status available to nationals of countries that maintain qualifying treaties of commerce and navigation with the United States. It permits an investor to enter and work in the United States for the purpose of developing and directing a business in which they have made a substantial investment. E-2 is not a green card — but it offers a renewable, practical, and often more rapidly accessible entry point for active investors from qualifying nations.</p>
    </div>
    <div class="card">
      <h3>Key Distinction: Nonimmigrant Status</h3>
      <p>E-2 does not, by itself, lead to lawful permanent residence. E-2 holders must maintain nonimmigrant intent — they are present on a temporary basis for qualifying business purposes. While E-2 status can be renewed indefinitely as long as the qualifying enterprise remains operational, investors who ultimately seek permanent residence will typically need to pursue a separate pathway toward that objective.</p>
    </div>
    <div class="card">
      <h3>Treaty Country Nationality Requirement</h3>
      <p>E-2 eligibility is strictly limited to nationals of countries that have a qualifying bilateral investment or commerce treaty with the United States. The investor's nationality — not country of residence — is the controlling factor. Where a client holds dual nationality, treaty eligibility should be reviewed for each passport. Clients from non-treaty countries are not eligible for E-2 regardless of their place of business or domicile.</p>
    </div>
  </div>

  <hr class="section-rule">

  <div class="detail-block">
    <div class="detail-col">
      <h4>Substantial Investment — What It Means</h4>
      <ul class="detail-list">
        <li>There is no fixed statutory minimum investment amount for E-2. The governing standard is that the investment be "substantial" relative to the total cost of establishing or acquiring the enterprise.</li>
        <li>The investment must be committed and genuinely at risk — it cannot remain in escrow or be readily repatriated at the investor's discretion.</li>
        <li>Substantiality is assessed proportionally: a lower-cost business may require a higher percentage of committed capital to satisfy the standard.</li>
        <li>In practice, qualifying E-2 investments commonly range from approximately $100,000 to several million dollars depending on the enterprise, though the threshold is not determined by amount alone.</li>
        <li>The investment must be irrevocably committed before the visa is adjudicated.</li>
      </ul>
    </div>
    <div class="detail-col">
      <h4>The Active Business Requirement</h4>
      <ul class="detail-list">
        <li>E-2 requires investment in an active, real, and operational commercial enterprise — not a passive holding vehicle, dormant entity, or speculative financial instrument.</li>
        <li>A purely speculative investment, a real estate purchase without active development or management, or a holding company with no operational activity will generally not qualify.</li>
        <li>The enterprise must generate income beyond merely sustaining the investor — satisfying the "marginality" standard that the business has broader economic impact.</li>
        <li>The investor must actively direct and develop the enterprise; holding equity without substantive operational engagement is insufficient.</li>
      </ul>
    </div>
  </div>

  <hr class="section-rule">

  <div class="detail-block">
    <div class="detail-col">
      <h4>Key Advantages of E-2</h4>
      <ul class="detail-list">
        <li>No fixed minimum investment — proportionate and accessible for earlier-stage or smaller enterprises</li>
        <li>Processing timelines are typically significantly faster than EB-5</li>
        <li>E-2 status is renewable indefinitely as long as the qualifying enterprise remains active</li>
        <li>Spouse is generally eligible for employment authorization in the United States</li>
        <li>Children under 21 may accompany and access U.S. educational institutions</li>
        <li>Effective U.S. business and family platform while longer-term residency strategies are developed in parallel</li>
      </ul>
    </div>
    <div class="detail-col">
      <h4>Key Limitations of E-2</h4>
      <ul class="detail-list">
        <li>Unavailable to nationals of non-treaty countries — eligibility is strictly nationality-based</li>
        <li>Does not lead directly to permanent residence — a separate pathway is required for green card objectives</li>
        <li>Active, directed business engagement is required — passive investors do not qualify</li>
        <li>Business viability is essential to status continuity; enterprise failure places E-2 status at risk</li>
        <li>Years in E-2 status do not accrue toward U.S. citizenship eligibility</li>
        <li>Dependent children aging out at 21 require timely separate status planning</li>
      </ul>
    </div>
  </div>

  <div class="pull-quote">
    <p>"For the active entrepreneur who wants to build and operate in the United States — and whose nationality qualifies — E-2 often provides a faster and more proportionate entry point than any other pathway."</p>
  </div>

  <!-- ── TREATY COUNTRIES ──────────────────── -->
  <h4 style="font-family:var(--serif);font-size:24px;font-weight:400;color:var(--deep);margin-bottom:.5rem;">E-2 Treaty Countries</h4>
  <p style="font-size:14px;color:var(--muted);margin-bottom:.25rem;max-width:640px;line-height:1.8;">The following is a selection of the most prominent nationalities that maintain E-2 treaty eligibility with the United States. This list is illustrative — not exhaustive — and treaty eligibility should be confirmed with counsel based on your specific nationality at the time of application.</p>

  <div class="treaty-grid">
    <div class="treaty-item"><span class="treaty-flag">🇬🇧</span><span class="treaty-name">United Kingdom</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇩🇪</span><span class="treaty-name">Germany</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇫🇷</span><span class="treaty-name">France</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇯🇵</span><span class="treaty-name">Japan</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇰🇷</span><span class="treaty-name">South Korea</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇮🇹</span><span class="treaty-name">Italy</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇪🇸</span><span class="treaty-name">Spain</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇨🇭</span><span class="treaty-name">Switzerland</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇳🇱</span><span class="treaty-name">Netherlands</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇦🇺</span><span class="treaty-name">Australia</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇧🇪</span><span class="treaty-name">Belgium</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇸🇪</span><span class="treaty-name">Sweden</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇦🇹</span><span class="treaty-name">Austria</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇳🇴</span><span class="treaty-name">Norway</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇩🇰</span><span class="treaty-name">Denmark</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇫🇮</span><span class="treaty-name">Finland</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇹🇷</span><span class="treaty-name">Turkey</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇲🇽</span><span class="treaty-name">Mexico</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇨🇴</span><span class="treaty-name">Colombia</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇵🇭</span><span class="treaty-name">Philippines</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇮🇱</span><span class="treaty-name">Israel</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇵🇰</span><span class="treaty-name">Pakistan</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇹🇭</span><span class="treaty-name">Thailand</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇵🇹</span><span class="treaty-name">Portugal</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇬🇷</span><span class="treaty-name">Greece</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇮🇪</span><span class="treaty-name">Ireland</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇸🇬</span><span class="treaty-name">Singapore</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇿🇦</span><span class="treaty-name">South Africa</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇧🇩</span><span class="treaty-name">Bangladesh</span></div>
    <div class="treaty-item"><span class="treaty-flag">🇷🇴</span><span class="treaty-name">Romania</span></div>
  </div>

 
  <hr class="section-rule">

  <h4 style="font-family:var(--serif);font-size:22px;font-weight:400;color:var(--deep);margin-bottom:1.5rem;">Ideal E-2 Client Profiles</h4>
  <div class="cards" style="grid-template-columns:repeat(auto-fit,minmax(220px,1fr));">
    <div class="card">
      <h3>The Active Operator</h3>
      <p>A business owner from a treaty country who intends to directly manage and grow a U.S.-based enterprise — whether launching a new venture, acquiring an existing U.S. business, or expanding a home-country operation into the American market.</p>
    </div>
    <div class="card">
      <h3>The Franchise Investor</h3>
      <p>An investor acquiring a qualifying U.S. franchise concept. Franchise structures are frequently used in E-2 applications and can satisfy both the substantiality and active management requirements when properly structured and documented.</p>
    </div>
    <div class="card">
      <h3>The Platform Builder</h3>
      <p>An entrepreneur or founder who wants to establish a U.S. operational presence as a strategic foundation — using E-2 as the initial platform while concurrently developing a longer-term permanent residence strategy in parallel.</p>
    </div>
    <div class="card">
      <h3>The Relocating Family</h3>
      <p>A family principal who values the flexibility of an E-2 platform for U.S. presence, spouse employment authorization, and educational access for children, while retaining optionality for future permanent residence planning.</p>
    </div>
  </div>
</section>


<!-- ══ IV. COMPARISON TABLE ══════════════════════════════ -->
<div class="section-dark" id="compare">
<div class="section-inner">
  <div class="section-header">
    <span class="section-number">Section IV</span>
    <span class="rule-gold left"></span>
    <h2 class="section-h2">EB-5 vs. E-2 — <em>Side by Side</em></h2>
    <p class="section-intro">A high-level comparison of the two primary U.S. investment immigration pathways. All information is general and subject to current government regulations.</p>
  </div>

  <div class="table-wrap">
    <table>
      <thead>
        <tr>
          <th>Category</th>
          <th>EB-5 Immigrant Investor</th>
          <th>E-2 Treaty Investor</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Status Type</td>
          <td><span class="badge badge-green">Permanent Residence (Green Card)</span></td>
          <td><span class="badge badge-amber">Nonimmigrant — Renewable</span></td>
        </tr>
        <tr>
          <td>Nationality Restriction</td>
          <td>None — open to all nationalities</td>
          <td>Treaty country nationals only</td>
        </tr>
        <tr>
          <td>Typical Investment</td>
          <td>~$800K (TEA) to ~$1.05M+ (non-TEA); at risk in qualifying enterprise</td>
          <td>No fixed minimum; "substantial" relative to business cost; at risk and committed</td>
        </tr>
        <tr>
          <td>Business Involvement</td>
          <td>Passive permitted (regional center); active management required for direct EB-5</td>
          <td>Active direction and development of the enterprise is required — passive investment does not qualify</td>
        </tr>
        <tr>
          <td>Job Creation</td>
          <td>Minimum 10 full-time U.S. jobs required (direct or indirect)</td>
          <td>No minimum job creation requirement; business must not be "marginal"</td>
        </tr>
        <tr>
          <td>Leads to Green Card?</td>
          <td>Yes — directly</td>
          <td>Not directly — requires separate permanent residence strategy</td>
        </tr>
        <tr>
          <td>Spouse Work Authorization</td>
          <td>Authorized as lawful permanent resident upon approval</td>
          <td>Spouse generally eligible for separate employment authorization</td>
        </tr>
        <tr>
          <td>Processing Timeline</td>
          <td>Typically longer — subject to visa availability by country of birth</td>
          <td>Generally faster — often adjudicated at consulate within weeks to months</td>
        </tr>
        <tr>
          <td>Path to Citizenship</td>
          <td>Yes — after required lawful permanent residence period</td>
          <td>No — E-2 years do not count toward naturalization</td>
        </tr>
        <tr>
          <td>Source of Funds Review</td>
          <td>Rigorous — full lawful source documentation required for all invested capital</td>
          <td>Required — documentation of lawful investment source is expected</td>
        </tr>
        <tr>
          <td>Best For</td>
          <td>Investors of any nationality seeking permanent U.S. residence through qualifying capital</td>
          <td>Active entrepreneurs from treaty countries seeking agile U.S. market entry</td>
        </tr>
      </tbody>
    </table>
  </div>
  <p style="margin-top:1.25rem;font-size:12px;color:var(--muted);line-height:1.75;"><em>This comparison is for general orientation only. It does not constitute legal advice. Immigration eligibility, processing timelines, and investment thresholds are subject to U.S. government regulations and may change. Consult qualified immigration counsel before taking any action.</em></p>
</div>
</div>


<!-- ══ V. HOW OUR FIRM HELPS ══════════════════════════════ -->
<section class="section" id="firm" style="background:var(--paper);">
  <div class="section-header">
    <span class="section-number">Section V</span>
    <span class="rule-gold left"></span>
    <h2 class="section-h2">How <em>Ramseyer &amp; Associates</em> Helps</h2>  </div>
    <p class="section-intro">We serve internationally mobile investors, entrepreneurs, and families as a strategic immigration partner — not a paperwork processor. Our mandate is to help clients make well-informed decisions and execute them with precision and discretion.</p>
  </div>

  <div class="cards" style="grid-template-columns:repeat(auto-fit,minmax(260px,1fr));">
    <div class="card">
      <h3>Strategic Visa Selection</h3>
      <p>We begin every engagement by understanding your objectives — not by defaulting to the most common solution. Nationality, investment capacity, business model, family structure, and long-term residence goals are all evaluated before a pathway is recommended.</p>
    </div>
    <div class="card">
      <h3>Eligibility &amp; Risk Assessment</h3>
      <p>A preliminary eligibility analysis helps clients understand where they stand before committing time or capital. We identify potential obstacles early and provide honest guidance on the realistic likelihood and timeline of each available pathway.</p>
    </div>
    <div class="card">
      <h3>Source-of-Funds Planning</h3>
      <p>Documentation of lawful capital origin is one of the most consequential and underestimated aspects of investment immigration. We help clients structure and compile a coherent, government-ready source-of-funds narrative well in advance of any filing.</p>
    </div>
    <div class="card">
      <h3>Investment Structuring Coordination</h3>
      <p>Immigration implications should inform corporate and investment structure decisions — not be addressed after the fact. We coordinate closely with client advisors, corporate counsel, and tax professionals to ensure structures are immigration-compatible from the outset.</p>
    </div>
    <div class="card">
      <h3>Filing &amp; Case Management</h3>
      <p>We manage petitions, applications, and supporting documentation from preparation through adjudication. Clients receive proactive updates on processing changes and direct attorney access throughout the entire process.</p>
    </div>
    <div class="card">
      <h3>Family &amp; Generational Planning</h3>
      <p>Immigration strategy rarely concerns only the principal investor. We incorporate spouse employment authorization, children's educational pathways, dependent status planning, and long-term citizenship optionality into every relevant engagement.</p>
    </div>
    <div class="card">
      <h3>Long-Term Pathway Development</h3>
      <p>The first visa is rarely the final chapter. We advise on the pathway beyond initial status — helping clients understand how their current immigration platform positions them for permanent residence, citizenship eligibility, and multi-generational U.S. presence.</p>
    </div>
    </div>
    </div>
    </div>
    </div>
    <div class="highlight-box">
    <p><strong style="color:var(--gold-lt);">A note on our approach:</strong> We do not guarantee immigration outcomes. No ethical attorney can. What we commit to is rigorous preparation, honest assessment, transparent communication, and the highest standard of legal judgment in our field. Our clients are making decisions that affect their families and their capital. We take that responsibility seriously. — <em style="color:var(--gold);">Ramseyer &amp; Associates PC, Attorneys at Law</em></p>
  </div>
</section>



<!-- ══ CTA ══════════════════════════════════════════════ -->
<section id="cta">
  <div class="cta-inner">
    <span class="label" style="display:block;margin-bottom:1.5rem;">Schedule a Confidential Consultation</span>
    <h2 class="cta-h2">Begin with a<br><em>Strategic Conversation</em></h2>
    <p class="cta-body">
      The decision to pursue U.S. immigration is rarely straightforward — and it should never be made without qualified guidance. Ramseyer &amp; Associates PC offers a structured, confidential preliminary consultation designed to evaluate your profile, identify applicable pathways, and provide an honest, clear-eyed assessment of your options before any commitment is made.
      <br><br>
      Consultations are available in person at our Manhattan office — 14 Penn Plaza, 34th Street, New York — or by secure video conference for internationally based clients. Introductions through our Dubai advisory partner network are welcomed and managed with complete discretion.
    </p>
    <a href="mailto:info@ramseyerattorneys.com?subject=Investor%20Immigration%20Consultation%20Request&body=Dear%20Ramseyer%20%26%20Associates%2C%0A%0AI%20would%20like%20to%20request%20a%20confidential%20consultation%20regarding%20U.S.%20investment%20immigration%20options." class="btn-gold">Request a Private Consultation</a>
    <p class="cta-note">All communications handled under attorney-client privilege &nbsp;·&nbsp; No commitment required &nbsp;·&nbsp; International video consultations available</p>
  </div>
</section>


<!-- ══ FOOTER ════════════════════════════════════════════ -->
<footer>
  <div>
    <div class="footer-logo">
      <img src="https://img1.wsimg.com/isteam/ip/94b29341-0380-49bf-944f-0d379ab4e949/logo-horizontal-transparent.png/:/rs=h:170,cg:true,m/qt=q:95" alt="Ramseyer & Associates PC">
    </div>
    <div style="margin-top:.75rem;line-height:2;">
      <strong style="color:var(--muted);font-weight:400;">Ramseyer &amp; Associates PC (Attorneys at Law)</strong><br>
      14 Penn Plaza, 34th Street, New York, NY &nbsp;·&nbsp; Founded 2002<br>
      <a href="mailto:info@ramseyerattorneys.com">info@ramseyerattorneys.com</a> &nbsp;·&nbsp;
      <a href="tel:13477124488">+1 347 712 4488</a> &nbsp;·&nbsp;
      <a href="https://ramseyerattorneys.com" target="_blank">ramseyerattorneys.com</a>
    </div>
  </div>
  <div style="text-align:right;line-height:2;max-width:380px;">
    This brochure is prepared for general informational and business development purposes only. It does not constitute legal advice and does not establish an attorney-client relationship. Immigration law is subject to change. All figures and thresholds should be confirmed against current USCIS regulations at the time of filing.<br>
    © 2025 Ramseyer &amp; Associates PC · All Rights Reserved.
  </div>
</footer>

</body>
</html>

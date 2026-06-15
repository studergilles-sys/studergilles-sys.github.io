<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<title>FORGE/37 — Programme 4 semaines</title>

<!-- Mode "app" sur écran d'accueil iOS -->
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="FORGE/37">
<meta name="mobile-web-app-capable" content="yes">
<meta name="theme-color" content="#13161B">
<link rel="apple-touch-icon" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALQAAAC0CAIAAACyr5FlAAAFWklEQVR4nO3dPZIbNxRFYYxLO5BKgRQo9FYcKNU2vBhtQ6kDb0WhEkVehANUobqG88juJoB3L/p8mUpjEkSffs0/jV/ef/xcgLf8kb0A6CIOhIgDIeJAiDgQIg6EiAMh4kCIOBAiDoSIAyHiQIg4ECIOhIgDIeJAiDgQIg6EiAOhd9kLSPbft0/3f+DDj99zViLo5YJfMH4YRORqoVwojtNN3LpIJevH0bGJW2tXsvgT0qFlTLj9XMtOjsmHbckRsubkmH9CLzlCVpsc6QdppRGy1ORIL0NkDb2sE4fOUdFZyZMWiUPteKit55wV4tA8EpqrOmTgE9Kv3//d/vGfv/8acS/ix8D6+emQOF5lsdU3EfEyKt8++n8qe6eM+reDRshpdw6eRXzjdJ4c98touvTx5JE7dELPvC8dPePYWUb1ZB/PHK3ThyrlThNd68s+Tx6h+p9f51rT7aXsobFx4ue3zh2eXufuudtxTMrvfY4Tu/zhx+++U/3cDdr14RfHUeMu9o5PIw5ZPw6cZhbH0ck8+uQ+evteVxbLl7I7t3ja2FdbTy+WL2W9XlLaNdEYv0PavFnJ5ENyuwbfJpr+H7w97GPcZyvbI5QYxwJZVN6fymIo++9zYJzVvn2Ojsze58BMxIEQcSBEHAgRB0LEgZDlZytdHPpoZpk3PQ+50Psc/Nqno9aPg1/7dNqycfCbfZ63WhzpX/JYqZJ14kjPYmuNRFaIQyqLLfdE7N/nkC2jaK9tD+PJYbT1piPEdXIYlVHcVtv4TQ7Tja68RojZ5LAuo7it3ykOr52NGD0KmziM9vQhl8di8JzjzFZ++fPBD/z6eW4xfYk/BVGP40AZD4OIpIai3Id0HHvLOJ3FVl4isn2Yf9mnSxbbm9K43IjQnRwPxkbHLG5NT0RzeIi+WsksY8Lt39B8/aI4Oe7t1OTDNneEqM0PuckhVMb0e1SbH3JxhOaXkXu/ArTiUDt15pPaAaE4tC4oefeu04dQHCGFwa6whulU4tA5XRSI7IZEHLoXlK3rXVwk4oCm/DgUThFN6TuTH8c9OteUSm09gyXHkX5yiMvdH+3JgVTEgVBmHFxT9kjcJSYHQsSBUFocu6al2jc6k9aTdWVhciBEHAjlxHFgTupcWVJXknJlYXIg5BCHwvBQWMN0DnGU7GNzyTKKTRzIkBDHyedWWaevzNiY/5zUanLMP04yZaRw+1f29WhN+NLNtbOorCZHM/rIUUYpxW9yNINGCFls2MZRdUyELG6Yx1E9mQhZBJaIo9oeY5PfJihuoTi2OPY9eL5awRTEgRBxIEQcCBEHQsSBUEIcar9t08X8fWNyIEQcCBEHQsSBUE4cPCc9KmXHmBwIEQdCaXFwZdkva6+YHAgRB0KZcXBl2SNxl5gcCBEHQslxcGW5L3d/mBwI5cfB8Iik70x+HJAlEUf6KSJIYU8k4igae6FDZDdU4oAgoThETpd0OvsgFEdR2pcsUjugFQekyMUhdepMpvbY5eIoens0h+CjVoyjSO7UUJqPVzSOorpfI8g+Ut04kE46DtlTqiPlxygdR9Heu+eJP7qX9x8/Z69hl8X+D8XiWVTqk6Ox2M2dXB6LTRzFZ0/vM3oUTnEUq519k9f6bZ5zvGL3FMQri8pscjRee+212sZ1cjTiI8Q0i8p1cjTKu6+8tj3sJ0cjNULcs6jWiaNKT2SNLKrV4mgmV7JSE82ycTRDK1myiWb9OJqOlazdRHOhOF451MpFanjlunHgIfv3OTAOcSBEHAgRB0LEgRBxIEQcCBEHQsSBEHEgRBwIEQdCxIEQcSBEHAgRB0LEgRBxIPQ/AIGOc2ghPTkAAAAASUVORK5CYII=">
<link rel="icon" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAALQAAAC0CAIAAACyr5FlAAAFWklEQVR4nO3dPZIbNxRFYYxLO5BKgRQo9FYcKNU2vBhtQ6kDb0WhEkVehANUobqG88juJoB3L/p8mUpjEkSffs0/jV/ef/xcgLf8kb0A6CIOhIgDIeJAiDgQIg6EiAMh4kCIOBAiDoSIAyHiQIg4ECIOhIgDIeJAiDgQIg6EiAOhd9kLSPbft0/3f+DDj99zViLo5YJfMH4YRORqoVwojtNN3LpIJevH0bGJW2tXsvgT0qFlTLj9XMtOjsmHbckRsubkmH9CLzlCVpsc6QdppRGy1ORIL0NkDb2sE4fOUdFZyZMWiUPteKit55wV4tA8EpqrOmTgE9Kv3//d/vGfv/8acS/ix8D6+emQOF5lsdU3EfEyKt8++n8qe6eM+reDRshpdw6eRXzjdJ4c98touvTx5JE7dELPvC8dPePYWUb1ZB/PHK3ThyrlThNd68s+Tx6h+p9f51rT7aXsobFx4ue3zh2eXufuudtxTMrvfY4Tu/zhx+++U/3cDdr14RfHUeMu9o5PIw5ZPw6cZhbH0ck8+uQ+evteVxbLl7I7t3ja2FdbTy+WL2W9XlLaNdEYv0PavFnJ5ENyuwbfJpr+H7w97GPcZyvbI5QYxwJZVN6fymIo++9zYJzVvn2Ojsze58BMxIEQcSBEHAgRB0LEgZDlZytdHPpoZpk3PQ+50Psc/Nqno9aPg1/7dNqycfCbfZ63WhzpX/JYqZJ14kjPYmuNRFaIQyqLLfdE7N/nkC2jaK9tD+PJYbT1piPEdXIYlVHcVtv4TQ7Tja68RojZ5LAuo7it3ykOr52NGD0KmziM9vQhl8di8JzjzFZ++fPBD/z6eW4xfYk/BVGP40AZD4OIpIai3Id0HHvLOJ3FVl4isn2Yf9mnSxbbm9K43IjQnRwPxkbHLG5NT0RzeIi+WsksY8Lt39B8/aI4Oe7t1OTDNneEqM0PuckhVMb0e1SbH3JxhOaXkXu/ArTiUDt15pPaAaE4tC4oefeu04dQHCGFwa6whulU4tA5XRSI7IZEHLoXlK3rXVwk4oCm/DgUThFN6TuTH8c9OteUSm09gyXHkX5yiMvdH+3JgVTEgVBmHFxT9kjcJSYHQsSBUFocu6al2jc6k9aTdWVhciBEHAjlxHFgTupcWVJXknJlYXIg5BCHwvBQWMN0DnGU7GNzyTKKTRzIkBDHyedWWaevzNiY/5zUanLMP04yZaRw+1f29WhN+NLNtbOorCZHM/rIUUYpxW9yNINGCFls2MZRdUyELG6Yx1E9mQhZBJaIo9oeY5PfJihuoTi2OPY9eL5awRTEgRBxIEQcCBEHQsSBUEIcar9t08X8fWNyIEQcCBEHQsSBUE4cPCc9KmXHmBwIEQdCaXFwZdkva6+YHAgRB0KZcXBl2SNxl5gcCBEHQslxcGW5L3d/mBwI5cfB8Iik70x+HJAlEUf6KSJIYU8k4igae6FDZDdU4oAgoThETpd0OvsgFEdR2pcsUjugFQekyMUhdepMpvbY5eIoens0h+CjVoyjSO7UUJqPVzSOorpfI8g+Ut04kE46DtlTqiPlxygdR9Heu+eJP7qX9x8/Z69hl8X+D8XiWVTqk6Ox2M2dXB6LTRzFZ0/vM3oUTnEUq519k9f6bZ5zvGL3FMQri8pscjRee+212sZ1cjTiI8Q0i8p1cjTKu6+8tj3sJ0cjNULcs6jWiaNKT2SNLKrV4mgmV7JSE82ycTRDK1myiWb9OJqOlazdRHOhOF451MpFanjlunHgIfv3OTAOcSBEHAgRB0LEgRBxIEQcCBEHQsSBEHEgRBwIEQdCxIEQcSBEHAgRB0LEgRBxIPQ/AIGOc2ghPTkAAAAASUVORK5CYII=">
<style>
  :root{
    --bg:#13161B;
    --bg-elev:#191D24;
    --surface:#1F242C;
    --surface-2:#2A313B;
    --line:#323A45;
    --text:#ECEAE5;
    --text-dim:#9AA4AF;
    --accent:#FF6B35;
    --accent-soft:#FF6B3522;
    --accent-2:#5FA8D3;
    --success:#4ADE80;
    --warn:#FFD166;
    --radius:16px;
    --radius-sm:10px;
    --nav-h:64px;
  }
  *{box-sizing:border-box;}
  html,body{margin:0;padding:0;}
  body{
    background:var(--bg);
    color:var(--text);
    font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
    -webkit-font-smoothing:antialiased;
    min-height:100vh;
  }
  .display{
    font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
    font-weight:800;
    text-transform:uppercase;
    letter-spacing:0.06em;
    font-stretch:condensed;
  }
  #app{
    max-width:520px;
    margin:0 auto;
    min-height:100vh;
    display:flex;
    flex-direction:column;
    position:relative;
  }
  /* ---------- HEADER ---------- */
  header.topbar{
    position:sticky; top:0; z-index:20;
    background:linear-gradient(180deg,var(--bg) 70%, transparent);
    padding:calc(18px + env(safe-area-inset-top)) 18px 8px;
    display:flex; align-items:center; justify-content:space-between;
  }
  .brand{
    display:flex; align-items:baseline; gap:8px;
  }
  .brand .mark{
    color:var(--accent);
    font-size:22px;
  }
  .brand .name{
    font-size:20px;
    letter-spacing:0.12em;
  }
  .brand .slash{ color:var(--text-dim); font-weight:400; }
  .week-pill{
    background:var(--surface);
    border:1px solid var(--line);
    border-radius:999px;
    padding:6px 14px;
    font-size:12px;
    color:var(--text-dim);
    letter-spacing:0.08em;
    text-transform:uppercase;
  }
  .week-pill b{ color:var(--accent); }

  /* ---------- MAIN ---------- */
  main{
    flex:1;
    padding:4px 18px calc(var(--nav-h) + env(safe-area-inset-bottom) + 28px);
  }
  .view{ display:none; animation:fade .25s ease; }
  .view.active{ display:block; }
  @keyframes fade{ from{opacity:0; transform:translateY(6px);} to{opacity:1; transform:translateY(0);} }

  h1.page-title{
    font-size:26px;
    margin:6px 0 4px;
    letter-spacing:0.04em;
  }
  .subtitle{
    color:var(--text-dim);
    font-size:14px;
    line-height:1.5;
    margin:0 0 18px;
  }
  .card{
    background:var(--surface);
    border:1px solid var(--line);
    border-radius:var(--radius);
    padding:16px;
    margin-bottom:14px;
  }
  .card.accent-edge{ border-left:3px solid var(--accent); }

  /* ---------- DASHBOARD ---------- */
  .progress-grid{
    display:grid; grid-template-columns:repeat(6,1fr); gap:6px; margin:10px 0 16px;
  }
  .progress-cell{
    aspect-ratio:1; border-radius:8px; background:var(--surface-2);
    display:flex; align-items:center; justify-content:center;
    font-size:11px; color:var(--text-dim); border:1px solid var(--line);
    position:relative;
  }
  .progress-cell.done{ background:var(--accent-soft); border-color:var(--accent); color:var(--accent); }
  .progress-cell.next{ border-color:var(--accent-2); color:var(--accent-2); }
  .stat-row{ display:flex; gap:10px; margin:10px 0 4px; }
  .stat-box{
    flex:1; background:var(--surface-2); border-radius:var(--radius-sm);
    padding:12px; text-align:center;
  }
  .stat-box .num{ font-size:24px; font-weight:800; color:var(--accent); }
  .stat-box .lab{ font-size:11px; color:var(--text-dim); text-transform:uppercase; letter-spacing:0.06em; margin-top:2px; }

  .btn{
    display:inline-flex; align-items:center; justify-content:center; gap:8px;
    background:var(--accent); color:#1A1006; border:none;
    font-weight:700; font-size:15px; letter-spacing:0.03em;
    padding:14px 20px; border-radius:var(--radius-sm);
    cursor:pointer; width:100%; transition:transform .12s, opacity .12s;
    text-transform:uppercase;
  }
  .btn:active{ transform:scale(0.98); }
  .btn.secondary{
    background:transparent; color:var(--text); border:1px solid var(--line);
  }
  .btn.ghost{
    background:transparent; color:var(--accent-2); border:1px solid var(--accent-2);
  }
  .btn.small{ padding:9px 14px; font-size:12px; width:auto; }
  .btn:disabled{ opacity:0.4; cursor:not-allowed; }

  .exercise-preview-list{ display:flex; flex-direction:column; gap:8px; margin-top:10px; }
  .exercise-preview{
    display:flex; align-items:center; gap:12px;
    background:var(--surface-2); border-radius:var(--radius-sm); padding:8px 12px;
  }
  .exercise-preview .mini-fig{ width:40px; height:40px; flex:none; }
  .exercise-preview .ep-info{ flex:1; }
  .exercise-preview .ep-name{ font-size:14px; font-weight:600; }
  .exercise-preview .ep-target{ font-size:12px; color:var(--text-dim); }

  /* ---------- FIGURE / SVG ANIMATION ---------- */
  .figure-stage{
    position:relative; width:100%; aspect-ratio:1/1; max-height:240px;
    background:
      linear-gradient(var(--bg-elev) 0 0) padding-box,
      repeating-linear-gradient(0deg, var(--line) 0 1px, transparent 1px 20px),
      repeating-linear-gradient(90deg, var(--line) 0 1px, transparent 1px 20px);
    background-color:var(--bg-elev);
    border-radius:var(--radius);
    border:1px solid var(--line);
    overflow:hidden;
  }
  .figure-stage svg{
    position:absolute; inset:8%;
    opacity:0; transition:opacity .55s ease;
  }
  .figure-stage svg.show{ opacity:1; }
  .fig-line{ fill:none; stroke:var(--accent); stroke-width:4; stroke-linecap:round; stroke-linejoin:round; }
  .fig-head{ fill:none; stroke:var(--accent); stroke-width:4; }
  .fig-kb circle{ fill:var(--accent-2); opacity:.9; }
  .fig-kb path{ fill:none; stroke:var(--accent-2); stroke-width:4; }
  .mini-fig svg{ position:relative; inset:auto; opacity:1; width:100%; height:100%; }
  .mini-fig .fig-line, .mini-fig .fig-head{ stroke-width:6; }
  .mini-fig .fig-kb path{ stroke-width:6; }

  /* ---------- WORKOUT PLAYER ---------- */
  .player-wrap{ display:flex; flex-direction:column; gap:14px; }
  .player-phase{
    text-align:center; font-size:13px; letter-spacing:0.18em; text-transform:uppercase;
    color:var(--text-dim);
  }
  .player-phase.work{ color:var(--accent); }
  .player-phase.rest{ color:var(--accent-2); }
  .player-exname{ text-align:center; font-size:24px; margin:2px 0 0; }
  .player-target{ text-align:center; color:var(--text-dim); font-size:14px; margin-bottom:4px; }
  .player-note{ text-align:center; color:var(--warn); font-size:12px; min-height:16px; }
  .timer-wrap{ display:flex; justify-content:center; align-items:center; margin:6px 0; }
  .timer-ring{ position:relative; width:140px; height:140px; }
  .timer-ring svg{ transform:rotate(-90deg); }
  .timer-ring .track{ fill:none; stroke:var(--surface-2); stroke-width:8; }
  .timer-ring .progress{ fill:none; stroke:var(--accent); stroke-width:8; stroke-linecap:round; transition:stroke-dashoffset .25s linear; }
  .timer-ring.rest .progress{ stroke:var(--accent-2); }
  .timer-num{
    position:absolute; inset:0; display:flex; align-items:center; justify-content:center;
    font-size:38px; font-weight:800;
  }
  .round-indicator{ text-align:center; color:var(--text-dim); font-size:12px; letter-spacing:0.1em; text-transform:uppercase; }
  .player-controls{ display:flex; gap:10px; }
  .queue-strip{
    display:flex; gap:6px; overflow-x:auto; padding:4px 0 2px;
  }
  .queue-dot{
    flex:none; width:10px; height:10px; border-radius:50%; background:var(--surface-2); border:1px solid var(--line);
  }
  .queue-dot.done{ background:var(--accent); border-color:var(--accent); }
  .queue-dot.cur{ background:var(--accent-2); border-color:var(--accent-2); }

  /* ---------- HISTORY ---------- */
  .hist-item{
    display:flex; align-items:center; gap:12px; padding:10px 0; border-bottom:1px solid var(--line);
  }
  .hist-item:last-child{ border-bottom:none; }
  .hist-date{ width:54px; text-align:center; }
  .hist-date .d{ font-size:18px; font-weight:800; line-height:1; }
  .hist-date .m{ font-size:10px; color:var(--text-dim); text-transform:uppercase; letter-spacing:0.08em; }
  .hist-info{ flex:1; }
  .hist-info .ht{ font-size:14px; font-weight:600; }
  .hist-info .hs{ font-size:12px; color:var(--text-dim); }
  .hist-diff{
    display:flex; gap:2px;
  }
  .hist-diff span{ width:6px; height:14px; border-radius:2px; background:var(--surface-2); }
  .hist-diff span.on{ background:var(--accent); }

  .bar-chart{ display:flex; align-items:flex-end; gap:6px; height:90px; margin-top:8px; }
  .bar{ flex:1; background:var(--surface-2); border-radius:4px 4px 0 0; position:relative; min-height:4px; }
  .bar.filled{ background:var(--accent); }
  .bar-label{ display:flex; gap:6px; margin-top:4px; }
  .bar-label span{ flex:1; text-align:center; font-size:10px; color:var(--text-dim); }

  /* ---------- COACH ---------- */
  .coach-msg{
    background:var(--surface); border:1px solid var(--line); border-left:3px solid var(--accent-2);
    border-radius:var(--radius); padding:14px; margin-bottom:12px; font-size:14px; line-height:1.6;
  }
  .coach-msg .tag{
    display:inline-block; font-size:10px; letter-spacing:0.12em; text-transform:uppercase;
    color:var(--accent-2); margin-bottom:6px;
  }
  textarea, input[type=text], input[type=password]{
    width:100%; background:var(--surface-2); border:1px solid var(--line); color:var(--text);
    border-radius:var(--radius-sm); padding:12px; font-size:14px; font-family:inherit;
  }
  textarea{ min-height:80px; resize:vertical; }
  label.field-label{ display:block; font-size:12px; color:var(--text-dim); margin-bottom:6px; text-transform:uppercase; letter-spacing:0.08em; }
  .field{ margin-bottom:14px; }

  /* ---------- LOG / RATING ---------- */
  .rating-row{ display:flex; gap:8px; margin:10px 0; }
  .rating-row button{
    flex:1; padding:12px 0; border-radius:var(--radius-sm); border:1px solid var(--line);
    background:var(--surface-2); color:var(--text); font-weight:700; cursor:pointer; font-size:16px;
  }
  .rating-row button.sel{ background:var(--accent); color:#1A1006; border-color:var(--accent); }

  /* ---------- NAV ---------- */
  nav.tabbar{
    position:fixed; bottom:0; left:0; right:0; height:calc(var(--nav-h) + env(safe-area-inset-bottom));
    padding-bottom:env(safe-area-inset-bottom);
    background:rgba(25,29,36,0.92); backdrop-filter:blur(10px);
    border-top:1px solid var(--line);
    display:flex; justify-content:center; z-index:30;
  }
  nav.tabbar .inner{
    max-width:520px; width:100%; display:flex;
  }
  nav.tabbar button{
    flex:1; background:none; border:none; color:var(--text-dim);
    display:flex; flex-direction:column; align-items:center; justify-content:center; gap:3px;
    font-size:10px; letter-spacing:0.06em; text-transform:uppercase; cursor:pointer; padding:6px 0;
  }
  nav.tabbar button.active{ color:var(--accent); }
  nav.tabbar button svg{ width:20px; height:20px; }

  details.help{ margin-top:8px; }
  details.help summary{ cursor:pointer; color:var(--accent-2); font-size:13px; }
  pre.code-block{
    background:var(--bg-elev); border:1px solid var(--line); border-radius:var(--radius-sm);
    padding:12px; font-size:11px; overflow-x:auto; color:var(--text-dim); line-height:1.5;
  }
  .toast{
    position:fixed; bottom:calc(var(--nav-h) + env(safe-area-inset-bottom) + 14px); left:50%; transform:translateX(-50%) translateY(20px);
    background:var(--surface-2); border:1px solid var(--accent); color:var(--text);
    padding:10px 18px; border-radius:999px; font-size:13px; opacity:0; transition:all .3s; pointer-events:none; z-index:50;
    white-space:nowrap;
  }
  .toast.show{ opacity:1; transform:translateX(-50%) translateY(0); }
  .muscle-tags{ display:flex; gap:6px; flex-wrap:wrap; margin-top:6px; }
  .muscle-tags span{
    font-size:11px; background:var(--surface-2); border-radius:999px; padding:3px 10px; color:var(--text-dim);
  }
  hr.sep{ border:none; border-top:1px solid var(--line); margin:18px 0; }
</style>
</head>
<body>
<div id="app">

  <header class="topbar">
    <div class="brand">
      <span class="mark">●</span>
      <span class="name display">FORGE<span class="slash">/</span>37</span>
    </div>
    <div class="week-pill" id="weekPill">Semaine <b>1</b> · 1/12</div>
  </header>

  <main>

    <!-- DASHBOARD -->
    <section class="view active" id="view-dashboard">
      <h1 class="page-title display">Programme</h1>
      <p class="subtitle">4 semaines · 3 séances/semaine · 25 min max · calisthénie + kettlebell + gainage.
      Objectif réaliste : en 1 mois on ne « sculpte » pas un physique, mais avec une régularité de 12 séances,
      un tonus visible et une meilleure définition musculaire sont tout à fait atteignables — surtout combinés
      à des apports suffisants en protéines.</p>

      <div class="card">
        <div style="display:flex;justify-content:space-between;align-items:baseline;">
          <strong style="font-size:14px;letter-spacing:.08em;text-transform:uppercase;color:var(--text-dim);">Progression</strong>
          <span id="progressCount" style="color:var(--accent);font-weight:800;">0/12</span>
        </div>
        <div class="progress-grid" id="progressGrid"></div>
        <div class="stat-row">
          <div class="stat-box"><div class="num" id="statStreak">0</div><div class="lab">Séries de séances</div></div>
          <div class="stat-box"><div class="num" id="statTotalMin">0</div><div class="lab">Min cumulées</div></div>
          <div class="stat-box"><div class="num" id="statAvgDiff">–</div><div class="lab">Difficulté moy.</div></div>
        </div>
      </div>

      <div class="card accent-edge" id="nextSessionCard">
        <strong style="font-size:13px;letter-spacing:.1em;text-transform:uppercase;color:var(--text-dim);">Prochaine séance</strong>
        <h2 class="display" id="nextSessionTitle" style="margin:4px 0 2px;font-size:22px;"></h2>
        <p class="subtitle" id="nextSessionMeta" style="margin-bottom:10px;"></p>
        <div class="exercise-preview-list" id="nextSessionList"></div>
        <button class="btn" style="margin-top:14px;" onclick="goTo('workout')">Démarrer la séance →</button>
      </div>
    </section>

    <!-- WORKOUT -->
    <section class="view" id="view-workout">
      <div id="workoutPreview">
        <h1 class="page-title display" id="woTitle">Séance</h1>
        <p class="subtitle" id="woMeta"></p>
        <div class="exercise-preview-list" id="woList"></div>
        <button class="btn" style="margin-top:16px;" onclick="startPlayer()">Lancer le chrono →</button>
      </div>

      <div id="workoutPlayer" style="display:none;">
        <div class="player-wrap">
          <div class="round-indicator" id="plRound"></div>
          <div class="queue-strip" id="plQueue"></div>
          <div class="figure-stage" id="plStage"></div>
          <div class="player-phase" id="plPhase">Travail</div>
          <h2 class="player-exname display" id="plExName"></h2>
          <p class="player-target" id="plTarget"></p>
          <p class="player-note" id="plNote"></p>
          <div class="timer-wrap">
            <div class="timer-ring" id="plRing">
              <svg width="140" height="140" viewBox="0 0 140 140">
                <circle class="track" cx="70" cy="70" r="62"/>
                <circle class="progress" id="plProgressCircle" cx="70" cy="70" r="62"
                  stroke-dasharray="389.6" stroke-dashoffset="0"/>
              </svg>
              <div class="timer-num" id="plTimerNum">--</div>
            </div>
          </div>
          <div class="player-controls">
            <button class="btn secondary" id="plPauseBtn" onclick="togglePause()">Pause</button>
            <button class="btn ghost" onclick="skipStep()">Suivant ▸</button>
          </div>
          <button class="btn secondary" onclick="quitPlayer()" style="border-color:#5a3030;color:#e08080;">Quitter la séance</button>
        </div>
      </div>

      <div id="workoutDone" style="display:none;">
        <h1 class="page-title display">Séance terminée 🔥</h1>
        <p class="subtitle">Bravo, une séance de plus dans la boîte. Note ton ressenti pour que le coach
        adapte la suite du programme.</p>
        <div class="card">
          <label class="field-label">Difficulté ressentie</label>
          <div class="rating-row" id="ratingRow">
            <button data-v="1">1</button>
            <button data-v="2">2</button>
            <button data-v="3">3</button>
            <button data-v="4">4</button>
            <button data-v="5">5</button>
          </div>
          <p class="subtitle" style="margin-bottom:8px;">1 = trop facile · 3 = parfait · 5 = trop dur</p>
          <div class="field">
            <label class="field-label">Notes (optionnel)</label>
            <textarea id="sessionNotes" placeholder="Ex: douleur épaule droite sur les pompes, kettlebell trop légère sur le swing..."></textarea>
          </div>
          <button class="btn" onclick="saveSession()">Enregistrer la séance</button>
        </div>
      </div>
    </section>

    <!-- HISTORY -->
    <section class="view" id="view-history">
      <h1 class="page-title display">Historique</h1>
      <p class="subtitle">Ton journal d'entraînement. Synchronisable avec Google Sheets depuis Réglages.</p>

      <div class="card">
        <strong style="font-size:13px;letter-spacing:.1em;text-transform:uppercase;color:var(--text-dim);">Volume par séance (min)</strong>
        <div class="bar-chart" id="barChart"></div>
        <div class="bar-label" id="barLabels"></div>
      </div>

      <div class="card" id="historyList">
        <strong style="font-size:13px;letter-spacing:.1em;text-transform:uppercase;color:var(--text-dim);">Séances</strong>
        <div id="historyItems"></div>
        <p class="subtitle" id="historyEmpty" style="margin-top:10px;">Aucune séance enregistrée pour le moment.</p>
      </div>

      <button class="btn secondary" onclick="exportCSV()">Exporter en CSV</button>
    </section>

    <!-- COACH -->
    <section class="view" id="view-coach">
      <h1 class="page-title display">Coach</h1>
      <p class="subtitle">Analyse de ta progression et ajustements du programme, basés sur ton historique.</p>

      <div id="coachReport"></div>

      <hr class="sep">

      <div class="card">
        <strong style="font-size:13px;letter-spacing:.1em;text-transform:uppercase;color:var(--text-dim);">Coach IA avancé (optionnel)</strong>
        <p class="subtitle">Envoie un résumé anonymisé de ton historique à Claude (API Anthropic) pour un avis
        personnalisé. Nécessite ta propre clé API et une connexion internet — configure-la dans Réglages.</p>
        <button class="btn ghost" onclick="askAICoach()">Demander un avis au coach IA</button>
        <div id="aiCoachOutput"></div>
      </div>
    </section>

    <!-- SETTINGS -->
    <section class="view" id="view-settings">
      <h1 class="page-title display">Réglages</h1>

      <div class="card">
        <strong style="font-size:13px;letter-spacing:.1em;text-transform:uppercase;color:var(--text-dim);">Google Sheets</strong>
        <p class="subtitle">Chaque séance enregistrée peut être envoyée vers une feuille Google Sheets via
        un Apps Script déployé en Web App.</p>
        <div class="field">
          <label class="field-label">URL du Web App Apps Script</label>
          <input type="text" id="sheetsUrl" placeholder="https://script.google.com/macros/s/.../exec">
        </div>
        <button class="btn secondary" onclick="saveSettings()">Enregistrer</button>
        <details class="help">
          <summary>Comment configurer la synchronisation ?</summary>
          <p class="subtitle">1. Crée une Google Sheet vide. 2. Extensions → Apps Script. 3. Colle ce code :</p>
          <pre class="code-block">function doPost(e) {
  var sheet = SpreadsheetApp.getActiveSpreadsheet().getActiveSheet();
  var d = JSON.parse(e.postData.contents);
  sheet.appendRow([d.date, d.week, d.day, d.title, d.durationMin, d.difficulty, d.notes]);
  return ContentService.createTextOutput("OK");
}</pre>
          <p class="subtitle">4. Déployer → Nouveau déploiement → Application Web → Accès "Tout le monde".
          5. Copie l'URL fournie ci-dessus.</p>
        </details>
      </div>

      <div class="card">
        <strong style="font-size:13px;letter-spacing:.1em;text-transform:uppercase;color:var(--text-dim);">Coach IA (Claude)</strong>
        <div class="field" style="margin-top:10px;">
          <label class="field-label">Clé API Anthropic</label>
          <input type="password" id="apiKey" placeholder="sk-ant-...">
        </div>
        <button class="btn secondary" onclick="saveSettings()">Enregistrer</button>
        <p class="subtitle" style="margin-top:8px;">Ta clé reste stockée localement dans ce fichier (localStorage de
        ton navigateur) et n'est envoyée qu'à l'API Anthropic. Selon ton navigateur, l'appel direct depuis un fichier
        local peut être bloqué (CORS) — dans ce cas, le coach hors-ligne intégré reste pleinement fonctionnel.</p>
      </div>

      <div class="card">
        <strong style="font-size:13px;letter-spacing:.1em;text-transform:uppercase;color:var(--text-dim);">Données</strong>
        <p class="subtitle">Toutes les données (historique, réglages) sont stockées uniquement sur cet appareil,
        dans ce fichier HTML.</p>
        <button class="btn secondary" style="border-color:#5a3030;color:#e08080;" onclick="resetData()">Réinitialiser toutes les données</button>
      </div>
    </section>

  </main>

  <nav class="tabbar">
    <div class="inner">
      <button class="tab active" data-view="dashboard" onclick="goTo('dashboard')">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 12l2-2 4 4 8-8 4 4"/><path d="M3 21h18"/></svg>
        Accueil
      </button>
      <button class="tab" data-view="workout" onclick="goTo('workout')">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="6" cy="12" r="3"/><circle cx="18" cy="12" r="3"/><path d="M9 12h6"/></svg>
        Séance
      </button>
      <button class="tab" data-view="history" onclick="goTo('history')">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M3 3v18h18"/><path d="M7 14l4-4 3 3 5-6"/></svg>
        Historique
      </button>
      <button class="tab" data-view="coach" onclick="goTo('coach')">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="8" r="4"/><path d="M4 21c0-4 4-6 8-6s8 2 8 6"/></svg>
        Coach
      </button>
      <button class="tab" data-view="settings" onclick="goTo('settings')">
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.7 1.7 0 0 0 .3 1.9l.1.1a2 2 0 1 1-2.8 2.8l-.1-.1a1.7 1.7 0 0 0-1.9-.3 1.7 1.7 0 0 0-1 1.5V21a2 2 0 1 1-4 0v-.1a1.7 1.7 0 0 0-1-1.6 1.7 1.7 0 0 0-1.9.3l-.1.1a2 2 0 1 1-2.8-2.8l.1-.1a1.7 1.7 0 0 0 .3-1.9 1.7 1.7 0 0 0-1.5-1H3a2 2 0 1 1 0-4h.1a1.7 1.7 0 0 0 1.6-1 1.7 1.7 0 0 0-.3-1.9l-.1-.1a2 2 0 1 1 2.8-2.8l.1.1a1.7 1.7 0 0 0 1.9.3H9a1.7 1.7 0 0 0 1-1.5V3a2 2 0 1 1 4 0v.1a1.7 1.7 0 0 0 1 1.5 1.7 1.7 0 0 0 1.9-.3l.1-.1a2 2 0 1 1 2.8 2.8l-.1.1a1.7 1.7 0 0 0-.3 1.9V9a1.7 1.7 0 0 0 1.5 1H21a2 2 0 1 1 0 4h-.1a1.7 1.7 0 0 0-1.5 1z"/></svg>
        Réglages
      </button>
    </div>
  </nav>

  <div class="toast" id="toast"></div>
</div>

<script>
/* ============================================================
   FORGE/37 — données du programme
   ============================================================ */

// ---- Figures (pictogrammes SVG animés, 2 poses par exercice) ----
function fig(pose){
  const L = p => `${p[0]},${p[1]}`;
  let parts = [];
  parts.push(`<line class="fig-line" x1="${pose.shoulder[0]}" y1="${pose.shoulder[1]}" x2="${pose.hip[0]}" y2="${pose.hip[1]}"/>`);
  [pose.arm1,pose.arm2].forEach(a=>{
    parts.push(`<polyline class="fig-line" points="${L(pose.shoulder)} ${L(a[0])} ${L(a[1])}"/>`);
  });
  [pose.leg1,pose.leg2].forEach(l=>{
    parts.push(`<polyline class="fig-line" points="${L(pose.hip)} ${L(l[0])} ${L(l[1])}"/>`);
  });
  parts.push(`<circle class="fig-head" cx="${pose.head[0]}" cy="${pose.head[1]}" r="6"/>`);
  if(pose.kb){
    const k = pose.kb;
    parts.push(`<g class="fig-kb"><path d="M${k[0]-4} ${k[1]-2} a4 4 0 0 1 8 0"/><circle cx="${k[0]}" cy="${k[1]+4}" r="6.5"/></g>`);
  }
  return `<svg viewBox="0 0 100 100">${parts.join('')}</svg>`;
}

const EXERCISES = {
  squat: {
    name: "Squat gobelet",
    muscles: ["Quadriceps","Fessiers","Gainage"],
    tip: "Tiens la kettlebell contre ta poitrine, descends en poussant les hanches vers l'arrière, genoux vers l'extérieur, dos droit.",
    mode: "reps", base: 12, kb:true,
    poses: [
      {head:[50,12],shoulder:[50,22],hip:[50,50],
       arm1:[[42,32],[44,46]],arm2:[[58,32],[56,46]],
       leg1:[[44,75],[42,98]],leg2:[[56,75],[58,98]], kb:[50,48]},
      {head:[53,28],shoulder:[53,40],hip:[50,68],
       arm1:[[45,52],[46,64]],arm2:[[58,52],[57,64]],
       leg1:[[35,72],[35,98]],leg2:[[65,72],[65,98]], kb:[50,66]}
    ]
  },
  pushup: {
    name: "Pompes",
    muscles: ["Pectoraux","Triceps","Épaules"],
    tip: "Corps gainé, ligne droite de la tête aux pieds. Descends jusqu'à effleurer le sol, coudes proches du corps. Sur les genoux si besoin.",
    mode: "reps", base: 8, kb:false,
    poses: [
      {head:[15,35],shoulder:[28,38],hip:[65,42],
       arm1:[[28,55],[30,75]],arm2:[[30,57],[32,75]],
       leg1:[[80,48],[95,55]],leg2:[[82,50],[97,57]], kb:null},
      {head:[15,55],shoulder:[28,58],hip:[65,60],
       arm1:[[30,62],[30,78]],arm2:[[32,64],[33,78]],
       leg1:[[80,62],[95,68]],leg2:[[82,63],[97,69]], kb:null}
    ]
  },
  swing: {
    name: "Kettlebell swing",
    muscles: ["Fessiers","Ischios","Dos"],
    tip: "Hinge de hanche, la kettlebell part entre les jambes puis est projetée par une extension explosive des hanches jusqu'à hauteur d'épaule.",
    mode: "reps", base: 15, kb:true,
    poses: [
      {head:[28,28],shoulder:[35,35],hip:[55,55],
       arm1:[[40,45],[48,62]],arm2:[[42,47],[50,63]],
       leg1:[[55,75],[50,98]],leg2:[[65,75],[68,98]], kb:[50,68]},
      {head:[50,12],shoulder:[50,22],hip:[50,48],
       arm1:[[50,30],[50,40]],arm2:[[52,30],[52,40]],
       leg1:[[45,75],[42,98]],leg2:[[55,75],[58,98]], kb:[51,38]}
    ]
  },
  plank: {
    name: "Gainage (planche)",
    muscles: ["Abdominaux","Lombaires","Épaules"],
    tip: "Avant-bras au sol, corps aligné tête-bassin-talons, abdos contractés, fessiers serrés. Respire calmement.",
    mode: "time", base: 30, kb:false,
    poses: [
      {head:[15,40],shoulder:[28,42],hip:[65,44],
       arm1:[[28,58],[28,75]],arm2:[[30,60],[30,75]],
       leg1:[[80,46],[95,50]],leg2:[[82,47],[97,51]], kb:null},
      {head:[15,42],shoulder:[28,44],hip:[65,48],
       arm1:[[28,58],[28,75]],arm2:[[30,60],[30,75]],
       leg1:[[80,50],[95,52]],leg2:[[82,51],[97,53]], kb:null}
    ]
  },
  lunge: {
    name: "Fentes avant alternées",
    muscles: ["Quadriceps","Fessiers","Équilibre"],
    tip: "Grand pas en avant, descends jusqu'à ce que le genou arrière frôle le sol, buste droit. Tiens la kettlebell à deux mains devant toi (goblet).",
    mode: "reps", base: 10, kb:true,
    poses: [
      {head:[50,12],shoulder:[50,22],hip:[50,50],
       arm1:[[45,35],[45,52]],arm2:[[55,35],[55,52]],
       leg1:[[45,75],[42,98]],leg2:[[55,75],[58,98]], kb:[50,54]},
      {head:[52,15],shoulder:[52,25],hip:[52,52],
       arm1:[[47,38],[47,56]],arm2:[[57,38],[57,56]],
       leg1:[[35,68],[30,98]],leg2:[[68,80],[75,98]], kb:[52,58]}
    ]
  },
  row: {
    name: "Rowing kettlebell unilatéral",
    muscles: ["Dos","Biceps","Gainage"],
    tip: "Buste penché à 45°, dos plat. Tire la kettlebell vers la hanche en gardant le coude proche du corps, puis redescends en contrôle.",
    mode: "reps", base: 10, kb:true,
    poses: [
      {head:[33,28],shoulder:[40,35],hip:[60,50],
       arm1:[[42,50],[45,70]],arm2:[[55,48],[58,55]],
       leg1:[[60,72],[55,98]],leg2:[[68,72],[70,98]], kb:[45,72]},
      {head:[33,28],shoulder:[40,35],hip:[60,50],
       arm1:[[48,42],[50,42]],arm2:[[55,48],[58,55]],
       leg1:[[60,72],[55,98]],leg2:[[68,72],[70,98]], kb:[50,40]}
    ]
  },
  mountainclimber: {
    name: "Mountain climbers",
    muscles: ["Gainage","Cardio","Hanches"],
    tip: "En position de planche haute, ramène un genou vers la poitrine puis l'autre, rapidement, en gardant le bassin stable.",
    mode: "time", base: 30, kb:false,
    poses: [
      {head:[15,38],shoulder:[28,40],hip:[55,42],
       arm1:[[28,55],[28,72]],arm2:[[30,57],[30,72]],
       leg1:[[45,55],[40,60]],leg2:[[78,46],[95,50]], kb:null},
      {head:[15,38],shoulder:[28,40],hip:[55,42],
       arm1:[[28,55],[28,72]],arm2:[[30,57],[30,72]],
       leg1:[[78,46],[95,50]],leg2:[[45,55],[40,60]], kb:null}
    ]
  },
  hipthrust: {
    name: "Pont fessier kettlebell",
    muscles: ["Fessiers","Ischios","Gainage"],
    tip: "Allongé, genoux fléchis, kettlebell posée sur le bassin. Pousse les hanches vers le plafond en serrant les fessiers, redescends en contrôle.",
    mode: "reps", base: 15, kb:true,
    poses: [
      {head:[15,70],shoulder:[25,72],hip:[50,75],
       arm1:[[25,80],[20,85]],arm2:[[25,80],[20,85]],
       leg1:[[65,60],[78,75]],leg2:[[67,61],[80,76]], kb:[50,68]},
      {head:[15,70],shoulder:[25,72],hip:[50,58],
       arm1:[[25,80],[20,85]],arm2:[[25,80],[20,85]],
       leg1:[[65,60],[78,75]],leg2:[[67,61],[80,76]], kb:[50,52]}
    ]
  },
  sideplank: {
    name: "Gainage latéral",
    muscles: ["Obliques","Épaules","Hanches"],
    tip: "Appui sur un avant-bras, corps aligné sur le côté, hanches relevées. Le bras libre peut pointer vers le plafond. Change de côté à la moitié du temps.",
    mode: "time", base: 20, kb:false,
    poses: [
      {head:[20,35],shoulder:[30,38],hip:[60,42],
       arm1:[[30,55],[30,70]],arm2:[[60,45],[65,50]],
       leg1:[[78,46],[95,50]],leg2:[[80,47],[97,51]], kb:null},
      {head:[20,35],shoulder:[30,38],hip:[60,42],
       arm1:[[30,55],[30,70]],arm2:[[65,30],[75,15]],
       leg1:[[78,46],[95,50]],leg2:[[80,47],[97,51]], kb:null}
    ]
  },
  deadlift: {
    name: "Soulevé de terre kettlebell",
    muscles: ["Chaîne postérieure","Fessiers","Dos"],
    tip: "Pieds écartés largeur de hanches, kettlebell au sol entre les pieds. Hanches en arrière, dos plat, pousse le sol pour te relever en gainant fort.",
    mode: "reps", base: 12, kb:true,
    poses: [
      {head:[50,12],shoulder:[50,22],hip:[50,50],
       arm1:[[45,35],[45,55]],arm2:[[55,35],[55,55]],
       leg1:[[45,75],[42,98]],leg2:[[55,75],[58,98]], kb:[50,57]},
      {head:[35,35],shoulder:[40,40],hip:[55,45],
       arm1:[[40,55],[40,80]],arm2:[[45,57],[45,80]],
       leg1:[[58,75],[55,98]],leg2:[[65,76],[68,98]], kb:[40,85]}
    ]
  },
  russiantwist: {
    name: "Russian twist kettlebell",
    muscles: ["Obliques","Gainage"],
    tip: "Assis, buste légèrement incliné en arrière, pieds décollés du sol. Fais pivoter la kettlebell d'un côté à l'autre en tournant le buste.",
    mode: "reps", base: 16, kb:true,
    poses: [
      {head:[40,35],shoulder:[45,45],hip:[50,70],
       arm1:[[55,50],[68,55]],arm2:[[58,52],[68,58]],
       leg1:[[65,75],[80,85]],leg2:[[60,78],[78,90]], kb:[70,57]},
      {head:[60,35],shoulder:[55,45],hip:[50,70],
       arm1:[[45,50],[32,55]],arm2:[[42,52],[32,58]],
       leg1:[[65,75],[80,85]],leg2:[[60,78],[78,90]], kb:[30,57]}
    ]
  },
  burpee: {
    name: "Burpees",
    muscles: ["Full body","Cardio"],
    tip: "Place-toi en planche, fais une pompe (optionnel), ramène les pieds sous toi puis explose vers le haut en sautant, bras levés.",
    mode: "reps", base: 8, kb:false,
    poses: [
      {head:[15,55],shoulder:[28,58],hip:[65,60],
       arm1:[[30,62],[30,78]],arm2:[[32,64],[33,78]],
       leg1:[[80,62],[95,68]],leg2:[[82,63],[97,69]], kb:null},
      {head:[50,10],shoulder:[50,22],hip:[50,48],
       arm1:[[44,12],[40,4]],arm2:[[56,12],[60,4]],
       leg1:[[45,72],[42,98]],leg2:[[55,72],[58,98]], kb:null}
    ]
  }
};

// ---- Structure des séances (jours A/B/C) ----
const DAY_TEMPLATES = {
  A: { title: "Push & Bas du corps", exercises: ["squat","pushup","lunge","deadlift","plank"] },
  B: { title: "Tirage & Postérieur", exercises: ["swing","row","hipthrust","sideplank","mountainclimber"] },
  C: { title: "Cardio & Gainage", exercises: ["burpee","russiantwist","squat","pushup","plank"] }
};
const WEEK_ORDER = ["A","B","C"]; // x4 semaines = 12 séances

function buildSession(sessionIndex){
  // sessionIndex 0..11
  const week = Math.floor(sessionIndex/3)+1; // 1..4
  const dayKey = WEEK_ORDER[sessionIndex%3];
  const tpl = DAY_TEMPLATES[dayKey];
  const rounds = week<=2 ? 3 : 4;
  const restSec = Math.max(15, 30 - (week-1)*5);
  const roundRest = restSec*2;
  const repsAdd = (week-1)*2;
  const secAdd = (week-1)*5;

  const exercises = tpl.exercises.map(id=>{
    const ex = EXERCISES[id];
    const target = ex.mode==="reps" ? (ex.base+repsAdd) : (ex.base+secAdd);
    const workSec = ex.mode==="time" ? target : 40;
    return {id, ex, target, workSec};
  });

  return {
    sessionIndex, week, dayKey,
    title: tpl.title,
    exercises, rounds, restSec, roundRest
  };
}

const WARMUP_MOVES = [
  "Rotations des épaules et des chevilles, marche sur place",
  "Montées de genoux dynamiques",
  "Squats à vide, lents et contrôlés",
  "Enchaînement planche / chien tête en bas"
];
const COOLDOWN_MOVES = [
  "Étirement ischio-jambiers et dos : debout, mains vers les pieds",
  "Étirement épaules et pectoraux : bras en croix ou contre un mur"
];

/* ============================================================
   État, stockage local
   ============================================================ */
const STORE_HISTORY = "forge37_history";
const STORE_SETTINGS = "forge37_settings";

function getHistory(){
  try{ return JSON.parse(localStorage.getItem(STORE_HISTORY)) || []; }catch(e){ return []; }
}
function saveHistory(h){ localStorage.setItem(STORE_HISTORY, JSON.stringify(h)); }
function getSettings(){
  try{ return JSON.parse(localStorage.getItem(STORE_SETTINGS)) || {}; }catch(e){ return {}; }
}
function setSettings(s){ localStorage.setItem(STORE_SETTINGS, JSON.stringify(s)); }

function currentSessionIndex(){
  const h = getHistory();
  return Math.min(h.length, 11);
}

/* ============================================================
   Navigation
   ============================================================ */
function goTo(view){
  document.querySelectorAll('.view').forEach(v=>v.classList.remove('active'));
  document.getElementById('view-'+view).classList.add('active');
  document.querySelectorAll('nav .tab').forEach(b=>b.classList.toggle('active', b.dataset.view===view));
  if(view==='dashboard') renderDashboard();
  if(view==='workout') renderWorkout();
  if(view==='history') renderHistory();
  if(view==='coach') renderCoach();
  if(view==='settings') renderSettings();
}

function toast(msg){
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.classList.add('show');
  setTimeout(()=>t.classList.remove('show'), 2200);
}

/* ============================================================
   DASHBOARD
   ============================================================ */
function renderDashboard(){
  const h = getHistory();
  const idx = currentSessionIndex();
  const session = buildSession(idx);

  document.getElementById('weekPill').innerHTML = `Semaine <b>${session.week}</b> · ${idx+1}/12`;
  document.getElementById('progressCount').textContent = `${h.length}/12`;

  // grid
  const grid = document.getElementById('progressGrid');
  grid.innerHTML='';
  for(let i=0;i<12;i++){
    const cell = document.createElement('div');
    cell.className='progress-cell';
    if(i<h.length) cell.classList.add('done');
    else if(i===h.length) cell.classList.add('next');
    cell.textContent = i+1;
    grid.appendChild(cell);
  }

  // stats
  document.getElementById('statTotalMin').textContent = h.reduce((s,x)=>s+Math.round(x.durationMin||0),0);
  let streak=0;
  for(let i=h.length-1;i>=0;i--){ if(h[i].difficulty>=1) streak++; else break; }
  document.getElementById('statStreak').textContent = streak;
  const diffs = h.map(x=>x.difficulty).filter(Boolean);
  document.getElementById('statAvgDiff').textContent = diffs.length ? (diffs.reduce((a,b)=>a+b,0)/diffs.length).toFixed(1) : "–";

  // next session
  if(h.length>=12){
    document.getElementById('nextSessionTitle').textContent = "Programme terminé 🎉";
    document.getElementById('nextSessionMeta').textContent = "Bravo pour les 12 séances ! Va voir le Coach pour décider de la suite (cycle 2, plus intense).";
    document.getElementById('nextSessionList').innerHTML='';
    document.querySelector('#nextSessionCard .btn').style.display='none';
  } else {
    document.querySelector('#nextSessionCard .btn').style.display='block';
    document.getElementById('nextSessionTitle').textContent = `Semaine ${session.week} · Jour ${session.dayKey} — ${session.title}`;
    document.getElementById('nextSessionMeta').textContent = `${session.rounds} tours · repos ${session.restSec}s · ~${estimateDuration(session)} min`;
    const list = document.getElementById('nextSessionList');
    list.innerHTML='';
    session.exercises.forEach(item=>{
      list.appendChild(buildPreviewRow(item));
    });
  }
}

function buildPreviewRow(item){
  const row = document.createElement('div');
  row.className='exercise-preview';
  const targetLabel = item.ex.mode==='reps' ? `${item.target} reps` : `${item.target} sec`;
  row.innerHTML = `
    <div class="mini-fig">${fig(item.ex.poses[0])}</div>
    <div class="ep-info">
      <div class="ep-name">${item.ex.name}</div>
      <div class="ep-target">${targetLabel} × ${'-'}</div>
    </div>`;
  return row;
}

function estimateDuration(session){
  const exWork = session.exercises.reduce((s,e)=>s+e.workSec,0);
  const exRest = session.restSec*(session.exercises.length-1);
  const roundTotal = exWork+exRest;
  const total = roundTotal*session.rounds + session.roundRest*(session.rounds-1) + 180 + 120;
  return Math.round(total/60);
}

/* ============================================================
   WORKOUT — preview + player
   ============================================================ */
let activeSession = null;

function renderWorkout(){
  document.getElementById('workoutPreview').style.display='block';
  document.getElementById('workoutPlayer').style.display='none';
  document.getElementById('workoutDone').style.display='none';
  const idx = currentSessionIndex();
  if(idx>=12){
    document.getElementById('woTitle').textContent = "Programme terminé";
    document.getElementById('woMeta').textContent = "Toutes les séances sont complétées. Consulte le Coach.";
    document.getElementById('woList').innerHTML='';
    document.querySelector('#workoutPreview .btn').style.display='none';
    return;
  }
  document.querySelector('#workoutPreview .btn').style.display='block';
  activeSession = buildSession(idx);
  document.getElementById('woTitle').textContent = `S${activeSession.week} · ${activeSession.dayKey} — ${activeSession.title}`;
  document.getElementById('woMeta').textContent = `${activeSession.rounds} tours × ${activeSession.exercises.length} exercices · repos ${activeSession.restSec}s · ~${estimateDuration(activeSession)} min`;
  const list = document.getElementById('woList');
  list.innerHTML='';
  activeSession.exercises.forEach(item=>{
    const row = buildPreviewRow(item);
    row.querySelector('.ep-target').textContent = (item.ex.mode==='reps' ? `${item.target} reps` : `${item.target} sec`) + ` · ${item.ex.muscles.join(', ')}`;
    list.appendChild(row);
  });
}

// ---- player engine ----
let playerQueue = [];
let playerIdx = 0;
let playerTimer = null;
let playerRemaining = 0;
let playerPaused = false;
let figureInterval = null;
let sessionStartTime = null;

function buildQueue(session){
  const q = [];
  WARMUP_MOVES.forEach(m=> q.push({type:'warmup', label:m, duration:45}));
  for(let r=1; r<=session.rounds; r++){
    session.exercises.forEach((item, i)=>{
      q.push({type:'work', item, duration:item.workSec, round:r});
      if(i < session.exercises.length-1){
        q.push({type:'rest', duration:session.restSec, round:r});
      }
    });
    if(r < session.rounds){
      q.push({type:'roundrest', duration:session.roundRest, round:r});
    }
  }
  COOLDOWN_MOVES.forEach(m=> q.push({type:'cooldown', label:m, duration:60}));
  return q;
}

function startPlayer(){
  playerQueue = buildQueue(activeSession);
  playerIdx = 0;
  sessionStartTime = Date.now();
  document.getElementById('workoutPreview').style.display='none';
  document.getElementById('workoutPlayer').style.display='block';
  document.getElementById('workoutDone').style.display='none';
  renderQueueStrip();
  loadStep();
}

function renderQueueStrip(){
  const strip = document.getElementById('plQueue');
  strip.innerHTML='';
  playerQueue.forEach((s,i)=>{
    const d = document.createElement('div');
    d.className='queue-dot';
    if(i<playerIdx) d.classList.add('done');
    if(i===playerIdx) d.classList.add('cur');
    strip.appendChild(d);
  });
}

const RING_CIRC = 2*Math.PI*62;

function loadStep(){
  if(playerIdx>=playerQueue.length){ finishPlayer(); return; }
  const step = playerQueue[playerIdx];
  playerRemaining = step.duration;
  playerPaused = false;
  document.getElementById('plPauseBtn').textContent='Pause';
  renderQueueStrip();

  const phaseEl = document.getElementById('plPhase');
  const ring = document.getElementById('plRing');
  const stage = document.getElementById('plStage');

  if(step.type==='work'){
    phaseEl.textContent='Travail';
    phaseEl.className='player-phase work';
    ring.classList.remove('rest');
    document.getElementById('plExName').textContent = step.item.ex.name;
    const t = step.item.ex.mode==='reps' ? `Objectif : ${step.item.target} répétitions` : `Tiens ${step.item.target} secondes`;
    document.getElementById('plTarget').textContent = t;
    document.getElementById('plNote').textContent = step.item.ex.tip.length>90 ? step.item.ex.tip.slice(0,90)+'…' : step.item.ex.tip;
    document.getElementById('plRound').textContent = `Tour ${step.round} / ${activeSession.rounds}`;
    startFigureAnimation(stage, step.item.ex.poses);
  } else if(step.type==='rest' || step.type==='roundrest'){
    phaseEl.textContent = step.type==='roundrest' ? 'Repos entre tours' : 'Repos';
    phaseEl.className='player-phase rest';
    ring.classList.add('rest');
    document.getElementById('plExName').textContent = 'Récupération';
    const nextWork = findNextWork();
    document.getElementById('plTarget').textContent = nextWork ? `Suivant : ${nextWork.ex.name}` : '';
    document.getElementById('plNote').textContent = 'Respire, secoue les bras, hydrate-toi.';
    document.getElementById('plRound').textContent = `Tour ${step.round} / ${activeSession.rounds}`;
    stopFigureAnimation();
    stage.innerHTML = nextWork ? fig(nextWork.poses[0]) : '';
    if(stage.firstChild) stage.firstChild.classList.add('show');
  } else if(step.type==='warmup' || step.type==='cooldown'){
    phaseEl.textContent = step.type==='warmup' ? 'Échauffement' : 'Retour au calme';
    phaseEl.className='player-phase';
    ring.classList.remove('rest');
    document.getElementById('plExName').textContent = step.type==='warmup' ? 'Échauffement' : 'Étirements';
    document.getElementById('plTarget').textContent = '';
    document.getElementById('plNote').textContent = step.label;
    document.getElementById('plRound').textContent = '';
    stopFigureAnimation();
    stage.innerHTML = `<div style="display:flex;align-items:center;justify-content:center;height:100%;font-size:40px;">${step.type==='warmup'?'🔥':'🧘'}</div>`;
  }

  updateTimerDisplay();
  clearInterval(playerTimer);
  playerTimer = setInterval(tickTimer, 1000);
}

function findNextWork(){
  for(let i=playerIdx+1;i<playerQueue.length;i++){
    if(playerQueue[i].type==='work') return playerQueue[i].item.ex;
  }
  return null;
}

function startFigureAnimation(stage, poses){
  stopFigureAnimation();
  stage.innerHTML = fig(poses[0]) + fig(poses[1]);
  const svgs = stage.querySelectorAll('svg');
  svgs[0].classList.add('show');
  let toggle=0;
  figureInterval = setInterval(()=>{
    toggle = 1-toggle;
    svgs[0].classList.toggle('show', toggle===0);
    svgs[1].classList.toggle('show', toggle===1);
  }, 1100);
}
function stopFigureAnimation(){
  if(figureInterval){ clearInterval(figureInterval); figureInterval=null; }
}

function updateTimerDisplay(){
  document.getElementById('plTimerNum').textContent = playerRemaining;
  const step = playerQueue[playerIdx];
  const frac = playerRemaining/step.duration;
  const offset = RING_CIRC * (1-frac);
  document.getElementById('plProgressCircle').setAttribute('stroke-dasharray', RING_CIRC.toFixed(1));
  document.getElementById('plProgressCircle').setAttribute('stroke-dashoffset', offset.toFixed(1));
}

function tickTimer(){
  if(playerPaused) return;
  playerRemaining--;
  updateTimerDisplay();
  if(playerRemaining<=0){
    playSound();
    playerIdx++;
    loadStep();
  }
}

function togglePause(){
  playerPaused = !playerPaused;
  document.getElementById('plPauseBtn').textContent = playerPaused ? 'Reprendre' : 'Pause';
}

function skipStep(){
  clearInterval(playerTimer);
  playerIdx++;
  loadStep();
}

function quitPlayer(){
  if(!confirm("Quitter la séance en cours ? Rien ne sera enregistré.")) return;
  clearInterval(playerTimer);
  stopFigureAnimation();
  goTo('workout');
}

function finishPlayer(){
  clearInterval(playerTimer);
  stopFigureAnimation();
  document.getElementById('workoutPlayer').style.display='none';
  document.getElementById('workoutDone').style.display='block';
  document.querySelectorAll('#ratingRow button').forEach(b=>{
    b.classList.remove('sel');
    b.onclick = ()=>{
      document.querySelectorAll('#ratingRow button').forEach(x=>x.classList.remove('sel'));
      b.classList.add('sel');
    };
  });
}

function playSound(){
  try{
    const ctx = new (window.AudioContext||window.webkitAudioContext)();
    const o = ctx.createOscillator();
    const g = ctx.createGain();
    o.type='sine'; o.frequency.value=880;
    g.gain.value=0.08;
    o.connect(g); g.connect(ctx.destination);
    o.start();
    setTimeout(()=>{ o.stop(); ctx.close(); }, 150);
  }catch(e){}
}

function saveSession(){
  const sel = document.querySelector('#ratingRow button.sel');
  const difficulty = sel ? parseInt(sel.dataset.v) : 3;
  const notes = document.getElementById('sessionNotes').value.trim();
  const durationMin = Math.round((Date.now()-sessionStartTime)/60000) || estimateDuration(activeSession);

  const entry = {
    date: new Date().toISOString().slice(0,10),
    week: activeSession.week,
    day: activeSession.dayKey,
    title: activeSession.title,
    durationMin,
    difficulty,
    notes
  };
  const h = getHistory();
  h.push(entry);
  saveHistory(h);

  // sheets sync (best effort)
  const settings = getSettings();
  if(settings.sheetsUrl){
    fetch(settings.sheetsUrl, {
      method:'POST', mode:'no-cors',
      headers:{'Content-Type':'text/plain'},
      body: JSON.stringify(entry)
    }).catch(()=>{});
  }

  document.getElementById('sessionNotes').value='';
  toast('Séance enregistrée 💪');
  goTo('dashboard');
}

/* ============================================================
   HISTORY
   ============================================================ */
function renderHistory(){
  const h = getHistory();
  const items = document.getElementById('historyItems');
  const empty = document.getElementById('historyEmpty');
  items.innerHTML='';
  empty.style.display = h.length ? 'none':'block';

  [...h].reverse().forEach(e=>{
    const d = new Date(e.date+'T00:00:00');
    const div = document.createElement('div');
    div.className='hist-item';
    const diffDots = [1,2,3,4,5].map(n=>`<span class="${n<=e.difficulty?'on':''}"></span>`).join('');
    div.innerHTML = `
      <div class="hist-date"><div class="d">${d.getDate()}</div><div class="m">${d.toLocaleDateString('fr-FR',{month:'short'})}</div></div>
      <div class="hist-info">
        <div class="ht">S${e.week} · ${e.day} — ${e.title}</div>
        <div class="hs">${e.durationMin} min ${e.notes? '· '+e.notes : ''}</div>
      </div>
      <div class="hist-diff">${diffDots}</div>`;
    items.appendChild(div);
  });

  // bar chart
  const bar = document.getElementById('barChart');
  const labels = document.getElementById('barLabels');
  bar.innerHTML=''; labels.innerHTML='';
  const maxMin = Math.max(...h.map(e=>e.durationMin), 25);
  for(let i=0;i<12;i++){
    const e = h[i];
    const b = document.createElement('div');
    b.className='bar'+(e?' filled':'');
    b.style.height = e ? Math.max(6, (e.durationMin/maxMin*90))+'px' : '4px';
    b.title = e ? `${e.durationMin} min` : '';
    bar.appendChild(b);
    const lab = document.createElement('span');
    lab.textContent = (i+1);
    labels.appendChild(lab);
  }
}

function exportCSV(){
  const h = getHistory();
  let csv = "date,semaine,jour,titre,duree_min,difficulte,notes\n";
  h.forEach(e=>{
    csv += `${e.date},${e.week},${e.day},"${e.title}",${e.durationMin},${e.difficulty},"${(e.notes||'').replace(/"/g,'""')}"\n`;
  });
  const blob = new Blob([csv], {type:'text/csv'});
  const url = URL.createObjectURL(blob);
  const a = document.createElement('a');
  a.href=url; a.download='forge37_historique.csv';
  document.body.appendChild(a); a.click(); document.body.removeChild(a);
  URL.revokeObjectURL(url);
}

/* ============================================================
   COACH (règles locales + option IA)
   ============================================================ */
const QUOTES = [
  "À 37 ans, ton corps répond toujours très bien à la régularité — chaque séance compte plus que sa perfection.",
  "La récupération fait partie de l'entraînement : un sommeil correct et des protéines suffisantes valent autant qu'une bonne séance.",
  "Le but n'est pas la perfection technique immédiate, mais l'accumulation de séances sur 4 semaines.",
  "Le gainage est le fil rouge de ce programme : un tronc fort protège le dos et améliore tous les autres mouvements.",
  "Si une séance est ratée, la suivante compte double pour la motivation — ne saute pas deux séances de suite.",
];

function renderCoach(){
  const h = getHistory();
  const idx = currentSessionIndex();
  const wrap = document.getElementById('coachReport');
  wrap.innerHTML='';

  const intro = document.createElement('div');
  intro.className='coach-msg';
  intro.innerHTML = `<span class="tag">Coach</span>
  Salut ! Programme calisthénie + kettlebell sur 4 semaines (12 séances de 25 min max).
  Garde en tête qu'en 1 mois, une vraie « définition musculaire » dépend autant de l'entraînement que de l'alimentation
  (apport en protéines, léger déficit calorique si l'objectif inclut une perte de gras). Ce coach analyse ta régularité
  et ta difficulté ressentie pour ajuster le plan, mais le programme de base reste le même — je te propose juste
  des ajustements (intensité, repos) selon tes retours.`;
  wrap.appendChild(intro);

  // consistency
  const consistency = document.createElement('div');
  consistency.className='coach-msg';
  let consText;
  if(h.length===0){
    consText = "Aucune séance enregistrée encore. Lance la première séance dès que possible — la première semaine donne le ton !";
  } else if(h.length>=12){
    consText = `Programme terminé : ${h.length}/12 séances ! Tu peux soit relancer un cycle avec l'intensité de la semaine 4
    dès le départ, soit ajouter une kettlebell plus lourde si tu en as une.`;
  } else {
    const week = Math.floor(idx/3)+1;
    const sessionsThisWeek = h.filter(e=>e.week===week).length;
    consText = `Semaine ${week} : ${sessionsThisWeek}/3 séances faites. `;
    if(sessionsThisWeek>=3) consText += "Semaine complète, bravo ! Le repos avant la suivante est important.";
    else if(sessionsThisWeek===0 && h.length>0) consText += "Pense à programmer ta prochaine séance pour garder le rythme de 3x/semaine.";
    else consText += "Continue, tu es sur la bonne trajectoire pour les 3 séances de la semaine.";
  }
  consistency.innerHTML = `<span class="tag">Régularité</span>${consText}`;
  wrap.appendChild(consistency);

  // difficulty trend / adjustment
  if(h.length>=2){
    const last3 = h.slice(-3);
    const avg = last3.reduce((s,e)=>s+e.difficulty,0)/last3.length;
    const adj = document.createElement('div');
    adj.className='coach-msg';
    let adjText;
    if(avg<=2){
      adjText = `Tes 3 dernières séances semblent plutôt faciles (difficulté moy. ${avg.toFixed(1)}/5).
      Suggestion : ajoute 1 tour supplémentaire ou utilise une kettlebell plus lourde sur les mouvements
      kettlebell (swing, deadlift, rowing, fentes, pont fessier). Le nombre de tours/répétitions prévus
      par le programme reste un minimum — tu peux pousser un peu plus si la forme est bonne.`;
    } else if(avg>=4){
      adjText = `Tes 3 dernières séances sont notées difficiles (moy. ${avg.toFixed(1)}/5).
      Suggestion pour la prochaine séance : retire 1 tour ou rallonge les temps de repos de 10s,
      surtout sur les exercices cardio (burpees, mountain climbers). Mieux vaut une séance complète à 80%
      qu'une séance abandonnée à mi-chemin.`;
    } else {
      adjText = `Difficulté moyenne récente : ${avg.toFixed(1)}/5 — c'est exactement la zone visée. Continue avec
      les paramètres du programme tels qu'ils sont prévus pour cette semaine.`;
    }
    adj.innerHTML = `<span class="tag">Ajustement suggéré</span>${adjText}`;
    wrap.appendChild(adj);
  }

  // notes mention
  const lastWithNotes = [...h].reverse().find(e=>e.notes);
  if(lastWithNotes){
    const noteCard = document.createElement('div');
    noteCard.className='coach-msg';
    noteCard.innerHTML = `<span class="tag">Dernière note</span>« ${lastWithNotes.notes} » (S${lastWithNotes.week} · ${lastWithNotes.day}).
    Si une douleur articulaire est mentionnée, réduis l'amplitude ou remplace temporairement l'exercice par sa version
    plus facile (ex : pompes sur les genoux, gainage sur les genoux) plutôt que de forcer.`;
    wrap.appendChild(noteCard);
  }

  // motivational quote
  const quote = document.createElement('div');
  quote.className='coach-msg';
  const q = QUOTES[idx % QUOTES.length];
  quote.innerHTML = `<span class="tag">Pour la suite</span>${q}`;
  wrap.appendChild(quote);

  document.getElementById('aiCoachOutput').innerHTML='';
}

async function askAICoach(){
  const settings = getSettings();
  const out = document.getElementById('aiCoachOutput');
  if(!settings.apiKey){
    out.innerHTML = `<p class="subtitle" style="margin-top:10px;color:var(--warn);">Aucune clé API configurée. Va dans Réglages pour l'ajouter, ou utilise l'analyse du coach intégré ci-dessus.</p>`;
    return;
  }
  out.innerHTML = `<p class="subtitle" style="margin-top:10px;">Analyse en cours...</p>`;

  const h = getHistory();
  const idx = currentSessionIndex();
  const summary = h.map(e=>`S${e.week}/${e.day} le ${e.date}: ${e.durationMin}min, difficulté ${e.difficulty}/5${e.notes?', notes: '+e.notes:''}`).join('\n') || "Aucune séance encore.";

  const prompt = `Tu es un coach de fitness pour une personne de 37 ans suivant un programme calisthénie + kettlebell
sur 4 semaines (12 séances de 25 min, 3x/semaine, axé gainage). Objectif : améliorer la définition musculaire
visible et le tonus en 1 mois, de façon réaliste. Voici son historique de séances :
${summary}
Séance actuelle : ${idx+1}/12.
En 4-6 phrases maximum : (1) un message de motivation personnalisé et concret, (2) une analyse honnête de sa
régularité/progression, (3) une suggestion d'ajustement précise pour la prochaine séance ou semaine si pertinent.
Réponds en français, ton direct et encourageant, sans formules génériques.`;

  try{
    const res = await fetch('https://api.anthropic.com/v1/messages', {
      method:'POST',
      headers:{
        'Content-Type':'application/json',
        'x-api-key': settings.apiKey,
        'anthropic-version':'2023-06-01',
        'anthropic-dangerous-direct-browser-access':'true'
      },
      body: JSON.stringify({
        model:'claude-sonnet-4-6',
        max_tokens:600,
        messages:[{role:'user', content: prompt}]
      })
    });
    if(!res.ok){
      const txt = await res.text();
      throw new Error(`HTTP ${res.status}: ${txt.slice(0,200)}`);
    }
    const data = await res.json();
    const text = (data.content||[]).filter(c=>c.type==='text').map(c=>c.text).join('\n');
    out.innerHTML = `<div class="coach-msg" style="margin-top:10px;"><span class="tag">Coach IA</span>${text.replace(/\n/g,'<br>')}</div>`;
  }catch(err){
    out.innerHTML = `<p class="subtitle" style="margin-top:10px;color:var(--warn);">
      Impossible de contacter le coach IA (${err.message}). Cela peut venir d'une restriction CORS de ton navigateur
      pour les fichiers locaux, ou d'une clé invalide. Le coach intégré ci-dessus reste disponible hors-ligne.</p>`;
  }
}

/* ============================================================
   SETTINGS
   ============================================================ */
function renderSettings(){
  const s = getSettings();
  document.getElementById('sheetsUrl').value = s.sheetsUrl || '';
  document.getElementById('apiKey').value = s.apiKey || '';
}
function saveSettings(){
  const s = {
    sheetsUrl: document.getElementById('sheetsUrl').value.trim(),
    apiKey: document.getElementById('apiKey').value.trim()
  };
  setSettings(s);
  toast('Réglages enregistrés');
}
function resetData(){
  if(!confirm("Supprimer tout l'historique et les réglages ? Cette action est irréversible.")) return;
  localStorage.removeItem(STORE_HISTORY);
  localStorage.removeItem(STORE_SETTINGS);
  toast('Données réinitialisées');
  goTo('dashboard');
}

/* ============================================================
   Init
   ============================================================ */
renderDashboard();
</script>
</body>
</html>

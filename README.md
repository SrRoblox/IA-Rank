# IA-Rank
Encontre a melhor IA para cada tarefa
<html lang="pt-BR"><head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>IA Rank — Encontre a melhor IA para cada tarefa</title>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@600;800&amp;family=Source+Sans+3:wght@400;600&amp;display=swap" rel="stylesheet">
<meta name="description" content="IA Rank: portal para comparar e classificar inteligências artificiais por finalidade: estudos, programação, imagens, vídeos, escrita e mais.">
<style>
:root{--bg:#000;--card:#0a0a0a;--line:#2a2a2a;--tx:#f2f4fb;--mu:#aab2cf;--blue:#3b82f6;--vio:#8b5cf6;--ok:#34d399;color-scheme:dark;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
*,*::before,*::after{box-sizing:inherit}html{scroll-behavior:smooth;scroll-padding-top:90px}
body{margin:0;background:radial-gradient(900px 400px at 80% -10%,#00000000,transparent),var(--bg);color:var(--tx);font:17px/1.6 "Source Sans 3",system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
a{color:inherit}.wrap{max-width:1080px;margin:0 auto;padding:0 20px}
:focus-visible{outline:3px solid #93c5fd;outline-offset:2px}
header{position:sticky;top:0;z-index:5;background:#000000ee;backdrop-filter:blur(8px);border-bottom:1px solid var(--line)}
.bar{display:flex;flex-wrap:wrap;align-items:center;gap:10px 22px;padding:12px 0}
.logo{font-weight:800;font-size:1.35rem;text-decoration:none;background:linear-gradient(90deg,var(--blue),var(--vio));-webkit-background-clip:text;background-clip:text;color:transparent}
.tag{display:block;font-size:.78rem;color:var(--mu);font-weight:400;-webkit-text-fill-color:var(--mu)}
.status{display:flex;align-items:center;gap:8px;font-size:.72rem;letter-spacing:.12em;color:var(--mu)}
.lamp{width:10px;height:10px;border-radius:50%;background:var(--ok);box-shadow:0 0 10px var(--ok);animation:blink 2s ease-in-out infinite}
@keyframes blink{0%,100%{opacity:1}50%{opacity:.15;box-shadow:none}}
nav{display:flex;gap:16px;margin-left:auto;flex-wrap:wrap}nav a{text-decoration:none;color:var(--mu);padding:4px 2px}nav a:hover{color:var(--tx)}
.btn{display:inline-block;border:0;cursor:pointer;font:inherit;font-weight:600;color:#fff;text-decoration:none;padding:10px 18px;border-radius:12px;background:linear-gradient(90deg,var(--blue),var(--vio))}
.btn.ghost{background:transparent;border:1px solid var(--line);color:var(--tx)}
.hero{padding:96px 20px 56px;text-align:center}.eyebrow{display:inline-block;font-size:.75rem;letter-spacing:.14em;text-transform:uppercase;color:#9db8ff;border:1px solid var(--line);background:#0f1426;padding:5px 14px;border-radius:999px;margin-bottom:18px}.grad{background:linear-gradient(90deg,#60a5fa,#a78bfa);-webkit-background-clip:text;background-clip:text;color:transparent}.steps{display:grid;gap:16px;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));padding:0;list-style:none;margin:0}.steps li{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:18px}.steps b{display:block;color:#9db8ff;font-size:.8rem;letter-spacing:.12em;margin-bottom:4px}.steps span{color:var(--mu);font-size:.95rem}.hero h1{font-size:clamp(2rem,6vw,3.4rem);line-height:1.1;margin:0 0 14px}
.hero p{max-width:640px;margin:0 auto 26px;color:var(--mu);font-size:1.1rem}
.sr{display:flex;gap:10px;max-width:560px;margin:0 auto;flex-wrap:wrap}
input,select{font:inherit;color:var(--tx);background:var(--card);border:1px solid var(--line);border-radius:12px;padding:10px 14px;min-width:0}
.sr input{flex:1 1 220px}
.pills{display:flex;gap:10px;justify-content:center;flex-wrap:wrap;margin-top:26px;padding:0;list-style:none}
.pills li{border:1px solid var(--line);background:var(--card);padding:6px 14px;border-radius:999px;font-size:.88rem;color:var(--mu)}
section{padding:40px 0}h2{font-size:1.7rem;margin:0 0 6px}.sub{color:var(--mu);margin:0 0 20px}
.tabs{display:flex;gap:8px;overflow-x:auto;padding:4px 0 10px;scrollbar-width:thin}
.tab{flex:0 0 auto;font:inherit;cursor:pointer;color:var(--mu);background:var(--card);border:1px solid var(--line);padding:9px 16px;border-radius:999px}
.tab[aria-selected=true]{color:#fff;border-color:transparent;background:linear-gradient(90deg,var(--blue),var(--vio))}
.tools{display:flex;gap:10px;flex-wrap:wrap;margin:14px 0}.tools input{flex:1 1 200px}
.note{font-size:.88rem;color:var(--mu)}
.grid{display:grid;gap:16px;grid-template-columns:repeat(auto-fill,minmax(300px,1fr));padding:0;list-style:none;margin:16px 0 0}
.card{background:var(--card);border:1px solid var(--line);border-radius:18px;padding:20px;display:flex;flex-direction:column;gap:10px}
.top{display:flex;align-items:center;gap:12px}.pos{width:38px;height:38px;border-radius:12px;display:grid;place-items:center;font-weight:800;background:#1b2347;color:#9db8ff}
.top h3{margin:0;font-size:1.2rem}.score{margin-left:auto;text-align:right;font-weight:700}.score small{display:block;font-weight:400;color:var(--mu);font-size:.72rem}
.badge{align-self:flex-start;font-size:.75rem;color:#fcd34d;border:1px solid #6b5a1a;background:#2a2410;padding:2px 10px;border-radius:999px}
.card{transition:transform .2s,border-color .2s}.card:hover{transform:translateY(-3px);border-color:#4b5bd6}.btn{transition:filter .2s}.btn:hover{filter:brightness(1.12)}.card p{margin:0;color:var(--mu)}.card dl{margin:0;font-size:.9rem}.card dt{font-weight:600;margin-top:6px}.card dd{margin:0;color:var(--mu)}
.card .btn{margin-top:auto;text-align:center}
.empty{border:1px dashed var(--line);border-radius:16px;padding:30px;text-align:center;color:var(--mu)}
.box{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:20px}
code{background:#141414;padding:2px 6px;border-radius:6px;font-size:.88rem;overflow-wrap:anywhere}
table{width:100%;border-collapse:collapse;margin:12px 0}td,th{padding:8px;border-bottom:1px solid var(--line);text-align:left}
ul.t{padding-left:20px;color:var(--mu)}.two{display:grid;gap:16px;grid-template-columns:repeat(auto-fit,minmax(280px,1fr))}
footer{border-top:1px solid var(--line);padding:30px 0;color:var(--mu);font-size:.9rem}footer nav{margin:10px 0}
details{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:12px 16px;margin:0 0 10px}summary{cursor:pointer;font-weight:600;min-height:28px}details p{color:var(--mu);margin:8px 0 0}
.cf{display:grid;gap:8px;max-width:520px}.cf textarea{font:inherit;color:var(--tx);background:var(--bg);border:1px solid var(--line);border-radius:12px;padding:10px 14px}.cf input{background:var(--bg)}.hp{position:absolute;left:-9999px}.cf .btn{justify-self:start}
.fav{background:none;border:0;color:#fcd34d;font-size:1.4rem;cursor:pointer;min-width:44px;min-height:44px}
#topBtn{position:fixed;right:16px;bottom:calc(16px + env(safe-area-inset-bottom,0px));width:46px;height:46px;border-radius:50%;padding:0;display:none}
.herobg{position:relative;overflow:hidden}.herobg canvas{position:absolute;inset:0;width:100%;height:100%;pointer-events:none}.scrim{position:absolute;inset:0;pointer-events:none;background:radial-gradient(115% 95% at 50% 46%,rgba(4,5,12,.68) 0%,rgba(4,5,12,.68) 24%,rgba(4,5,12,.46) 52%,rgba(4,5,12,.12) 100%)}.herobg .hero{position:relative;z-index:2}
h1,h2,h3,.logo{font-family:"Bricolage Grotesque",system-ui,sans-serif}
.hero h1{font-size:clamp(2.6rem,8vw,5rem);font-weight:800;line-height:1;letter-spacing:-.035em;max-width:11ch;margin:0 auto 18px}
.logo{background:none;color:var(--tx);-webkit-text-fill-color:var(--tx);letter-spacing:-.02em}
.btn{background:#4f6bff}.btn.ghost{background:transparent}
.tab{border:0;border-bottom:2px solid transparent;border-radius:0;background:none;padding:10px 14px}.tab:hover{color:var(--tx)}
.tab[aria-selected=true]{background:none;color:#fff;border-bottom-color:#a78bfa}
.grid{column-gap:48px;grid-template-columns:repeat(auto-fill,minmax(340px,1fr))}
.card{background:none;border:0;border-top:1px solid var(--line);border-radius:0;padding:22px 0}.card:hover{transform:none;border-color:var(--line)}
.pos{width:auto;height:auto;min-width:2.2ch;background:none;font:800 2.8rem/1 "Bricolage Grotesque",system-ui,sans-serif;color:#a78bfa}
.herobg{overflow:visible}.herobg canvas{position:fixed;inset:0;width:100%;height:100%;z-index:-1}
.herobg .scrim{position:fixed;inset:0;z-index:-1;background:radial-gradient(120% 100% at 50% 35%,rgba(0,0,0,.74) 0%,rgba(0,0,0,.68) 45%,rgba(0,0,0,.58) 100%)}
.hero p,.sub,.note,.card p,.card dd,.card .score small,details p,ul.t,.steps span,.pills li,.box p,footer,footer p{color:#e2e6f3}
.btn,.btn.ghost,.tab,.tab:hover,.tab[aria-selected=true]{color:#fff}
@media (prefers-reduced-motion:reduce){.lamp{animation:none}.card,.btn{transition:none}.card:hover{transform:none}html{scroll-behavior:auto}}
</style>
</head>
<body>
<header><div class="wrap bar">
 <a class="logo" href="#inicio">IA Rank<span class="tag">Encontre a melhor IA para cada tarefa</span></a>
 <div class="status" role="img" aria-label="Indicador visual decorativo"><span class="lamp" aria-hidden="true"></span>CENTRAL DE IAs</div>
 <nav aria-label="Principal"><a href="#inicio">Início</a><a href="#rankings">Rankings</a><a href="#metodologia">Metodologia</a><a href="#sobre">Sobre</a><a href="#faq">FAQ</a><a href="#contato">Contato</a></nav>
 <a class="btn" href="#rankings">Explorar rankings</a>
</div></header>
<main>
<div class="herobg"><canvas id="fluid" aria-hidden="true" width="1350" height="991"></canvas><div class="scrim" aria-hidden="true"></div>
<div id="inicio" class="hero wrap">
 <h1>Qual é a melhor IA para você?</h1>
 <p>Compare inteligências artificiais, descubra seus pontos fortes e escolha a ferramenta ideal para cada tarefa.</p>
 <form class="sr" id="heroForm" role="search"><label for="heroQ" hidden="">Pesquisar IAs ou categorias</label>
  <input id="heroQ" type="search" placeholder="Pesquisar IAs ou categorias"><button class="btn" type="submit">Ver rankings</button></form>
 <ul class="pills"><li>Várias categorias</li><li>Critérios transparentes</li><li>Planos gratuitos e pagos</li></ul>
</div></div>
<section><div class="wrap"><h2>Como funciona</h2><p class="sub">Três passos para chegar à ferramenta certa.</p>
 <ol class="steps"><li><b>01 · ESCOLHA</b><span>Selecione a categoria que combina com a sua tarefa.</span></li><li><b>02 · COMPARE</b><span>Veja pontos fortes, limitações e planos de cada IA.</span></li><li><b>03 · EXPERIMENTE</b><span>Abra o site oficial e teste a ferramenta por conta própria.</span></li></ol></div></section>
<section id="rankings"><div class="wrap">
 <h2>Rankings por categoria</h2>
 <p class="sub">Escolha uma categoria para ver o ranking correspondente.</p>
 <div class="tabs" role="tablist" aria-label="Categorias" id="tabs"><button class="tab" type="button" id="tab-estudos" role="tab" aria-controls="panel" aria-selected="false" tabindex="-1">Estudos</button><button class="tab" type="button" id="tab-programacao" role="tab" aria-controls="panel" aria-selected="true" tabindex="0">Programação</button><button class="tab" type="button" id="tab-imagens" role="tab" aria-controls="panel" aria-selected="false" tabindex="-1">Criação de imagens</button><button class="tab" type="button" id="tab-videos" role="tab" aria-controls="panel" aria-selected="false" tabindex="-1">Criação de vídeos</button><button class="tab" type="button" id="tab-escrita" role="tab" aria-controls="panel" aria-selected="false" tabindex="-1">Escrita e textos</button><button class="tab" type="button" id="tab-pesquisa" role="tab" aria-controls="panel" aria-selected="false" tabindex="-1">Pesquisa na internet</button><button class="tab" type="button" id="tab-trabalho" role="tab" aria-controls="panel" aria-selected="false" tabindex="-1">Trabalho e produtividade</button><button class="tab" type="button" id="tab-geral" role="tab" aria-controls="panel" aria-selected="false" tabindex="-1">Uso geral</button></div>
 <div class="tools">
  <label for="q" hidden="">Buscar por nome</label><input id="q" type="search" placeholder="Buscar IA pelo nome">
  <label for="plan" hidden="">Filtrar por plano</label>
  <select id="plan"><option value="all">Todos os planos</option><option value="free">Gratuito</option><option value="paid">Pago</option><option value="both">Gratuito e pago</option><option value="verify">Plano a verificar</option><option value="fav">Só favoritos</option></select>
  <label for="sort" hidden="">Ordenar</label>
  <select id="sort"><option value="rank">Ordem do ranking</option><option value="score" disabled="">Maior nota</option></select>
  <button class="btn ghost" id="clear" type="button">Limpar filtros</button>
 </div>
 <p class="note" id="count" role="status" aria-live="polite">9 de 9 ferramentas em Programação · ordenação por nota indisponível: ainda sem notas válidas</p>
 <div id="panel" role="tabpanel" tabindex="0" aria-labelledby="tab-programacao"><ul class="grid"><li class="card"><div class="top"><div class="pos">1</div><h3>ChatGPT</h3><div class="score">Sem nota<small>nota geral</small></div><button class="fav" type="button" aria-pressed="false" aria-label="Favoritar ChatGPT">☆</button></div><span class="badge">Exemplo ilustrativo — ainda não testado</span><p>Informação a verificar</p><dl><dt>Vantagens</dt><dd>Informação a verificar</dd><dt>Desvantagens</dt><dd>Informação a verificar</dd><dt>Plano</dt><dd>A verificar</dd><dt>Melhor para</dt><dd>Informação a verificar</dd><dt>Última avaliação</dt><dd>Ainda não avaliada</dd></dl><a class="btn" href="https://chatgpt.com" target="_blank" rel="noopener noreferrer" aria-label="Conhecer ChatGPT (abre em nova aba)">Conhecer IA</a></li><li class="card"><div class="top"><div class="pos">2</div><h3>Claude</h3><div class="score">Sem nota<small>nota geral</small></div><button class="fav" type="button" aria-pressed="false" aria-label="Favoritar Claude">☆</button></div><span class="badge">Exemplo ilustrativo — ainda não testado</span><p>Informação a verificar</p><dl><dt>Vantagens</dt><dd>Informação a verificar</dd><dt>Desvantagens</dt><dd>Informação a verificar</dd><dt>Plano</dt><dd>A verificar</dd><dt>Melhor para</dt><dd>Informação a verificar</dd><dt>Última avaliação</dt><dd>Ainda não avaliada</dd></dl><a class="btn" href="https://claude.ai" target="_blank" rel="noopener noreferrer" aria-label="Conhecer Claude (abre em nova aba)">Conhecer IA</a></li><li class="card"><div class="top"><div class="pos">3</div><h3>Google Gemini</h3><div class="score">Sem nota<small>nota geral</small></div><button class="fav" type="button" aria-pressed="false" aria-label="Favoritar Google Gemini">☆</button></div><span class="badge">Exemplo ilustrativo — ainda não testado</span><p>Informação a verificar</p><dl><dt>Vantagens</dt><dd>Informação a verificar</dd><dt>Desvantagens</dt><dd>Informação a verificar</dd><dt>Plano</dt><dd>A verificar</dd><dt>Melhor para</dt><dd>Informação a verificar</dd><dt>Última avaliação</dt><dd>Ainda não avaliada</dd></dl><a class="btn" href="https://gemini.google.com" target="_blank" rel="noopener noreferrer" aria-label="Conhecer Google Gemini (abre em nova aba)">Conhecer IA</a></li><li class="card"><div class="top"><div class="pos">4</div><h3>GitHub Copilot</h3><div class="score">Sem nota<small>nota geral</small></div><button class="fav" type="button" aria-pressed="false" aria-label="Favoritar GitHub Copilot">☆</button></div><span class="badge">Exemplo ilustrativo — ainda não testado</span><p>Informação a verificar</p><dl><dt>Vantagens</dt><dd>Informação a verificar</dd><dt>Desvantagens</dt><dd>Informação a verificar</dd><dt>Plano</dt><dd>A verificar</dd><dt>Melhor para</dt><dd>Informação a verificar</dd><dt>Última avaliação</dt><dd>Ainda não avaliada</dd></dl><a class="btn" href="https://github.com/features/copilot" target="_blank" rel="noopener noreferrer" aria-label="Conhecer GitHub Copilot (abre em nova aba)">Conhecer IA</a></li><li class="card"><div class="top"><div class="pos">5</div><h3>Cursor</h3><div class="score">Sem nota<small>nota geral</small></div><button class="fav" type="button" aria-pressed="false" aria-label="Favoritar Cursor">☆</button></div><span class="badge">Exemplo ilustrativo — ainda não testado</span><p>Informação a verificar</p><dl><dt>Vantagens</dt><dd>Informação a verificar</dd><dt>Desvantagens</dt><dd>Informação a verificar</dd><dt>Plano</dt><dd>A verificar</dd><dt>Melhor para</dt><dd>Informação a verificar</dd><dt>Última avaliação</dt><dd>Ainda não avaliada</dd></dl><a class="btn" href="https://cursor.com" target="_blank" rel="noopener noreferrer" aria-label="Conhecer Cursor (abre em nova aba)">Conhecer IA</a></li><li class="card"><div class="top"><div class="pos">6</div><h3>Windsurf</h3><div class="score">Sem nota<small>nota geral</small></div><button class="fav" type="button" aria-pressed="false" aria-label="Favoritar Windsurf">☆</button></div><span class="badge">Exemplo ilustrativo — ainda não testado</span><p>Informação a verificar</p><dl><dt>Vantagens</dt><dd>Informação a verificar</dd><dt>Desvantagens</dt><dd>Informação a verificar</dd><dt>Plano</dt><dd>A verificar</dd><dt>Melhor para</dt><dd>Informação a verificar</dd><dt>Última avaliação</dt><dd>Ainda não avaliada</dd></dl><a class="btn" href="https://windsurf.com" target="_blank" rel="noopener noreferrer" aria-label="Conhecer Windsurf (abre em nova aba)">Conhecer IA</a></li><li class="card"><div class="top"><div class="pos">7</div><h3>Replit</h3><div class="score">Sem nota<small>nota geral</small></div><button class="fav" type="button" aria-pressed="false" aria-label="Favoritar Replit">☆</button></div><span class="badge">Exemplo ilustrativo — ainda não testado</span><p>Informação a verificar</p><dl><dt>Vantagens</dt><dd>Informação a verificar</dd><dt>Desvantagens</dt><dd>Informação a verificar</dd><dt>Plano</dt><dd>A verificar</dd><dt>Melhor para</dt><dd>Informação a verificar</dd><dt>Última avaliação</dt><dd>Ainda não avaliada</dd></dl><a class="btn" href="https://replit.com" target="_blank" rel="noopener noreferrer" aria-label="Conhecer Replit (abre em nova aba)">Conhecer IA</a></li><li class="card"><div class="top"><div class="pos">8</div><h3>Lovable</h3><div class="score">Sem nota<small>nota geral</small></div><button class="fav" type="button" aria-pressed="false" aria-label="Favoritar Lovable">☆</button></div><span class="badge">Exemplo ilustrativo — ainda não testado</span><p>Informação a verificar</p><dl><dt>Vantagens</dt><dd>Informação a verificar</dd><dt>Desvantagens</dt><dd>Informação a verificar</dd><dt>Plano</dt><dd>A verificar</dd><dt>Melhor para</dt><dd>Informação a verificar</dd><dt>Última avaliação</dt><dd>Ainda não avaliada</dd></dl><a class="btn" href="https://lovable.dev" target="_blank" rel="noopener noreferrer" aria-label="Conhecer Lovable (abre em nova aba)">Conhecer IA</a></li><li class="card"><div class="top"><div class="pos">9</div><h3>DeepSeek</h3><div class="score">Sem nota<small>nota geral</small></div><button class="fav" type="button" aria-pressed="false" aria-label="Favoritar DeepSeek">☆</button></div><span class="badge">Exemplo ilustrativo — ainda não testado</span><p>Informação a verificar</p><dl><dt>Vantagens</dt><dd>Informação a verificar</dd><dt>Desvantagens</dt><dd>Informação a verificar</dd><dt>Plano</dt><dd>A verificar</dd><dt>Melhor para</dt><dd>Informação a verificar</dd><dt>Última avaliação</dt><dd>Ainda não avaliada</dd></dl><a class="btn" href="https://chat.deepseek.com" target="_blank" rel="noopener noreferrer" aria-label="Conhecer DeepSeek (abre em nova aba)">Conhecer IA</a></li></ul></div>
</div></section>
<section id="metodologia"><div class="wrap two">
 <div class="box"><h2>Como calculamos os rankings</h2>
  <p class="sub">Categoria inicial: Estudos. A nota final é uma média ponderada das notas (de 0 a 10) de cada critério.</p>
  <table><caption hidden="">Critérios</caption><tbody><tr><th>Critério</th><th>Peso</th></tr>
  <tr><td>Qualidade das explicações</td><td>30%</td></tr><tr><td>Precisão das respostas</td><td>25%</td></tr><tr><td>Utilidade para aprender</td><td>20%</td></tr><tr><td>Recursos gratuitos</td><td>15%</td></tr><tr><td>Facilidade de uso</td><td>10%</td></tr></tbody></table>
  <p><code>Nota final = (explicações × 0,30) + (precisão × 0,25) + (aprendizagem × 0,20) + (recursos gratuitos × 0,15) + (facilidade × 0,10)</code></p>
  <p class="note">Os pesos podem variar conforme a categoria. Resultados só serão apresentados como avaliações reais após testes consistentes.</p></div>
 <div class="box"><h2>Transparência</h2>
  <ul class="t"><li>As ferramentas ainda não foram testadas: os cartões são exemplos ilustrativos e não trazem notas.</li>
  <li>Última revisão dos rankings: <span id="rev">nenhuma até agora, pois os rankings ainda não foram testados.</span></li>
  <li>Planos gratuitos podem ter limites de uso.</li>
  <li>Resultados dependem da tarefa e podem mudar com atualizações.</li>
  <li>No futuro o site poderá receber comissões por links de afiliados, sempre informado com clareza. Hoje não há parcerias com empresas.</li></ul></div>
</div></section>
<section id="sobre"><div class="wrap box"><h2>Sobre o IA Rank</h2>
 <p class="sub">Projeto para ajudar pessoas a descobrir qual IA combina com cada necessidade. Esta versão é um protótipo funcional com dados demonstrativos.</p></div></section>
<section id="faq"><div class="wrap"><h2>Perguntas frequentes</h2><p class="sub">Respostas para as dúvidas mais comuns.</p>
 <details><summary>As notas são resultados de testes reais?</summary><p>Ainda não. Os cartões atuais são exemplos ilustrativos e não trazem notas. Só mostraremos notas depois de testes consistentes.</p></details>
 <details><summary>As ferramentas são gratuitas?</summary><p>Cada ferramenta tem sua política de planos, que pode mudar e ter limites. Por isso o plano aparece como “A verificar” até ser confirmado no site oficial.</p></details>
 <details><summary>O IA Rank tem parceria com alguma empresa?</summary><p>Não. Se um dia houver links de afiliados, isso será informado com clareza.</p></details>
 <details><summary>Preciso criar conta?</summary><p>Não. Não há cadastro nem login nesta versão.</p></details>
 <details><summary>Onde ficam meus favoritos?</summary><p>Apenas no armazenamento do seu navegador, neste aparelho. Eles não são enviados a nenhum servidor.</p></details>
</div></section>
<section id="contato"><div class="wrap box"><h2>Contato</h2>
 <p class="sub">Formulário de demonstração. Esta versão não tem servidor, então nenhuma mensagem é enviada. E-mail de atendimento: [placeholder — ainda não definido].</p>
 <form id="cf" novalidate="" class="cf">
  <label for="cn">Nome</label><input id="cn" name="nome" autocomplete="name" required="">
  <label for="ce">E-mail</label><input id="ce" name="email" type="email" autocomplete="email" required="">
  <label for="cm">Mensagem</label><textarea id="cm" name="msg" rows="4" required=""></textarea>
  <input class="hp" name="site" tabindex="-1" autocomplete="off" aria-hidden="true">
  <p id="cs" role="status" aria-live="polite" class="note"></p>
  <button class="btn" type="submit">Enviar mensagem</button>
 </form></div></section>
<section id="privacidade"><div class="wrap"><h2>Informações legais</h2><p class="sub">Rascunho: revise com um profissional jurídico antes de publicar de verdade.</p>
 <details open=""><summary>Política de privacidade</summary><p>Esta versão não exige cadastro, não usa análise de visitas e não envia dados a servidores. Favoritos ficam só no seu navegador. Os links levam a sites de terceiros, com políticas próprias.</p></details>
 <details open=""><summary>Termos de uso</summary><p>O conteúdo é informativo e de demonstração, sem garantia de exatidão. Resultados dependem da tarefa e podem mudar. As ferramentas pertencem aos respectivos fabricantes.</p></details>
 <details open=""><summary>Cookies</summary><p>O site não usa cookies. Usa apenas o armazenamento local do navegador para guardar seus favoritos.</p></details>
</div></section>
</main>
<footer><div class="wrap"><strong>IA Rank</strong>
 <nav aria-label="Rodapé"><a href="#inicio">Início</a><a href="#rankings">Rankings</a><a href="#metodologia">Metodologia</a><a href="#sobre">Sobre</a><a href="#faq">FAQ</a><a href="#contato">Contato</a><a href="#privacidade">Privacidade e termos</a></nav>
 <p><button class="btn ghost" id="share" type="button">Compartilhar o site</button> <span class="note" id="shs" role="status"></span></p>
 <p>As ferramentas citadas pertencem aos respectivos fabricantes.</p>
 <p>Contato: [placeholder — contato ainda não definido]</p>
 <p>© <span id="year">2026</span> IA Rank</p></div></footer>
<button class="btn" id="topBtn" type="button" aria-label="Voltar ao topo" style="display: none;">↑</button>
<script>
// ===== Dados (separados da interface) =====
var DEMO="Exemplo ilustrativo — ainda não testado";
var LAST_REVIEW=null; // preencha com uma data (ex.: "2026-11-01") só depois de testes reais
function t(name,url,use){return{name:name,url:url,score:null,plan:"verify",use:use||"Informação a verificar",desc:"Informação a verificar",pros:"Informação a verificar",cons:"Informação a verificar",date:null}}
var CHATGPT=["ChatGPT","https://chatgpt.com"],GEM=["Google Gemini","https://gemini.google.com"],CLA=["Claude","https://claude.ai"],PPX=["Perplexity","https://www.perplexity.ai"],COP=["Microsoft Copilot","https://copilot.microsoft.com"];
function T(a,u){return t(a[0],a[1],u)}
var DS=["DeepSeek","https://chat.deepseek.com"],GROK=["Grok","https://grok.com"],MIS=["Le Chat (Mistral)","https://chat.mistral.ai"];
var CATS=[
{id:"estudos",label:"Estudos",items:[T(CHATGPT,"Estudos"),T(GEM,"Estudos"),t("NotebookLM","https://notebooklm.google.com","Estudos"),T(PPX,"Estudos"),T(CLA,"Estudos"),T(COP,"Estudos"),t("Khanmigo","https://www.khanmigo.ai","Estudos"),t("Quizlet","https://quizlet.com","Estudos"),T(DS,"Estudos"),T(MIS,"Estudos")]},
{id:"programacao",label:"Programação",items:[T(CHATGPT),T(CLA),T(GEM),t("GitHub Copilot","https://github.com/features/copilot"),t("Cursor","https://cursor.com"),t("Windsurf","https://windsurf.com"),t("Replit","https://replit.com"),t("Lovable","https://lovable.dev"),T(DS)]},
{id:"imagens",label:"Criação de imagens",items:[t("Midjourney","https://www.midjourney.com"),t("Adobe Firefly","https://firefly.adobe.com"),t("Ideogram","https://ideogram.ai"),T(CHATGPT),T(GEM),t("Leonardo AI","https://leonardo.ai"),t("Stability AI","https://stability.ai"),t("Microsoft Designer","https://designer.microsoft.com"),t("Krea","https://www.krea.ai"),t("Canva","https://www.canva.com")]},
{id:"videos",label:"Criação de vídeos",items:[t("Runway","https://runwayml.com"),t("Pika","https://pika.art"),t("Kling AI","https://klingai.com"),t("Sora","https://openai.com/sora"),t("Google Veo","https://deepmind.google/models/veo/"),t("Luma Dream Machine","https://lumalabs.ai/dream-machine"),t("HeyGen","https://www.heygen.com"),t("Synthesia","https://www.synthesia.io"),t("CapCut","https://www.capcut.com")]},
{id:"escrita",label:"Escrita e textos",items:[T(CLA),T(CHATGPT),T(GEM),T(COP),t("Grammarly","https://www.grammarly.com"),t("Jasper","https://www.jasper.ai"),t("QuillBot","https://quillbot.com"),t("DeepL Write","https://www.deepl.com/write")]},
{id:"pesquisa",label:"Pesquisa na internet",items:[T(PPX),T(GEM),T(CHATGPT),T(COP),T(CLA),T(GROK),t("You.com","https://you.com"),t("Consensus","https://consensus.app"),t("Elicit","https://elicit.com"),t("Phind","https://www.phind.com")]},
{id:"trabalho",label:"Trabalho e produtividade",items:[T(COP),t("Notion AI","https://www.notion.com/product/ai"),T(GEM),T(CHATGPT),T(CLA),t("Otter.ai","https://otter.ai"),t("Fireflies.ai","https://fireflies.ai"),t("Zapier","https://zapier.com"),t("Gamma","https://gamma.app")]},
{id:"geral",label:"Uso geral",items:[T(CHATGPT),T(GEM),T(CLA),T(COP),T(PPX),T(GROK),T(DS),T(MIS),t("Meta AI","https://www.meta.ai")]}
];

var PLAN={free:"Gratuito",paid:"Pago",both:"Gratuito e pago",verify:"A verificar"};
function validScore(s){return typeof s==="number"&&isFinite(s)&&s>=0&&s<=10}
var favs=[];try{favs=JSON.parse(localStorage.getItem("iarank-favs")||"[]");if(!Array.isArray(favs))favs=[]}catch(e){favs=[]}
function isFav(n){return favs.indexOf(n)>-1}
function toggleFav(n){var i=favs.indexOf(n);if(i>-1)favs.splice(i,1);else favs.push(n);try{localStorage.setItem("iarank-favs",JSON.stringify(favs))}catch(e){}}
// ===== Estado e interface =====
var cur=0,$=function(i){return document.getElementById(i)};
var tabs=$("tabs"),panel=$("panel"),q=$("q"),plan=$("plan"),sort=$("sort");
CATS.forEach(function(c,i){var b=document.createElement("button");b.className="tab";b.type="button";b.id="tab-"+c.id;b.setAttribute("role","tab");b.setAttribute("aria-controls","panel");b.textContent=c.label;
 b.onclick=function(){select(i,false)};
 b.onkeydown=function(e){var n=i;if(e.key==="ArrowRight")n=(i+1)%CATS.length;else if(e.key==="ArrowLeft")n=(i+CATS.length-1)%CATS.length;else if(e.key==="Home")n=0;else if(e.key==="End")n=CATS.length-1;else return;e.preventDefault();select(n,true)};
 tabs.appendChild(b)});
panel.id="panel";
function select(i,focus){cur=i;[].forEach.call(tabs.children,function(b,k){var on=k===i;b.setAttribute("aria-selected",on);b.tabIndex=on?0:-1;if(on&&focus)b.focus()});panel.setAttribute("aria-labelledby","tab-"+CATS[i].id);render()}
function el(tag,cls,txt){var e=document.createElement(tag);if(cls)e.className=cls;if(txt!=null)e.textContent=txt;return e}
function row(dl,k,v){dl.appendChild(el("dt",null,k));dl.appendChild(el("dd",null,v))}
function render(){
 var c=CATS[cur],term=q.value.trim().toLowerCase(),pf=plan.value;
 var list=c.items.map(function(x,i){return{x:x,pos:i+1}}).filter(function(o){
  return(!term||o.x.name.toLowerCase().indexOf(term)>-1)&&(pf==="all"||(pf==="fav"?isFav(o.x.name):o.x.plan===pf))});
 var hasScores=c.items.some(function(x){return validScore(x.score)});
 sort.querySelector("[value=score]").disabled=!hasScores;
 if(!hasScores&&sort.value==="score")sort.value="rank";
 if(sort.value==="score")list.sort(function(a,b){return(validScore(b.x.score)?b.x.score:-1)-(validScore(a.x.score)?a.x.score:-1)});
 panel.textContent="";
 $("count").textContent=list.length+" de "+c.items.length+" ferramentas em "+c.label+(hasScores?"":" · ordenação por nota indisponível: ainda sem notas válidas");
 if(!list.length){var e=el("div","empty","Nenhuma IA encontrada com esses filtros. Tente outro nome ou limpe os filtros.");panel.appendChild(e);return}
 var ul=el("ul","grid");
 list.forEach(function(o){var x=o.x,li=el("li","card"),top=el("div","top");
  top.appendChild(el("div","pos",o.pos));top.appendChild(el("h3",null,x.name));
  var s=el("div","score",validScore(x.score)?x.score.toFixed(1)+" / 10":"Sem nota");s.appendChild(el("small",null,"nota geral"));top.appendChild(s);
  var f=el("button","fav",isFav(x.name)?"★":"☆");f.type="button";f.setAttribute("aria-pressed",String(isFav(x.name)));f.setAttribute("aria-label","Favoritar "+x.name);f.onclick=function(){toggleFav(x.name);render()};top.appendChild(f);
  li.appendChild(top);li.appendChild(el("span","badge",DEMO));li.appendChild(el("p",null,x.desc));
  var dl=el("dl");row(dl,"Vantagens",x.pros);row(dl,"Desvantagens",x.cons);row(dl,"Plano",PLAN[x.plan]||PLAN.verify);row(dl,"Melhor para",x.use);row(dl,"Última avaliação",x.date||"Ainda não avaliada");
  li.appendChild(dl);
  var a=el("a","btn","Conhecer IA");a.href=x.url;a.target="_blank";a.rel="noopener noreferrer";a.setAttribute("aria-label","Conhecer "+x.name+" (abre em nova aba)");li.appendChild(a);ul.appendChild(li)});
 panel.appendChild(ul)}
q.oninput=plan.onchange=sort.onchange=render;
$("clear").onclick=function(){q.value="";plan.value="all";sort.value="rank";render();q.focus()};
$("heroForm").onsubmit=function(e){e.preventDefault();var v=$("heroQ").value.trim().toLowerCase();
 if(v){var k=CATS.findIndex(function(c){return c.label.toLowerCase().indexOf(v)>-1});
  if(k>-1){q.value="";select(k,false)}else q.value=$("heroQ").value.trim()}
 render();$("rankings").scrollIntoView()};
$("year").textContent=new Date().getFullYear();
$("rev").textContent=LAST_REVIEW?new Date(LAST_REVIEW+"T00:00:00").toLocaleDateString("pt-BR")+".":"nenhuma até agora, pois os rankings ainda não foram testados.";
$("cf").onsubmit=function(e){e.preventDefault();var s=$("cs"),n=$("cn").value.trim(),m=$("ce").value.trim(),g=$("cm").value.trim();
 if(!n||!g){s.textContent="Preencha seu nome e a mensagem.";return}
 if(!/^[^@\s]+@[^@\s]+\.[^@\s]+$/.test(m)){s.textContent="Digite um e-mail válido, como nome@exemplo.com.";return}
 s.textContent="Dados válidos, mas o envio ainda não está configurado: nenhuma mensagem foi enviada."};
var tb=$("topBtn");window.addEventListener("scroll",function(){tb.style.display=window.scrollY>600?"block":"none"},{passive:true});
tb.onclick=function(){window.scrollTo({top:0})};
$("share").onclick=function(){var s=$("shs"),u=location.href;
 if(navigator.share){navigator.share({title:"IA Rank",url:u}).catch(function(){})}
 else if(navigator.clipboard){navigator.clipboard.writeText(u).then(function(){s.textContent="Link copiado."},function(){s.textContent="Não foi possível copiar o link."})}
 else s.textContent="Copie o endereço na barra do navegador."};
select(0,false);
// ===== Fundo: simulação de fluido WebGL (só roda se o visitante não pediu menos movimento) =====
function fluidSimulation(canvas){
 canvas.width=canvas.clientWidth;canvas.height=canvas.clientHeight;
 var config={SIM_RESOLUTION:200,DYE_RESOLUTION:512,DENSITY_DISSIPATION:.958,VELOCITY_DISSIPATION:.96,PRESSURE_DISSIPATION:.8,PRESSURE_ITERATIONS:20,CURL:42,SPLAT_RADIUS:.22,SHADING:true,COLORFUL:true,BACK:[0,0,0]};
 function PointerP(){this.id=-1;this.x=0;this.y=0;this.dx=0;this.dy=0;this.down=false;this.moved=false;this.color={r:.1,g:0,b:1}}
 var pointers=[new PointerP()],splatStack=[];
 var params={alpha:true,depth:false,stencil:false,antialias:false,preserveDrawingBuffer:false};
 var gl=canvas.getContext("webgl2",params),isW2=!!gl;
 if(!isW2)gl=canvas.getContext("webgl",params)||canvas.getContext("experimental-webgl",params);
 if(!gl)return function(){};
 var halfFloat,linear;
 if(isW2){gl.getExtension("EXT_color_buffer_float");linear=gl.getExtension("OES_texture_float_linear")}
 else{halfFloat=gl.getExtension("OES_texture_half_float");linear=gl.getExtension("OES_texture_half_float_linear")}
 if(!isW2&&!halfFloat)return function(){};
 var texType=isW2?gl.HALF_FLOAT:halfFloat.HALF_FLOAT_OES;
 function okFmt(i,f){var t=gl.createTexture();gl.bindTexture(gl.TEXTURE_2D,t);gl.texParameteri(gl.TEXTURE_2D,gl.TEXTURE_MIN_FILTER,gl.NEAREST);gl.texParameteri(gl.TEXTURE_2D,gl.TEXTURE_MAG_FILTER,gl.NEAREST);gl.texParameteri(gl.TEXTURE_2D,gl.TEXTURE_WRAP_S,gl.CLAMP_TO_EDGE);gl.texParameteri(gl.TEXTURE_2D,gl.TEXTURE_WRAP_T,gl.CLAMP_TO_EDGE);gl.texImage2D(gl.TEXTURE_2D,0,i,4,4,0,f,texType,null);var b=gl.createFramebuffer();gl.bindFramebuffer(gl.FRAMEBUFFER,b);gl.framebufferTexture2D(gl.FRAMEBUFFER,gl.COLOR_ATTACHMENT0,gl.TEXTURE_2D,t,0);return gl.checkFramebufferStatus(gl.FRAMEBUFFER)==gl.FRAMEBUFFER_COMPLETE}
 function fmt(i,f){if(!okFmt(i,f)){if(i==gl.R16F)return fmt(gl.RG16F,gl.RG);if(i==gl.RG16F)return fmt(gl.RGBA16F,gl.RGBA);return null}return{internalFormat:i,format:f}}
 var fRGBA,fRG,fR;
 if(isW2){fRGBA=fmt(gl.RGBA16F,gl.RGBA);fRG=fmt(gl.RG16F,gl.RG);fR=fmt(gl.R16F,gl.RED)}else{fRGBA=fRG=fR=fmt(gl.RGBA,gl.RGBA)}
 if(!fRGBA||!fRG||!fR)return function(){};
 if(/Mobi|Android/i.test(navigator.userAgent)||!linear)config.SHADING=false;
 gl.clearColor(0,0,0,1);
 function GLP(vs,fs){this.u={};this.p=gl.createProgram();gl.attachShader(this.p,vs);gl.attachShader(this.p,fs);gl.bindAttribLocation(this.p,0,"aPosition");gl.linkProgram(this.p);if(!gl.getProgramParameter(this.p,gl.LINK_STATUS))throw gl.getProgramInfoLog(this.p);var n=gl.getProgramParameter(this.p,gl.ACTIVE_UNIFORMS);for(var i=0;i<n;i++){var nm=gl.getActiveUniform(this.p,i).name;this.u[nm]=gl.getUniformLocation(this.p,nm)}}
 GLP.prototype.bind=function(){gl.useProgram(this.p)};
 function sh(t,s){var o=gl.createShader(t);gl.shaderSource(o,s);gl.compileShader(o);if(!gl.getShaderParameter(o,gl.COMPILE_STATUS))throw gl.getShaderInfoLog(o);return o}
 var NB="varying highp vec2 vUv;varying highp vec2 vL;varying highp vec2 vR;varying highp vec2 vT;varying highp vec2 vB;";
 var vs=sh(gl.VERTEX_SHADER,"precision highp float;attribute vec2 aPosition;"+NB+"uniform vec2 texelSize;void main(){vUv=aPosition*.5+.5;vL=vUv-vec2(texelSize.x,0.);vR=vUv+vec2(texelSize.x,0.);vT=vUv+vec2(0.,texelSize.y);vB=vUv-vec2(0.,texelSize.y);gl_Position=vec4(aPosition,0.,1.);}");
 function fs(src){return sh(gl.FRAGMENT_SHADER,src)}
 var H="precision highp float;precision highp sampler2D;"+NB;
 var clearP=new GLP(vs,fs(H+"uniform sampler2D uTexture;uniform float value;void main(){gl_FragColor=value*texture2D(uTexture,vUv);}"));
 var colorP=new GLP(vs,fs("precision mediump float;uniform vec4 color;void main(){gl_FragColor=color;}"));
 var displayP=new GLP(vs,fs(H+"uniform sampler2D uTexture;void main(){vec3 C=texture2D(uTexture,vUv).rgb;float a=max(C.r,max(C.g,C.b));gl_FragColor=vec4(C,a);}"));
 var shadeP=new GLP(vs,fs(H+"uniform sampler2D uTexture;uniform vec2 texelSize;void main(){vec3 L=texture2D(uTexture,vL).rgb;vec3 R=texture2D(uTexture,vR).rgb;vec3 T=texture2D(uTexture,vT).rgb;vec3 B=texture2D(uTexture,vB).rgb;vec3 C=texture2D(uTexture,vUv).rgb;float dx=length(R)-length(L);float dy=length(T)-length(B);vec3 n=normalize(vec3(dx,dy,length(texelSize)));vec3 l=vec3(0.,0.,1.);float diffuse=clamp(dot(n,l)+.7,.7,1.);C.rgb*=diffuse;float a=max(C.r,max(C.g,C.b));gl_FragColor=vec4(C,a);}"));
 var splatP=new GLP(vs,fs(H+"uniform sampler2D uTarget;uniform float aspectRatio;uniform vec3 color;uniform vec2 point;uniform float radius;void main(){vec2 p=vUv-point.xy;p.x*=aspectRatio;vec3 splat=exp(-dot(p,p)/radius)*color;vec3 base=texture2D(uTarget,vUv).xyz;gl_FragColor=vec4(base+splat,1.);}"));
 var advP=new GLP(vs,fs(H+"uniform sampler2D uVelocity;uniform sampler2D uSource;uniform vec2 texelSize;uniform float dt;uniform float dissipation;void main(){vec2 coord=vUv-dt*texture2D(uVelocity,vUv).xy*texelSize;gl_FragColor=dissipation*texture2D(uSource,coord);gl_FragColor.a=1.;}"));
 var divP=new GLP(vs,fs(H+"uniform sampler2D uVelocity;void main(){float L=texture2D(uVelocity,vL).x;float R=texture2D(uVelocity,vR).x;float T=texture2D(uVelocity,vT).y;float B=texture2D(uVelocity,vB).y;vec2 C=texture2D(uVelocity,vUv).xy;if(vL.x<0.){L=-C.x;}if(vR.x>1.){R=-C.x;}if(vT.y>1.){T=-C.y;}if(vB.y<0.){B=-C.y;}gl_FragColor=vec4(.5*(R-L+T-B),0.,0.,1.);}"));
 var curlP=new GLP(vs,fs(H+"uniform sampler2D uVelocity;void main(){float L=texture2D(uVelocity,vL).y;float R=texture2D(uVelocity,vR).y;float T=texture2D(uVelocity,vT).x;float B=texture2D(uVelocity,vB).x;gl_FragColor=vec4(.5*(R-L-T+B),0.,0.,1.);}"));
 var vortP=new GLP(vs,fs(H+"uniform sampler2D uVelocity;uniform sampler2D uCurl;uniform float curl;uniform float dt;void main(){float L=texture2D(uCurl,vL).x;float R=texture2D(uCurl,vR).x;float T=texture2D(uCurl,vT).x;float B=texture2D(uCurl,vB).x;float C=texture2D(uCurl,vUv).x;vec2 force=.5*vec2(abs(T)-abs(B),abs(R)-abs(L));force/=length(force)+.0001;force*=curl*C;force.y*=-1.;vec2 vel=texture2D(uVelocity,vUv).xy;gl_FragColor=vec4(vel+force*dt,0.,1.);}"));
 var presP=new GLP(vs,fs(H+"uniform sampler2D uPressure;uniform sampler2D uDivergence;void main(){float L=texture2D(uPressure,vL).x;float R=texture2D(uPressure,vR).x;float T=texture2D(uPressure,vT).x;float B=texture2D(uPressure,vB).x;float d=texture2D(uDivergence,vUv).x;gl_FragColor=vec4((L+R+B+T-d)*.25,0.,0.,1.);}"));
 var gradP=new GLP(vs,fs(H+"uniform sampler2D uPressure;uniform sampler2D uVelocity;void main(){float L=texture2D(uPressure,vL).x;float R=texture2D(uPressure,vR).x;float T=texture2D(uPressure,vT).x;float B=texture2D(uPressure,vB).x;vec2 v=texture2D(uVelocity,vUv).xy;v.xy-=vec2(R-L,T-B);gl_FragColor=vec4(v,0.,1.);}"));
 var blit=(function(){gl.bindBuffer(gl.ARRAY_BUFFER,gl.createBuffer());gl.bufferData(gl.ARRAY_BUFFER,new Float32Array([-1,-1,-1,1,1,1,1,-1]),gl.STATIC_DRAW);gl.bindBuffer(gl.ELEMENT_ARRAY_BUFFER,gl.createBuffer());gl.bufferData(gl.ELEMENT_ARRAY_BUFFER,new Uint16Array([0,1,2,0,2,3]),gl.STATIC_DRAW);gl.vertexAttribPointer(0,2,gl.FLOAT,false,0,0);gl.enableVertexAttribArray(0);return function(d){gl.bindFramebuffer(gl.FRAMEBUFFER,d);gl.drawElements(gl.TRIANGLES,6,gl.UNSIGNED_SHORT,0)}})();
 function createFBO(w,h,f,filter){gl.activeTexture(gl.TEXTURE0);var t=gl.createTexture();gl.bindTexture(gl.TEXTURE_2D,t);gl.texParameteri(gl.TEXTURE_2D,gl.TEXTURE_MIN_FILTER,filter);gl.texParameteri(gl.TEXTURE_2D,gl.TEXTURE_MAG_FILTER,filter);gl.texParameteri(gl.TEXTURE_2D,gl.TEXTURE_WRAP_S,gl.CLAMP_TO_EDGE);gl.texParameteri(gl.TEXTURE_2D,gl.TEXTURE_WRAP_T,gl.CLAMP_TO_EDGE);gl.texImage2D(gl.TEXTURE_2D,0,f.internalFormat,w,h,0,f.format,texType,null);var fbo=gl.createFramebuffer();gl.bindFramebuffer(gl.FRAMEBUFFER,fbo);gl.framebufferTexture2D(gl.FRAMEBUFFER,gl.COLOR_ATTACHMENT0,gl.TEXTURE_2D,t,0);gl.viewport(0,0,w,h);gl.clear(gl.COLOR_BUFFER_BIT);return{texture:t,fbo:fbo,width:w,height:h,attach:function(id){gl.activeTexture(gl.TEXTURE0+id);gl.bindTexture(gl.TEXTURE_2D,t);return id}}}
 function createDouble(w,h,f,filter){var a=createFBO(w,h,f,filter),b=createFBO(w,h,f,filter);return{get read(){return a},set read(v){a=v},get write(){return b},set write(v){b=v},swap:function(){var t=a;a=b;b=t}}}
 function resizeDouble(tg,w,h,f,filter){var n=createFBO(w,h,f,filter);clearP.bind();gl.uniform1i(clearP.u.uTexture,tg.read.attach(0));gl.uniform1f(clearP.u.value,1);blit(n.fbo);tg.read=n;tg.write=createFBO(w,h,f,filter);return tg}
 function getRes(r){var a=gl.drawingBufferWidth/gl.drawingBufferHeight;if(a<1)a=1/a;var mx=Math.round(r*a),mn=Math.round(r);return gl.drawingBufferWidth>gl.drawingBufferHeight?{width:mx,height:mn}:{width:mn,height:mx}}
 var sw,sh2,dw,dh,density,velocity,divergence,curl,pressure;
 function initFB(){var s=getRes(config.SIM_RESOLUTION),d=getRes(config.DYE_RESOLUTION);sw=s.width;sh2=s.height;dw=d.width;dh=d.height;var fl=linear?gl.LINEAR:gl.NEAREST;
  density=density?resizeDouble(density,dw,dh,fRGBA,fl):createDouble(dw,dh,fRGBA,fl);
  velocity=velocity?resizeDouble(velocity,sw,sh2,fRG,fl):createDouble(sw,sh2,fRG,fl);
  divergence=createFBO(sw,sh2,fR,gl.NEAREST);curl=createFBO(sw,sh2,fR,gl.NEAREST);pressure=createDouble(sw,sh2,fR,gl.NEAREST)}
 function HSV(h,s,v){var r,g,b,i=Math.floor(h*6),f=h*6-i,p=v*(1-s),q=v*(1-f*s),t=v*(1-(1-f)*s);switch(i%6){case 0:r=v;g=t;b=p;break;case 1:r=q;g=v;b=p;break;case 2:r=p;g=v;b=t;break;case 3:r=p;g=q;b=v;break;case 4:r=t;g=p;b=v;break;default:r=v;g=p;b=q}return{r:r,g:g,b:b}}
 function genColor(){var c=HSV(.27+Math.random()*.2,.95,1);c.r*=.92;c.g*=.92;c.b*=.92;return c}
 function splat(x,y,dx,dy,c){gl.viewport(0,0,sw,sh2);splatP.bind();gl.uniform1i(splatP.u.uTarget,velocity.read.attach(0));gl.uniform1f(splatP.u.aspectRatio,canvas.width/canvas.height);gl.uniform2f(splatP.u.point,x/canvas.width,1-y/canvas.height);gl.uniform3f(splatP.u.color,dx,-dy,1);gl.uniform1f(splatP.u.radius,config.SPLAT_RADIUS/100);blit(velocity.write.fbo);velocity.swap();
  gl.viewport(0,0,dw,dh);gl.uniform1i(splatP.u.uTarget,density.read.attach(0));gl.uniform3f(splatP.u.color,c.r,c.g,c.b);blit(density.write.fbo);density.swap()}
 function multi(n){for(var i=0;i<n;i++){var c=genColor();c.r*=10;c.g*=10;c.b*=10;splat(canvas.width*Math.random(),canvas.height*Math.random(),1000*(Math.random()-.5),1000*(Math.random()-.5),c)}}
 function step(dt){gl.disable(gl.BLEND);gl.viewport(0,0,sw,sh2);var ts=[1/sw,1/sh2];
  curlP.bind();gl.uniform2f(curlP.u.texelSize,ts[0],ts[1]);gl.uniform1i(curlP.u.uVelocity,velocity.read.attach(0));blit(curl.fbo);
  vortP.bind();gl.uniform2f(vortP.u.texelSize,ts[0],ts[1]);gl.uniform1i(vortP.u.uVelocity,velocity.read.attach(0));gl.uniform1i(vortP.u.uCurl,curl.attach(1));gl.uniform1f(vortP.u.curl,config.CURL);gl.uniform1f(vortP.u.dt,dt);blit(velocity.write.fbo);velocity.swap();
  divP.bind();gl.uniform2f(divP.u.texelSize,ts[0],ts[1]);gl.uniform1i(divP.u.uVelocity,velocity.read.attach(0));blit(divergence.fbo);
  clearP.bind();gl.uniform1i(clearP.u.uTexture,pressure.read.attach(0));gl.uniform1f(clearP.u.value,config.PRESSURE_DISSIPATION);blit(pressure.write.fbo);pressure.swap();
  presP.bind();gl.uniform2f(presP.u.texelSize,ts[0],ts[1]);gl.uniform1i(presP.u.uDivergence,divergence.attach(0));
  for(var i=0;i<config.PRESSURE_ITERATIONS;i++){gl.uniform1i(presP.u.uPressure,pressure.read.attach(1));blit(pressure.write.fbo);pressure.swap()}
  gradP.bind();gl.uniform2f(gradP.u.texelSize,ts[0],ts[1]);gl.uniform1i(gradP.u.uPressure,pressure.read.attach(0));gl.uniform1i(gradP.u.uVelocity,velocity.read.attach(1));blit(velocity.write.fbo);velocity.swap();
  advP.bind();gl.uniform2f(advP.u.texelSize,ts[0],ts[1]);var vid=velocity.read.attach(0);gl.uniform1i(advP.u.uVelocity,vid);gl.uniform1i(advP.u.uSource,vid);gl.uniform1f(advP.u.dt,dt);gl.uniform1f(advP.u.dissipation,config.VELOCITY_DISSIPATION);blit(velocity.write.fbo);velocity.swap();
  gl.viewport(0,0,dw,dh);gl.uniform1i(advP.u.uVelocity,velocity.read.attach(0));gl.uniform1i(advP.u.uSource,density.read.attach(1));gl.uniform1f(advP.u.dissipation,config.DENSITY_DISSIPATION);blit(density.write.fbo);density.swap()}
 function render(){gl.blendFunc(gl.ONE,gl.ONE_MINUS_SRC_ALPHA);gl.enable(gl.BLEND);var w=gl.drawingBufferWidth,h=gl.drawingBufferHeight;gl.viewport(0,0,w,h);
  colorP.bind();gl.uniform4f(colorP.u.color,config.BACK[0],config.BACK[1],config.BACK[2],1);blit(null);
  var p=config.SHADING?shadeP:displayP;p.bind();if(config.SHADING)gl.uniform2f(p.u.texelSize,1/w,1/h);gl.uniform1i(p.u.uTexture,density.read.attach(0));blit(null)}
 initFB();multi(34);for(var i=0;i<8;i++)splatStack.push(10+parseInt(Math.random()*10));
 var lastCol=Date.now(),seeded=false,ang=0,pvx=0,pvy=0,vcol=null,lastV=0,t0=Date.now(),destroyed=false,raf=0;
 function virtual(){if(Date.now()-t0<700)return;var cx=canvas.width/2,cy=canvas.height/2,base=Math.min(300,canvas.width*.35,canvas.height*.35),r=base*(.72+.28*Math.sin(ang*.37));ang+=.026;var x=cx+Math.cos(ang)*r,y=cy+Math.sin(ang)*r;
  if(!seeded){seeded=true;pvx=x;pvy=y;return}
  if(!vcol||Date.now()-lastV>120){vcol=genColor();vcol.r*=3.2;vcol.g*=3.2;vcol.b*=3.2;lastV=Date.now()}
  var dx=(x-pvx)*9,dy=(y-pvy)*9;pvx=x;pvy=y;splat(x,y,dx,dy,vcol)}
 function input(){if(splatStack.length)multi(splatStack.pop());for(var i=0;i<pointers.length;i++){var p=pointers[i];if(p.moved){splat(p.x,p.y,p.dx,p.dy,p.color);p.moved=false}}
  if(lastCol+100<Date.now()){lastCol=Date.now();for(var j=0;j<pointers.length;j++)pointers[j].color=genColor()}}
 function update(){if(destroyed)return;if(canvas.width!=canvas.clientWidth||canvas.height!=canvas.clientHeight){canvas.width=canvas.clientWidth;canvas.height=canvas.clientHeight;initFB()}virtual();input();step(.016);render();raf=requestAnimationFrame(update)}
 update();
 function pos(cx,cy){var r=canvas.getBoundingClientRect();return{x:cx-r.left,y:cy-r.top}}
 var offs=[];function on(t,ty,h,o){t.addEventListener(ty,h,o);offs.push(function(){t.removeEventListener(ty,h,o)})}
 on(window,"mousemove",function(e){var q=pos(e.clientX,e.clientY),p=pointers[0];if(!p.ever){p.ever=true;p.x=q.x;p.y=q.y;return}p.moved=true;p.dx=(q.x-p.x)*5;p.dy=(q.y-p.y)*5;p.x=q.x;p.y=q.y;p.color=genColor()});
 on(window,"touchmove",function(e){var ts=e.targetTouches;for(var i=0;i<ts.length;i++){if(i>=pointers.length)pointers.push(new PointerP());var p=pointers[i],q=pos(ts[i].clientX,ts[i].clientY);p.moved=p.ever===true;p.ever=true;p.dx=(q.x-p.x)*8;p.dy=(q.y-p.y)*8;p.x=q.x;p.y=q.y}},{passive:true});
 on(window,"touchstart",function(e){var ts=e.targetTouches;for(var i=0;i<ts.length;i++){if(i>=pointers.length)pointers.push(new PointerP());var p=pointers[i],q=pos(ts[i].clientX,ts[i].clientY);p.x=q.x;p.y=q.y;p.color=genColor()}},{passive:true});
 return function(){destroyed=true;cancelAnimationFrame(raf);offs.forEach(function(f){f()})}
}

(function(){var c=$("fluid");if(!c)return;if(window.matchMedia("(prefers-reduced-motion: reduce)").matches){c.style.display="none";return}try{fluidSimulation(c)}catch(e){c.style.display="none"}})();
</script>


</body></html>

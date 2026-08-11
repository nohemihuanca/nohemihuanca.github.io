---
permalink: /
title:
excerpt:
layout: null
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<meta charset="utf-8">
<style>
  :root{--paper:#EEEDE5;--paper-2:#e4e3d9;--panel:#f8f6ef;--ink:#29312C;--ink-soft:#48534c;--muted:#6f766d;--amber:#B99A5B;--amber-deep:#94733a;--sage:#5f715f;--header:#15201B;--line:rgba(41,49,44,.14);--line-2:rgba(41,49,44,.08);--fig-bg:#fff;--spectral:linear-gradient(90deg,#5b4bd6,#3aa0d6,#4cc38a,#e3d24c,#e07a3c,#d64b6a);--serif:"Iowan Old Style","Palatino Linotype",Palatino,Georgia,"Times New Roman",serif;--sans:ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;--mono:ui-monospace,"SF Mono",Menlo,Consolas,monospace}
  @media (prefers-color-scheme:dark){:root{--paper:#17130f;--paper-2:#1f1a14;--panel:#211b15;--ink:#efe7da;--ink-soft:#c3b6a3;--muted:#9d8f7c;--amber:#d68f45;--amber-deep:#c9812f;--sage:#8ca07e;--line:rgba(239,231,218,.14);--line-2:rgba(239,231,218,.07);--fig-bg:#f3f0ea}}
  *{box-sizing:border-box} html,body{margin:0;padding:0}
  body{background:var(--paper);color:var(--ink);font-family:var(--sans);line-height:1.62;-webkit-font-smoothing:antialiased}
  .wrap{max-width:1180px;margin:0 auto;padding:0 30px}
  nav.top{position:sticky;top:0;z-index:10;background:color-mix(in srgb,var(--header) 92%,transparent);backdrop-filter:blur(8px);border-bottom:1px solid rgba(238,237,229,.12)}
  nav.top .r{display:flex;align-items:center;justify-content:space-between;max-width:1180px;margin:0 auto;padding:13px 30px}
  .brand{display:flex;align-items:center;gap:10px;font-family:var(--serif);font-size:1.05rem;color:#f4f1e9;text-decoration:none}
  .brand svg{width:21px;height:25px}
  .links{display:flex;gap:14px;align-items:center;font-family:var(--mono);font-size:11.5px;letter-spacing:.06em;text-transform:uppercase;white-space:nowrap}
  .links a{color:#d8d0bb;text-decoration:none} .links a:hover{color:#fff6dc}.links .arr{color:var(--amber)}
  header.hero{text-align:center;padding:56px 30px 28px;background:var(--header);color:#f4f1e9}
  .portrait{width:184px;height:184px;margin:0 auto 24px;border-radius:50%;padding:6px;background:linear-gradient(150deg,var(--amber),var(--sage));box-shadow:0 14px 40px rgba(42,35,27,.22)}
  .portrait img{width:100%;height:100%;object-fit:cover;object-position:50% 20%;border-radius:50%;display:block;border:3px solid var(--panel)}
  .eyebrow{font-family:var(--mono);font-size:13px;letter-spacing:.18em;text-transform:uppercase;color:var(--amber);margin:0 0 12px}
  header.hero h1{font-family:var(--serif);font-weight:500;font-size:clamp(2.5rem,7vw,4rem);line-height:1.05;margin:0;letter-spacing:0;text-wrap:balance}
  .role{margin:16px auto 0;max-width:42ch;color:#d8d0bb;font-size:1.06rem}.role b{color:#fffaf0;font-weight:600}
  .band{display:grid;grid-template-columns:1fr 1fr;height:330px;margin:0;overflow:hidden;border-top:1px solid rgba(238,237,229,.12);border-bottom:1px solid var(--line);background:#111}
  .band figure{position:relative;min-width:0;margin:0}
  .band figure + figure{border-left:none}
  .band figure::before{content:"";position:absolute;left:0;right:0;bottom:0;height:86px;z-index:1;background:linear-gradient(180deg,rgba(17,17,17,0),rgba(17,17,17,.5));pointer-events:none}
  .band img{width:100%;height:100%;object-fit:cover;display:block}
  .band .bci img{object-position:50% 48%}
  .band .cocha img{object-position:50% 50%}
  .band .bci::after{content:"";position:absolute;top:0;right:-36px;bottom:0;width:72px;z-index:1;background:linear-gradient(90deg,rgba(17,17,17,0),rgba(17,17,17,.24),rgba(17,17,17,0));pointer-events:none}
  .site-label{position:absolute;left:18px;bottom:16px;z-index:10;width:max-content;max-width:calc(100% - 36px);padding:7px 10px;border-radius:4px;background:rgba(23,19,15,.84);backdrop-filter:blur(4px);font-family:var(--mono);font-size:11px;letter-spacing:.06em;text-transform:uppercase;color:#fffaf0;line-height:1.35;text-shadow:0 1px 5px rgba(0,0,0,.75);box-shadow:0 6px 18px rgba(0,0,0,.18);pointer-events:none}
  section{padding:46px 0;border-bottom:1px solid var(--line-2)}
  .sec-label{font-family:var(--mono);font-size:13.5px;letter-spacing:.22em;text-transform:uppercase;color:var(--amber);margin:0 0 8px;line-height:1.35}
  .major-label{font-size:14.5px}
  .contact-label{font-size:14.5px}
  h2{font-family:var(--serif);font-weight:500;font-size:clamp(1.6rem,4vw,2.15rem);margin:0 0 16px;letter-spacing:0}
  p{color:var(--ink-soft);font-size:17px} p.lead{font-size:1.22rem;color:var(--ink)}
  a.inline{color:var(--amber-deep);text-decoration:none;border-bottom:1px solid var(--amber)}
  .row{display:grid;grid-template-columns:1fr minmax(300px,43%);gap:34px;align-items:start;padding:36px 0;border-top:1px solid var(--line-2)}
  .row:first-of-type{border-top:none}
  .row.rev{grid-template-columns:minmax(300px,43%) 1fr} .row.rev .txt{order:2}
  .tag{font-family:var(--mono);font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:var(--sage)}
  .row h3{font-family:var(--serif);font-weight:500;font-size:1.36rem;margin:6px 0 10px;letter-spacing:0;line-height:1.22}
  .row .txt p{font-size:1.02rem;margin:0 0 12px}
  .figs{display:flex;flex-direction:column;gap:14px;position:sticky;top:70px}
  figure{margin:0} figure img{width:100%;display:block;border-radius:12px;border:1px solid var(--line)}
  figure.photo img{height:200px;object-fit:cover}
  figure.chart img{background:var(--fig-bg);object-fit:contain;max-height:330px;padding:4px}
  figcaption{font-family:var(--mono);font-size:10px;letter-spacing:.04em;color:var(--muted);margin-top:7px;text-transform:uppercase;line-height:1.5}
  .sb{height:3px;border-radius:3px;background:var(--spectral);margin:4px 0 0;opacity:.9;width:150px}
  .pubs{list-style:none;padding:0;margin:0} .pubs li{padding:15px 0;border-bottom:1px solid var(--line-2)}
  .pubs .venue{font-family:var(--mono);font-size:10.5px;letter-spacing:.06em;text-transform:uppercase;color:var(--sage)}
  .pubs .ptitle{color:var(--ink);font-size:1.08rem;margin:3px 0 2px;font-weight:600} .pubs .auth{color:var(--muted);font-size:.94rem}
  .btn{display:inline-flex;align-items:center;gap:8px;margin-top:24px;font-family:var(--mono);font-size:11.5px;letter-spacing:.12em;text-transform:uppercase;color:var(--paper);background:var(--amber-deep);padding:12px 20px;border-radius:999px;text-decoration:none;font-weight:600} .btn:hover{background:var(--amber)}
  .seedlearn{display:grid;grid-template-columns:1fr 1fr;gap:26px;align-items:center}
  .seedlearn img{width:100%;border-radius:14px;border:1px solid var(--line);display:block}
  .seedlearn .image-caption{font-family:var(--mono);font-size:10px;letter-spacing:.04em;color:var(--muted);margin-top:7px;text-transform:uppercase;line-height:1.5}
  .contact{display:flex;flex-wrap:wrap;gap:12px 24px;font-family:var(--mono);font-size:14px;margin-top:4px} .contact a{color:var(--muted);text-decoration:none} .contact a:hover{color:var(--amber-deep)}
  footer{padding:34px 0 56px;text-align:center;font-family:var(--mono);font-size:11px;letter-spacing:.16em;text-transform:uppercase;color:var(--muted)}
  @media (max-width:680px){.links{display:none}.band{grid-template-columns:1fr;height:auto}.band figure{height:230px}.band figure + figure{border-left:none;border-top:none}.band .bci::after{top:auto;right:0;left:0;bottom:-28px;width:auto;height:56px;background:linear-gradient(180deg,rgba(17,17,17,0),rgba(17,17,17,.28),rgba(17,17,17,0))}.site-label{font-size:10px;left:12px;bottom:12px;max-width:calc(100% - 24px)}.sec-label{letter-spacing:.16em}.row,.row.rev,.seedlearn{grid-template-columns:1fr}.row.rev .txt{order:0}.figs{position:static}}
</style>
<nav class="top"><div class="r">
  <a class="brand" href="#top"><svg viewBox="0 0 22 26" fill="none" aria-hidden="true"><line x1="3" y1="16" x2="19" y2="16" stroke="var(--line)" stroke-width="1"/><path d="M11 16 L11 7" stroke="var(--amber)" stroke-width="1.8" stroke-linecap="round"/><path d="M11 9 C5 8 2 4 2 1 C7 1.5 10 4.5 11 9 Z" fill="var(--sage)"/><path d="M11 9 C17 8 20 4 20 1 C15 1.5 12 4.5 11 9 Z" fill="var(--amber)"/><path d="M11 16 C10 20 7 22 5 25" stroke="var(--amber-deep)" stroke-width="1.3" stroke-linecap="round"/><path d="M11 16 C12 20 15 22 17 24.5" stroke="var(--amber-deep)" stroke-width="1.3" stroke-linecap="round"/></svg>Nohemi Huanca-Nunez, Ph.D.</a>
  <div class="links"><a href="#about">About</a><a href="#research">Research</a><a href="https://scholar.google.com/citations?user=cp5OMEIAAAAJ&hl=en&oi=ao" target="_blank" rel="noopener">Publications <span class="arr">&#8599;</span></a><a href="https://nohemihuanca.github.io/selected-features/">Selected Features</a><a href="https://nohemihuanca.github.io/seedlearn/">SeedLearn</a><a href="#contact">Contact</a></div>
</div></nav>
<a id="top"></a>
<header class="hero">
  <div class="portrait"><img src="images/site/portrait.jpg" alt="Nohemi Huanca-Nunez"></div>
  <p class="eyebrow">Forest Regeneration &amp; Plant Community Ecologist</p>
  <h1>Nohemi Huanca-Nunez</h1>
  <p class="role"><b>Associate Research Scientist, Yale University.</b> Understanding how processes operating from seedlings to landscapes shape tropical forest regeneration, biodiversity, and resilience.</p>
</header>
<div class="band" aria-label="Lowland tropical forest field sites">
  <figure class="bci"><img src="images/site/band.jpg" alt="Lowland tropical forest at Barro Colorado Island, Panama"><span class="site-label">BCI, Panama</span></figure>
  <figure class="cocha"><img src="images/habitat.jpg" alt="Lowland tropical forest at Cocha Cashu, Peru"><span class="site-label">Cocha Cashu, Peru</span></figure>
</div>
<main class="wrap">
  <section id="about">
    <p class="sec-label major-label">About</p>
    <p class="lead">My research asks how tropical forests regenerate, maintain their extraordinary biodiversity, and recover under environmental change.</p>
    <p>Across forests in Costa Rica, Panama, and Peru, I focus on the early life stages of trees, when dispersal, disturbance, density-dependent interactions, and neighboring vegetation determine which species arrive, establish, survive, and ultimately shape the future forest.</p>
    <p>A central part of my work examines the functional and demographic strategies underlying these processes. I study how above- and belowground traits are coordinated, how plant strategies develop across ontogeny, and how traits and species performance vary along successional and drought gradients. By combining whole-plant traits with long-term demographic data and field experiments, I seek to understand the mechanisms shaping seedling growth and survival, species coexistence, and forest resilience.</p>
    <p>Through collaborative projects, I am also extending this work from individuals and plots to broader landscapes. I use hyperspectral sensing, spatial remote sensing, and biologically informed AI to characterize ecological responses to environmental change, improve seedling identification, and examine how seed sources and landscape connectivity influence natural regeneration. Together, this work aims to build a predictive understanding of tropical forest recovery and identify where natural regeneration can succeed and where active restoration may be needed.</p>
  </section>
  <section id="research">
    <p class="sec-label major-label">Research — three integrated themes</p>
    <div class="row">
      <div class="txt">
        <span class="tag">Regeneration &amp; Coexistence</span>
        <h3>Seed dispersal and species interactions during forest regeneration</h3>
        <p>Why do regenerating tropical forests follow different recovery trajectories? Forest recovery depends on which species arrive and which successfully establish and persist. I investigate how seed dispersal, disturbance, density-dependent interactions, neighboring vegetation, and large mammals shape seedling communities and forest succession.</p>
        <p>My research developed the concept of seed rain–successional feedbacks, showing that regenerating forests increasingly reflect their own seed rain over time. These feedbacks can reinforce successional trajectories and contribute to divergence in species composition among forests (Huanca-Nunez et al. 2021, <em>Ecology</em>). More recent work showed that limited seed arrival can delay the compositional recovery of secondary forests even where environmental conditions permit seedling establishment, highlighting the importance of seed sources and landscape connectivity (Genes, Huanca-Nunez et al. 2026, <em>PNAS</em>). Across Amazonian floodplain forests, our research further demonstrated how disturbance and dispersal filters interact to create variation in recruitment and diversity (Terborgh, Huanca-Nunez et al. 2017, 2020, <em>Ecology</em>).</p>
        <p>I complement these studies with long-term demographic observations and field experiments examining how density dependence and natural enemies (e.g., using mammal exclusion) influence seedling recruitment, growth, and survival. Together, this work seeks to explain why some forests recover rapidly while others remain constrained by dispersal, environmental conditions, or biotic interactions.</p>
      </div>
      <div class="figs">
        <figure class="chart"><img src="images/site/fig-seedrain-2021.png" alt="Conceptual model of seed rain–successional feedbacks · Huanca-Nunez et al. 2021, Ecology"><figcaption>Conceptual model of seed rain–successional feedbacks · Huanca-Nunez et al. 2021, Ecology</figcaption></figure>
        <figure class="chart"><img src="images/site/cocha-cashu-treefall-zones.jpg" alt="Map of disturbance zones from treefalls in the Cocha Cashu forest plot"><figcaption>Treefall disturbance zones in the Cocha Cashu forest plot, Peru — Terborgh, Huanca-Nunez et al. 2020, <em>Ecology</em></figcaption></figure>
      </div>
    </div>
    <div class="row">
      <div class="txt">
        <span class="tag">Function &amp; Demography</span>
        <h3>Plant strategies across life stages and forest succession</h3>
        <p>Why do tree species differ in their growth, survival, recruitment, and responses to environmental change? I investigate the functional and demographic strategies underlying these differences by combining traits across leaves, stems, and roots with measurements of biomass allocation and long-term demographic performance.</p>
        <p>In tropical secondary forests, I showed that biomass allocation among leaves, stems, and roots can predict seedling performance better than many commonly measured organ-level traits, emphasizing the importance of whole-plant strategies during early establishment (Huanca-Nunez et al. 2024, <em>Plants</em>). Building on this work, I integrated trait data from first-year seedlings, established seedlings, saplings, and adults and found that, despite substantial changes in trait values during development, species broadly maintained their relative functional differences across life stages. At the established-seedling stage, coordination among leaf, stem, and root traits was strongest for structural investment traits, indicating that key dimensions of whole-plant strategy are established early during forest regeneration (Huanca-Nunez et al., <em>Functional Ecology, in review</em>).</p>
        <p>I also examine how these strategies influence species interactions. Using 18 years of seedling data from Barro Colorado Island, Panama, I found that differences among species in conspecific negative density dependence (CNDD) align more strongly with integrated demographic strategies than with isolated functional traits: fast-growing and tall, long-lived pioneer species experience stronger CNDD than slow-growing and short-lived species (Huanca-Nunez et al. 2026, <em>Journal of Ecology</em>). My current work examines whether belowground traits and coordinated root–shoot strategies explain why species differ in their responses to conspecific negative density dependence. I am also extending this trait-based framework across successional and drought gradients. Together, this research connects variation in plant form and function with species coexistence, community change, and forest resilience.</p>
      </div>
      <div class="figs">
        <figure class="chart"><img src="images/site/fig-wooddensity.png" alt="Wood density is correlated between seedlings and adults"><figcaption>Seedling–adult wood density relationships — error-aware trait model, Huanca-Nunez et al., <em>Functional Ecology</em>, in review</figcaption></figure>
        <figure class="chart"><img src="images/site/piper-grande-root-horizontal.jpg" alt="Root scan of Piper grande"><figcaption>Root scan of <em>Piper grande</em> — belowground functional traits</figcaption></figure>
      </div>
    </div>
    <div class="row rev">
      <div class="txt">
        <span class="tag">AI &amp; Restoration</span>
        <h3>Remote sensing and AI for forest monitoring and restoration</h3>
        <p>How can we measure biodiversity and forest recovery across more species and larger spatial scales? The extraordinary diversity of tropical forests limits our ability to identify seedlings, measure functional strategies, and monitor regeneration using field surveys alone. I therefore increasingly integrate hyperspectral sensing, spatial remote sensing, computer vision, and artificial intelligence into my ecological research to expand biodiversity monitoring across species and spatial scales.</p>
        <p>Across a tropical rainfall gradient in Panama, I integrate leaf hyperspectral reflectance with functional traits and demographic information to characterize drought-associated variation within and among tree species. This research examines whether spectral information can reveal functional and environmental responses that are difficult to capture using commonly measured traits alone.</p>
        <p>Through <a class="inline" href="https://nohemihuanca.github.io/seedlearn/">SeedLearn</a>, I lead an interdisciplinary collaboration among ecologists, botanists, and computer scientists to improve automated tropical-seedling identification. We combine <a class="inline" href="https://www.inaturalist.org/projects/yale-stri-ai-seedling-project" target="_blank" rel="noopener">seedling images</a> with morphological traits, taxonomic knowledge, and ecological reasoning to develop biologically informed AI tools for hyperdiverse forests. I am also helping lead the remote-sensing and spatial-analysis component of a restoration project in Panama that links remnant trees and surrounding forest cover with field censuses of naturally recruiting species. Together, these projects are building a predictive framework that links seedling traits and demography with landscape structure to identify where natural regeneration can succeed and where active restoration may be needed.</p>
        <div class="sb"></div>
      </div>
      <div class="figs">
        <figure class="chart"><img src="images/site/ai-leaf-depth-composite.png" alt="Leaf detection and AI-predicted depth map of a tropical seedling"><figcaption>Leaf detection and AI-predicted depth map for a tropical seedling</figcaption></figure>
        <figure class="photo"><img src="images/site/miconia-simplex-seedling.jpg" alt="Seedling of Miconia simplex"><figcaption>SeedLearn field image — <em>Miconia simplex</em></figcaption></figure>
        <figure class="photo"><img src="images/site/cojoba-rufescens-seedling.jpg" alt="Seedling of Cojoba rufescens"><figcaption>SeedLearn field image — <em>Cojoba rufescens</em></figcaption></figure>
      </div>
    </div>
  </section>
  <section id="pubs">
    <p class="sec-label">Selected publications</p>
    <ul class="pubs">
      <li><div class="venue">Journal of Ecology · 2026</div><div class="ptitle">Conspecific negative density-dependent mortality varies with tropical tree species life history, wood density and abundance</div><div class="auth">Huanca-Nunez, N., Browne, L., Hülsmann, L., Dent, D.H., Rüger, N., Comita, L.S.</div></li>
      <li><div class="venue">Plants · 2024 · Cover article</div><div class="ptitle">Trait-mediated variation in seedling performance in Costa Rican successional forests</div><div class="auth">Huanca-Nunez, N., Chazdon, R.L., Russo, S.E.</div></li>
      <li><div class="venue">Journal of Applied Ecology · 2023</div><div class="ptitle">Effects of large mammals on seedling communities depend on successional stage and species&#39; strategies</div><div class="auth">Huanca-Nunez, N., Chazdon, R., Russo, S.E.</div></li>
      <li><div class="venue">Ecology · 2021</div><div class="ptitle">Seed rain–successional feedbacks in regenerating tropical forests</div><div class="auth">Huanca-Nunez, N., Chazdon, R., Russo, S.E.</div></li>
    </ul>
    <a class="btn" href="https://scholar.google.com/citations?user=cp5OMEIAAAAJ&hl=en&oi=ao" target="_blank" rel="noopener">Full list on Google Scholar &#8599;</a>
  </section>
  <section id="seedlearn">
    <p class="sec-label">Featured project</p>
    <div class="seedlearn"><figure><img src="images/site/guatteria-amplifolia-seedling.jpg" alt="Seedling of Guatteria amplifolia"><figcaption class="image-caption">SeedLearn field image — <em>Guatteria amplifolia</em></figcaption></figure>
      <div><h2>SeedLearn</h2><p>Identifying tropical seedlings and measuring their traits at scale is a major bottleneck in forest ecology. SeedLearn pairs ecological knowledge with machine learning to automate seedling identification and trait inference — building scalable tools for restoration and conservation.</p><a class="inline" href="https://nohemihuanca.github.io/seedlearn/">Explore the project →</a></div>
    </div>
  </section>
  <section id="contact" style="border-bottom:none">
    <p class="sec-label contact-label">Contact</p><h2>Let&#39;s talk about forests.</h2>
    <p>Yale School of the Environment · New Haven, CT</p>
    <div class="contact"><a href="mailto:nohemi.huanca@yale.edu">Email</a><a href="https://scholar.google.com/citations?user=cp5OMEIAAAAJ&hl=en&oi=ao" target="_blank" rel="noopener">Google Scholar</a><a href="https://orcid.org/0000-0002-4603-827X" target="_blank" rel="noopener">ORCID</a><a href="https://github.com/nohemihuanca" target="_blank" rel="noopener">GitHub</a></div>
  </section>
</main>
<footer>© Nohemi Huanca-Nunez · nohemihuanca.github.io</footer>


<style>
@import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700&family=Fira+Code:wght@400;500&display=swap');
*{box-sizing:border-box;margin:0;padding:0}
.gh{background:#0d1117;border-radius:12px;padding:32px 36px;font-family:'JetBrains Mono',monospace;color:#c9d1d9;line-height:1.6}
.term-bar{display:flex;align-items:center;gap:8px;margin-bottom:24px}
.dot{width:12px;height:12px;border-radius:50%}
.d-r{background:#ff5f56}.d-y{background:#ffbd2e}.d-g{background:#27c93f}
.term-title{font-size:11px;color:#6e7681;margin-left:auto;font-family:'JetBrains Mono',monospace}
.prompt{color:#58a6ff;font-size:13px}
.cmd{color:#e6edf3;font-size:13px}
.green{color:#3fb950}
.cyan{color:#79c0ff}
.yellow{color:#e3b341}
.gray{color:#6e7681;font-size:12px}
.muted{color:#484f58;font-size:12px}
.block{margin-bottom:20px}
.name-line{font-size:22px;font-weight:700;color:#e6edf3;letter-spacing:-0.5px;margin:8px 0 4px}
.sub-line{color:#58a6ff;font-size:13px;margin-bottom:16px}
.divider{border:none;border-top:1px solid #21262d;margin:20px 0}
.section-label{color:#3fb950;font-size:11px;font-weight:500;text-transform:uppercase;letter-spacing:.1em;margin-bottom:10px}
.badge-row{display:flex;flex-wrap:wrap;gap:6px;margin-bottom:6px}
.badge{display:inline-flex;align-items:center;gap:5px;background:#161b22;border:1px solid #30363d;border-radius:6px;padding:4px 10px;font-size:11px;font-family:'JetBrains Mono',monospace}
.badge-py{color:#3572A5;border-color:#3572A5}.badge-js{color:#f1e05a;border-color:#f1e05a}
.badge-ts{color:#2b7489;border-color:#2b7489}.badge-node{color:#68a063;border-color:#68a063}
.badge-react{color:#61dafb;border-color:#61dafb}.badge-next{color:#e6edf3;border-color:#484f58}
.badge-sql{color:#e38c00;border-color:#e38c00}.badge-mongo{color:#47A248;border-color:#47A248}
.badge-pbi{color:#F2C811;border-color:#F2C811}.badge-aws{color:#FF9900;border-color:#FF9900}
.badge-docker{color:#2496ED;border-color:#2496ED}.badge-git{color:#F05032;border-color:#F05032}
.badge-uipath{color:#fa4616;border-color:#fa4616}.badge-gcp{color:#4285F4;border-color:#4285F4}
.badge-sk{color:#FF6B35;border-color:#FF6B35}.badge-tab{color:#E97627;border-color:#E97627}
.stats-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-top:8px}
.stat-card{background:#161b22;border:1px solid #30363d;border-radius:8px;padding:12px 14px}
.stat-num{font-size:20px;font-weight:700;color:#e6edf3}
.stat-lbl{font-size:10px;color:#6e7681;margin-top:2px;font-family:'JetBrains Mono',monospace}
.proj-card{background:#161b22;border:1px solid #30363d;border-radius:8px;padding:14px 16px;margin-bottom:8px}
.proj-title{color:#58a6ff;font-size:13px;font-weight:500;margin-bottom:4px}
.proj-desc{color:#8b949e;font-size:11px;line-height:1.5;margin-bottom:8px}
.proj-tags{display:flex;gap:5px;flex-wrap:wrap}
.ptag{font-size:10px;background:#0d1117;border:1px solid #21262d;border-radius:4px;padding:2px 7px;color:#8b949e}
.contrib-bar{background:#161b22;border:1px solid #30363d;border-radius:8px;padding:14px;margin-top:8px}
.contrib-grid{display:grid;grid-template-columns:repeat(52,1fr);gap:2px;margin-top:8px}
.contrib-day{aspect-ratio:1;border-radius:2px}
.c0{background:#161b22}.c1{background:#0e4429}.c2{background:#006d32}.c3{background:#26a641}.c4{background:#39d353}
.contrib-legend{display:flex;align-items:center;gap:4px;margin-top:6px;justify-content:flex-end}
.cl-box{width:10px;height:10px;border-radius:2px}
.typing-cursor{display:inline-block;width:8px;height:13px;background:#58a6ff;animation:blink 1s step-end infinite;vertical-align:middle}
@keyframes blink{0%,100%{opacity:1}50%{opacity:0}}
.footer-line{color:#484f58;font-size:11px;margin-top:20px;text-align:center}
.contact-row{display:flex;gap:16px;flex-wrap:wrap;margin-top:6px}
.contact-item{display:flex;align-items:center;gap:5px;font-size:11px;color:#8b949e}
</style>

<div class="gh">
  <div class="term-bar">
    <div class="dot d-r"></div><div class="dot d-y"></div><div class="dot d-g"></div>
    <span class="term-title">NoClipDvlp — README.md</span>
  </div>

  <div class="block">
    <div class="gray">$ whoami</div>
    <div class="name-line">Jefferson Rodriguez</div>
    <div class="sub-line">Data Scientist · Full-Stack Developer · Automatización & RPA</div>
    <div class="gray" style="font-size:12px;line-height:1.7">
      Construyo soluciones donde los datos y el código se encuentran.<br>
      Desde pipelines de ML hasta aplicaciones web premium, end-to-end.<br>
      <span class="muted">Bogotá, Colombia · Disponible para proyectos remotos</span>
    </div>
  </div>

  <hr class="divider">

  <div class="block">
    <div class="gray" style="margin-bottom:6px">$ cat skills.json</div>
    <div class="section-label">Data Science & Analytics</div>
    <div class="badge-row">
      <span class="badge badge-py">Python</span>
      <span class="badge badge-sk">Scikit-learn</span>
      <span class="badge badge-pbi">Power BI</span>
      <span class="badge badge-tab">Tableau</span>
      <span class="badge badge-sql">SQL</span>
      <span class="badge badge-mongo">MongoDB</span>
    </div>
    <div class="section-label" style="margin-top:10px">Full-Stack & Back-End</div>
    <div class="badge-row">
      <span class="badge badge-next">Next.js</span>
      <span class="badge badge-react">React</span>
      <span class="badge badge-node">Node.js</span>
      <span class="badge badge-ts">TypeScript</span>
      <span class="badge badge-js">JavaScript</span>
      <span class="badge badge-docker">Docker</span>
    </div>
    <div class="section-label" style="margin-top:10px">Cloud & Automatización</div>
    <div class="badge-row">
      <span class="badge badge-aws">AWS</span>
      <span class="badge badge-gcp">Google Cloud</span>
      <span class="badge badge-uipath">UiPath</span>
      <span class="badge badge-git">Git</span>
    </div>
  </div>

  <hr class="divider">

  <div class="block">
    <div class="gray" style="margin-bottom:8px">$ ls ./projects --highlight</div>
    <div class="proj-card">
      <div class="proj-title">real-estate-platform — Avest Capital GmbH</div>
      <div class="proj-desc">Plataforma inmobiliaria premium con showroom 3D interactivo y CRM integrado. Incrementó conversión de ventas un 30% en 3 meses.</div>
      <div class="proj-tags"><span class="ptag">Next.js</span><span class="ptag">TypeScript</span><span class="ptag">Python</span><span class="ptag">MongoDB</span><span class="ptag">Node.js</span></div>
    </div>
    <div class="proj-card">
      <div class="proj-title">ml-pipeline-mercadolibre</div>
      <div class="proj-desc">Pipelines de datos para +5M registros/mes. Modelos de segmentación y detección de churn con 82% accuracy. Detección de anomalías financieras.</div>
      <div class="proj-tags"><span class="ptag">Python</span><span class="ptag">Scikit-learn</span><span class="ptag">SQL</span><span class="ptag">Pandas</span><span class="ptag">MySQL</span></div>
    </div>
    <div class="proj-card">
      <div class="proj-title">audit-bot-bytecraft</div>
      <div class="proj-desc">Bot Python para auditoría automática de clases en tiempo real. Generación de reportes de calidad automatizando el 85% del trabajo manual.</div>
      <div class="proj-tags"><span class="ptag">Python</span><span class="ptag">RPA</span><span class="ptag">Google Cloud</span><span class="ptag">Zoho API</span></div>
    </div>
  </div>

  <hr class="divider">

  <div class="block">
    <div class="gray" style="margin-bottom:8px">$ git log --stat --author="NoClipDvlp"</div>
    <div class="stats-grid">
      <div class="stat-card"><div class="stat-num green">82<span style="font-size:14px">%</span></div><div class="stat-lbl">ML model accuracy</div></div>
      <div class="stat-card"><div class="stat-num cyan">+5M</div><div class="stat-lbl">records/month processed</div></div>
      <div class="stat-card"><div class="stat-num yellow">80<span style="font-size:14px">%</span></div><div class="stat-lbl">tasks automated w/ RPA</div></div>
      <div class="stat-card"><div class="stat-num" style="color:#3fb950">15+</div><div class="stat-lbl">corporate clients served</div></div>
    </div>
    <div class="contrib-bar">
      <div class="gray" style="font-size:11px">contributions this year</div>
      <div class="contrib-grid" id="cgrid"></div>
      <div class="contrib-legend">
        <span style="font-size:10px;color:#6e7681">less</span>
        <div class="cl-box c0" style="border:1px solid #30363d"></div>
        <div class="cl-box c1"></div><div class="cl-box c2"></div>
        <div class="cl-box c3"></div><div class="cl-box c4"></div>
        <span style="font-size:10px;color:#6e7681">more</span>
      </div>
    </div>
  </div>

  <hr class="divider">

  <div class="block">
    <div class="gray" style="margin-bottom:6px">$ echo $CONTACT</div>
    <div class="contact-row">
      <span class="contact-item"><span style="color:#58a6ff">@</span> davidromoda1@gmail.com</span>
      <span class="contact-item"><span style="color:#3fb950">in</span> /in/jefferson-rodriguez</span>
      <span class="contact-item"><span style="color:#e3b341">gh</span> github.com/NoClipDvlp</span>
    </div>
  </div>

  <div class="footer-line">
    <span class="prompt">~</span> <span class="cmd">open to remote · freelance · full-time opportunities</span> <span class="typing-cursor"></span>
  </div>
</div>

<script>
const grid = document.getElementById('cgrid');
const levels = [0,0,0,1,0,0,1,2,0,1,3,2,1,0,0,2,3,4,2,1,0,0,1,2,3,2,4,3,1,0,1,2,3,4,3,2,1,2,3,4,4,3,2,1,2,3,2,1,0,1,2,3,4,3,2,1,0,2,3,4,3,2,1,2,3,4,3,2,1,2,3,2,1,0,1,2,3,2,1,0,0,1,2,3,4,3,2,1,2,3,4,3,2,1,2,3,4,3,2,1,2,3,2,1,0,0,1,2,3,4,3,2,1,2,3,4,3,2,1,0,0,1,2,3,2,1,0,0,1,2,3,2,1,0,0,1,2,3,4,3,2,1,0,0,1,2,3,2,1,0,0,0,1,2,3,2,1,0,0,0,0,1,2,3,2,1,0,0,0,0,1,2,3,2,1,0,0,0,0,1,2,1,0,0,0,0,1,2,1,0,0,0,0,0,1,1,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0];
for(let i=0;i<364;i++){
  const d=document.createElement('div');
  const lv=levels[i]||0;
  d.className='contrib-day c'+lv;
  grid.appendChild(d);
}
</script>

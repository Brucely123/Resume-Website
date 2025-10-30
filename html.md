# Resume-Website

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Brucely Charles | Electrical Engineer</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Electrical engineer (UCF) & Marine veteran specializing in PCB design, embedded systems, and renewable energy.">
  <link rel="icon" href="assets/favicon.ico">
  <link rel="stylesheet" href="style.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <div class="container">
      <h1>Brucely Charles</h1>
      <p class="tagline">Electrical Engineer • Marine Veteran • Renewable-Energy Enthusiast</p>
      <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#experience">Experience</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main>
    <section id="about" class="section">
      <div class="container">
        <h2>About Me</h2>
        <p>
          I’m a U.S. Marine veteran finishing my B.S.E.E. at the University of Central Florida.
          I’ve led teams in mission-critical maintenance, designed solar-powered IoT systems,
          and saved utilities over $1 M by optimizing transmission lines.
          My focus: <strong>PCB design, embedded firmware, and renewable-energy integration.</strong>
        </p>
        <a class="btn" href="assets/pdf/Worked_Resume.pdf" target="_blank">Download Résumé (PDF)</a>
      </div>
    </section>

    <section id="projects" class="section alt">
      <div class="container">
        <h2>Featured Projects</h2>

        <article class="project">
          <h3>Bio-Sense Smart Plant Pot</h3>
          <p>ESP32-powered, solar-charged planter with adaptive LED lighting, dual spectrometers,
             soil-moisture telemetry, and a React-based dashboard for remote monitoring.</p>
          <span class="tag">ESP32</span>
          <span class="tag">Solar MPPT</span>
          <span class="tag">React</span>
        </article>

        <article class="project">
          <h3>PCB Fabrication & Micro-Regulator Debug</h3>
          <p>Fabricated 4-layer boards with stencil-aligned reflow soldering; root-caused EMI issues
             on a switching buck regulator, cutting ripple by 38 %.</p>
          <span class="tag">Altium</span>
          <span class="tag">EasyEDA</span>
          <span class="tag">Oscilloscope</span>
        </article>

        <article class="project">
          <h3>Wind-Farm Transmission Optimizer</h3>
          <p>Used PowerWorld Simulator to re-route 138 kV lines, reducing losses by 0.42 MW
             and saving $1.18 M annually while improving voltage stability.</p>
          <span class="tag">PowerWorld</span>
          <span class="tag">Power-Flow</span>
          <span class="tag">Python</span>
        </article>
      </div>
    </section>

    <section id="experience" class="section">
      <div class="container">
        <h2>Experience</h2>

        <div class="job">
          <h3>Electrical Technician (Contractor)</h3>
          <p class="meta">St. Thomas, USVI &nbsp;|&nbsp; Apr 2021 – Apr 2022</p>
          <ul>
            <li>Installed Siemens 15 kV breakers and rigid conduit to NEC standards in live substations.</li>
            <li>Performed insulation-resistance and contact-resistance testing on 138 kV gear.</li>
          </ul>
        </div>

        <div class="job">
          <h3>Semitrailer Refueler Operator <span class="rank">(MOS 3534)</span></h3>
          <p class="meta">U.S. Marine Corps &nbsp;|&nbsp; May 2020 – Present</p>
          <ul>
            <li>Led 5-Marine crew in 24/7 preventive maintenance of 10k-gallon fuel systems.</li>
            <li>Trained 12 juniors on 24-VDC and 120-VAC electrical troubleshooting; zero mission failures.</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="skills" class="section alt">
      <div class="container">
        <h2>Skills & Certifications</h2>
        <div class="skills-grid">
          <div>
            <h4>Software</h4>
            <ul>
              <li>MATLAB / Simulink</li>
              <li>C / C++</li>
              <li>Python</li>
              <li>LTspice • Multisim</li>
              <li>EasyEDA • Altium</li>
              <li>AutoCAD • Revit</li>
            </ul>
          </div>
          <div>
            <h4>Core Competencies</h4>
            <ul>
              <li>PCB Design & Fabrication</li>
              <li>Embedded Systems</li>
              <li>Control & Signal Processing</li>
              <li>Microcontroller Debug</li>
              <li>Power Systems</li>
              <li>Team Leadership</li>
            </ul>
          </div>
          <div>
            <h4>Certifications</h4>
            <ul>
              <li>OSHA 10 (General Industry)</li>
              <li>NFPA 70E 2024 (Electrical Safety)</li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <section id="contact" class="section">
      <div class="container">
        <h2>Let’s Connect</h2>
        <p>Currently seeking 2025 summer internships or full-time roles in hardware, embedded, or power systems.</p>
        <ul class="contact-list">
          <li><strong>Email:</strong> <a href="mailto:brucely.charles@knights.ucf.edu">brucely.charles@knights.ucf.edu</a></li>
          <li><strong>Phone:</strong> <a href="tel:3214409541">(321) 440-9541</a></li>
          <li><strong>Location:</strong> Orlando, FL (willing to relocate)</li>
          <li><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/brucelycharles" target="_blank">linkedin.com/in/brucelycharles</a></li>
        </ul>
      </div>
    </section>
  </main>

  <footer>
    <div class="container">
      <small>© 2025 Brucely Charles. Built with plain HTML/CSS and zero frameworks.</small>
    </div>
  </footer>
</body>
</html>

:root{
  --bg:#ffffff;
  --bg-alt:#f7f9fc;
  --text:#222;
  --accent:#0057b8; /* UCF gold-blue mix */
  --accent-light:#e5f0ff;
  --border:#e1e4e8;
  --font:'Inter',sans-serif;
}

* {box-sizing:border-box; margin:0; padding:0;}
body {font-family:var(--font); color:var(--text); line-height:1.6;}
a {color:var(--accent); text-decoration:none;}
a:hover{text-decoration:underline;}
.container{max-width:900px;margin:auto;padding:0 1rem;}
.section{padding:3rem 0;}
.section.alt{background:var(--bg-alt);}
h1,h2,h3,h4{line-height:1.2; margin-bottom:.5em;}
h1{font-size:2.2rem;}
h2{font-size:1.8rem; margin-bottom:1rem;}

/* header */
header{background:var(--accent);color:#fff;padding:2.5rem 0;text-align:center;}
.tagline{font-size:1.1rem;opacity:.9;margin:.5rem 0 1.5rem;}
nav{display:flex;gap:1.2rem;justify-content:center;flex-wrap:wrap;}
nav a{color:#fff;font-weight:600;text-transform:uppercase;font-size:.85rem;letter-spacing:.5px;}

/* buttons */
.btn{display:inline-block;background:#fff;color:var(--accent);padding:.6rem 1.2rem;border-radius:4px;font-weight:600;margin-top:1rem;}
.btn:hover{background:var(--accent-light);text-decoration:none;}

/* projects */
.project{background:#fff;border:1px solid var(--border);border-left:4px solid var(--accent);padding:1.2rem;margin-bottom:1.2rem;border-radius:4px;}
.tag{display:inline-block;background:var(--accent-light);color:var(--accent);padding:.2rem .5rem;font-size:.75rem;border-radius:3px;margin:.2rem .2rem 0 0;}

/* experience */
.job{margin-bottom:2rem;}
.meta{color:#555;font-size:.9rem;margin-bottom:.5rem;}
ul{margin-left:1.2rem;}

/* skills */
.skills-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:1.5rem;}

/* contact */
.contact-list{list-style:none;margin-top:1rem;}
.contact-list li{margin-bottom:.5rem;}

/* footer */
footer{background:var(--bg-alt);text-align:center;padding:1.5rem 0;color:#555;font-size:.8rem;}

/* responsive */
@media(max-width:600px){
  nav{flex-direction:column;gap:.6rem;}
  h1{font-size:1.8rem;}
}


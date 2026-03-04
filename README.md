🧑‍💻😂
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Felipe Botina | Portafolio Profesional</title>

<style>

/* ===== BASE ===== */

body{
margin:0;
font-family:'Segoe UI',sans-serif;
background:#0f172a;
color:#e2e8f0;
overflow-x:hidden;
}

/* Fondo tech sutil */
body::before{
content:"";
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background:
radial-gradient(circle at 20% 30%, rgba(56,189,248,0.08), transparent 40%),
radial-gradient(circle at 80% 70%, rgba(14,165,233,0.08), transparent 40%);
z-index:-1;
}

/* ===== HERO ===== */

.hero{
text-align:center;
padding:100px 20px 60px 20px;
background:linear-gradient(135deg,#0f172a,#1e293b);
}

.hero h1{
font-size:40px;
margin:0;
color:white;
}

.hero h2{
font-size:18px;
color:#38bdf8;
margin-top:10px;
}

.hero p{
max-width:600px;
margin:20px auto;
color:#94a3b8;
}

/* ===== CONTENIDO ===== */

.container{
max-width:900px;
margin:40px auto;
padding:0 20px;
}

.card{
background:#1e293b;
padding:30px;
border-radius:16px;
margin-bottom:30px;
box-shadow:0 10px 25px rgba(0,0,0,0.4);
}

/* Animación reveal */
.reveal{
opacity:0;
transform:translateY(40px);
transition:all 1s ease;
}

.reveal.active{
opacity:1;
transform:translateY(0);
}

.card h3{
margin-top:0;
color:white;
}

/* ===== SKILLS ===== */

.skill{
display:inline-block;
background:#334155;
padding:8px 14px;
border-radius:8px;
margin:6px 6px 0 0;
font-size:14px;
}

/* ===== BARRAS STACK ===== */

.bar{
background:#334155;
border-radius:10px;
overflow:hidden;
margin-bottom:15px;
}

.fill{
width:0;
background:linear-gradient(90deg,#38bdf8,#0ea5e9);
color:white;
padding:6px 10px;
font-size:12px;
font-weight:bold;
transition: width 1.5s ease-in-out;
}

/* ===== BOTONES ===== */

.buttons{
text-align:center;
margin-top:30px;
}

.btn{
display:inline-block;
margin:10px;
padding:14px 24px;
border-radius:10px;
text-decoration:none;
font-weight:bold;
}

.btn-whatsapp{
background:#25D366;
color:white;
}

.btn-outline{
border:1px solid #38bdf8;
color:#38bdf8;
}

/* ===== WHATSAPP FLOTANTE ===== */

.whatsapp-float{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
width:55px;
height:55px;
border-radius:50%;
display:flex;
align-items:center;
justify-content:center;
font-size:24px;
text-decoration:none;
box-shadow:0 8px 20px rgba(0,0,0,0.4);
transition:transform 0.3s ease;
z-index:999;
}

.whatsapp-float:hover{
transform:scale(1.1);
}

/* ===== FOOTER ===== */

.footer{
text-align:center;
padding:30px;
font-size:13px;
color:#64748b;
}

/* ===== MODO CLARO AUTOMÁTICO ===== */

@media (prefers-color-scheme: light) {
  body{
    background:#f1f5f9;
    color:#0f172a;
  }

  .card{
    background:white;
    box-shadow:0 10px 25px rgba(0,0,0,0.1);
  }

  .hero{
    background:linear-gradient(135deg,#e2e8f0,#cbd5e1);
  }
}

</style>
</head>

<body>

<div class="hero">
<h1>Felipe Botina</h1>
<h2>Ingeniería en Programación y Telecomunicaciones</h2>
<p>
Perfil técnico con experiencia en campo en el sector de telecomunicaciones,
enfocado en infraestructura de red, configuración de equipos y crecimiento profesional en desarrollo tecnológico.
</p>

<div class="buttons">
<a href="https://wa.me/573046338016?text=Hola%20Felipe,%20vi%20tu%20portafolio%20y%20quiero%20más%20información." 
class="btn btn-whatsapp" target="_blank">
Contactar
</a>

<a href="https://wa.me/573046338016?text=Hola,%20quiero%20conocer%20más%20sobre%20tu%20experiencia%20técnica." 
class="btn btn-outline" target="_blank">
Experiencia Técnica
</a>
</div>
</div>

<div class="container">

<div class="card reveal">
<h3>Experiencia Técnica</h3>
<p>
Experiencia práctica en instalación, validación y soporte de infraestructura de red,
aplicando diagnóstico técnico y optimización de parámetros en campo.
</p>
</div>

<div class="card reveal">
<h3>Formación</h3>
<p>
• Ingeniería en Programación y Telecomunicaciones (En curso)<br>
• Técnico en Telecomunicaciones<br>
• Técnico Mecánico Industrial<br>
• Técnico en Electricidad<br>
• Electrónica Básica
</p>
</div>

<div class="card reveal">
<h3>Stack Tecnológico</h3>

<p><strong>Redes y Telecomunicaciones</strong></p>
<div class="bar"><div class="fill" data-width="85%">85%</div></div>

<p><strong>Configuración de Equipos</strong></p>
<div class="bar"><div class="fill" data-width="80%">80%</div></div>

<p><strong>Programación (Fundamentos)</strong></p>
<div class="bar"><div class="fill" data-width="65%">65%</div></div>

<p><strong>HTML & CSS</strong></p>
<div class="bar"><div class="fill" data-width="70%">70%</div></div>

<p><strong>Automatización / IoT</strong></p>
<div class="bar"><div class="fill" data-width="60%">60%</div></div>

</div>

</div>

<div class="footer">
© 2026 Felipe Botina | Portafolio Profesional
</div>

<a href="https://wa.me/573046338016?text=Hola%20Felipe,%20vi%20tu%20perfil%20y%20quiero%20más%20información." 
class="whatsapp-float" target="_blank">💬</a>

<script>

/* Animación barras */
const fills = document.querySelectorAll('.fill');

function animateBars() {
  fills.forEach(fill => {
    const rect = fill.getBoundingClientRect();
    if(rect.top < window.innerHeight) {
      fill.style.width = fill.getAttribute('data-width');
    }
  });
}

window.addEventListener('scroll', animateBars);
window.addEventListener('load', animateBars);

/* Reveal cards */
function revealOnScroll() {
  const reveals = document.querySelectorAll('.reveal');

  reveals.forEach(element => {
    const windowHeight = window.innerHeight;
    const elementTop = element.getBoundingClientRect().top;
    const visiblePoint = 100;

    if (elementTop < windowHeight - visiblePoint) {
      element.classList.add('active');
    }
  });
}

window.addEventListener('scroll', revealOnScroll);
window.addEventListener('load', revealOnScroll);

</script>

</body>
</html>

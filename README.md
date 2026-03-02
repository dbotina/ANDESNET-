<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AndesNet Soluciones Tecnológicas</title>

<style>
body{
    margin:0;
    font-family:Arial, Helvetica, sans-serif;
    background:#0f172a;
    color:white;
    text-align:center;
}

header{
    background:#111827;
    padding:40px 20px;
}

header img{
    width:220px;
    border-radius:15px;
    margin-bottom:20px;
}

h1{
    color:#38bdf8;
}

section{
    padding:40px 20px;
}

.card{
    background:#1e293b;
    margin:20px auto;
    padding:25px;
    border-radius:15px;
    max-width:700px;
    box-shadow:0 0 20px rgba(0,0,0,0.4);
}

button{
    padding:15px 25px;
    border:none;
    border-radius:30px;
    font-size:16px;
    cursor:pointer;
    margin:10px;
}

.whatsapp{
    background:#25D366;
    color:white;
}

.qr{
    background:#38bdf8;
    color:black;
}

footer{
    background:#111827;
    padding:20px;
    margin-top:40px;
}
</style>
</head>

<body>

<header>
    <!-- IMAGEN LOGO + CAMIONETA -->
    <img src="logo-andesnet.png" alt="AndesNet Logo">
    <h1>ANDESNET SOLUCIONES TECNOLÓGICAS</h1>
    <p>Infraestructura Digital • Telecomunicaciones • Redes</p>
</header>

<section>
<div class="card">
<h2>Perfil Profesional</h2>

<p><strong>David Botina</strong></p>
<p>
Técnico en Telecomunicaciones<br>
Electricidad y Electrónica Básica<br>
Estudiante de Ingeniería de Sistemas<br>
Mecánica Industrial<br>
Infraestructura de Redes y Servidores
</p>

</div>

<div class="card">
<h2>Servicios</h2>

<p>
✔ Instalación y mantenimiento de redes HFC y FTTH<br>
✔ Configuración de MTA y equipos<br>
✔ Infraestructura de servidores<br>
✔ Optimización WiFi 2G / 5G<br>
✔ Soporte técnico especializado
</p>
</div>

<div class="card">
<h2>Contacto</h2>

<a href="https://wa.me/573046338016" target="_blank">
<button class="whatsapp">📲 WhatsApp 3046338016</button>
</a>

<br>

<!-- BOTÓN QR -->
<button class="qr" onclick="mostrarQR()">📷 Mostrar Código QR</button>

<br><br>

<img id="qrImagen" src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://dbotina.github.io/andesnet-soluciones-tecnologicas/" 
style="display:none; margin-top:20px; border-radius:10px;">

</div>
</section>

<footer>
© 2026 AndesNet Soluciones Tecnológicas - Pasto, Colombia
</footer>

<script>
function mostrarQR(){
    var qr = document.getElementById("qrImagen");
    if(qr.style.display === "none"){
        qr.style.display = "block";
    }else{
        qr.style.display = "none";
    }
}
</script>

</body>
</html>

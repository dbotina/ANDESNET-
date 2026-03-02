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
    background:linear-gradient(135deg,#0f172a,#1e293b);
    color:white;
    text-align:center;
}

header{
    padding:50px 20px;
}

header img{
    width:250px;
    border-radius:20px;
    box-shadow:0 0 25px rgba(56,189,248,0.6);
    margin-bottom:25px;
}

h1{
    color:#38bdf8;
    font-size:32px;
}

section{
    padding:40px 20px;
}

.card{
    background:rgba(255,255,255,0.05);
    backdrop-filter:blur(10px);
    margin:25px auto;
    padding:30px;
    border-radius:20px;
    max-width:750px;
    box-shadow:0 0 25px rgba(0,0,0,0.5);
}

button{
    padding:15px 30px;
    border:none;
    border-radius:40px;
    font-size:16px;
    cursor:pointer;
    margin:15px;
    transition:0.3s;
}

button:hover{
    transform:scale(1.05);
}

.whatsapp{
    background:#25D366;
    color:white;
}

.qr-btn{
    background:#38bdf8;
    color:black;
}

.qr-container{
    margin-top:20px;
    padding:20px;
    background:white;
    display:inline-block;
    border-radius:20px;
    box-shadow:0 0 20px rgba(0,0,0,0.4);
}

footer{
    margin-top:40px;
    padding:25px;
    background:#111827;
}
</style>
</head>

<body>

<header>
    <img src="logo-andesnet.png" alt="AndesNet Logo">
    <h1>ANDESNET SOLUCIONES TECNOLÓGICAS</h1>
    <p>Pasto - Colombia | Infraestructura Digital y Telecomunicaciones</p>
</header>

<section>

<div class="card">
<h2>Perfil Profesional</h2>
<p><strong>David Botina</strong></p>

<p>
🔹 Estudiante de Ingeniería de Sistemas<br>
🔹 Técnico en Telecomunicaciones<br>
🔹 Experiencia laboral activa en el campo de las telecomunicaciones<br>
🔹 Electricidad y Electrónica Básica<br>
🔹 Infraestructura de Redes HFC y FTTH<br>
🔹 Mecánica Industrial
</p>

<p style="margin-top:15px; font-size:15px; opacity:0.9;">
Profesional en formación con experiencia práctica en instalación,
mantenimiento y optimización de redes de telecomunicaciones,
infraestructura digital y soporte técnico especializado.
</p>

</div>

<div class="card">
<h2>Servicios</h2>
<p>
✔ Instalación y mantenimiento de redes HFC y FTTH<br>
✔ Configuración de MTA y routers<br>
✔ Optimización WiFi 2G / 5G<br>
✔ Infraestructura de servidores<br>
✔ Soporte técnico especializado en campo
</p>
</div>

<div class="card">
<h2>Contacto</h2>

<a href="https://wa.me/573046338016" target="_blank">
<button class="whatsapp">📲 WhatsApp 3046338016</button>
</a>

<br>

<button class="qr-btn" onclick="mostrarQR()">📷 Ver Código QR Oficial</button>

<div id="qrBox" style="display:none;">
    <div class="qr-container">
        <img src="https://api.qrserver.com/v1/create-qr-code/?size=250x250&data=https://dbotina.github.io/andesnet-soluciones-tecnologicas/" alt="QR AndesNet">
        <p style="color:black; font-weight:bold; margin-top:10px;">
        ANDESNET - Pasto Colombia
        </p>
    </div>
</div>

</div>

</section>

<footer>
© 2026 AndesNet Soluciones Tecnológicas - Pasto, Colombia
</footer>

<script>
function mostrarQR(){
    var box = document.getElementById("qrBox");
    if(box.style.display === "none"){
        box.style.display = "block";
    }else{
        box.style.display = "none";
    }
}
</script>

</body>
</html>


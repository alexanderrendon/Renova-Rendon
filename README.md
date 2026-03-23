# Renova-Rendon

<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Renova Rendon</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
<!-- Font Awesome para iconos -->
<script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
<style>
* {margin:0; padding:0; box-sizing:border-box;}
body {font-family:'Poppins', sans-serif; background:#0f0f0f; color:#fff; line-height:1.6;}
a {text-decoration:none;}
header {
  background: url('https://images.unsplash.com/photo-1503387762-592deb58ef4e') center/cover fixed;
  height:90vh; display:flex; align-items:center; justify-content:center; text-align:center;
}
header div {
  background: rgba(0,0,0,0.7); padding:30px; border-radius:15px;
  animation: fadeInDown 1.5s ease;
}
header h1 {font-size:50px; color:#FFD700;}
header p {margin:15px 0; font-size:20px;}
.btn {
  background:#FFD700; color:#000; padding:12px 25px; border:none; border-radius:8px;
  font-weight:bold; cursor:pointer; transition: all 0.3s ease;
}
.btn:hover {background:#ffbf00; transform: scale(1.05);}

@keyframes fadeInDown {
  0% {opacity:0; transform: translateY(-30px);}
  100% {opacity:1; transform: translateY(0);}
}

section {padding:60px 20px;}
h2 {text-align:center; margin-bottom:30px; color:#FFD700;}

.services {
  display:grid; grid-template-columns:repeat(auto-fit, minmax(250px, 1fr)); gap:25px;
}

.card {
  background:#1c1c1c; padding:25px; border-radius:15px; transition:0.3s; text-align:center;
}
.card:hover {transform:translateY(-10px); box-shadow:0 10px 20px rgba(255,215,0,0.3);}
.card h3 {color:#FFD700; margin-bottom:10px; font-size:22px;}
.card p {color:#e0e0e0;}

.card i {font-size:28px; margin-bottom:10px; color:#FFD700; display:block;}

.about, .contact {text-align:center; max-width:800px; margin:auto; color:#e0e0e0;}

footer {
  background:#000; text-align:center; padding:20px; color:#fff;
}
footer div a {
  margin: 0 10px; color:#FFD700; font-size:24px; transition:0.3s;
}
footer div a:hover {color:#ffbf00; transform:scale(1.2);}
</style>
</head>
<body>

<header>
  <div>
    <h1>RENOVA RENDON</h1>
    <p>Expertos en Construcción y Renovación</p>
    <a href="tel:0466345611"><button class="btn">📞 Llamar Ahora</button></a>
  </div>
</header>

<section>
  <h2>🔧 Nuestros Servicios</h2>
  <div class="services">
    <div class="card"><i class="fas fa-bolt"></i><h3>Electricidad</h3><p>Instalaciones completas y reparaciones</p></div>
    <div class="card"><i class="fas fa-water"></i><h3>Plomería</h3><p>Fugas, tuberías y mantenimiento</p></div>
    <div class="card"><i class="fas fa-paint-roller"></i><h3>Pintura</h3><p>Interior y exterior profesional</p></div>
    <div class="card"><i class="fas fa-th-large"></i><h3>Carrelage</h3><p>Pisos y paredes de alta calidad</p></div>
    <div class="card"><i class="fas fa-home"></i><h3>Tejados</h3><p>Estructura y reparación</p></div>
    <div class="card"><i class="fas fa-thermometer-half"></i><h3>Aislamiento</h3><p>Ahorro energético interior y exterior</p></div>
  </div>
</section>

<section class="about">
  <h2>🏗️ Sobre Nosotros</h2>
  <p>Somos especialistas en reformas completas en Bruselas. Ofrecemos trabajos profesionales en construcción, electricidad, fontanería, pintura y más. Garantizamos calidad, rapidez y precios competitivos.</p>
</section>

<section class="contact">
  <h2>📞 Contacto</h2>
  <p style="font-size:22px">0466345611</p>
  <a href="https://wa.me/32466345611"><button class="btn">💬 WhatsApp</button></a>
</section>

<footer>
  <p>Servicio en Bruselas y alrededores</p>
  <div>
    <a href="https://wa.me/32466345611" target="_blank">💬 WhatsApp</a>
    <a href="#" target="_blank">📸 Instagram</a>
    <a href="#" target="_blank">👍 Facebook</a>
  </div>
</footer>

</body>
</html>
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AlsurdelMundo</title>
    <link rel="stylesheet" href="proyecto3.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/fontawesome.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css">
</head>
<body>
    <header>
    <section  class="wrapper">
            <div class="icono-logo">
                <div class="logo">
                    <img src="./img/Logo.png.png">
                </div>
            </div>
            <nav class="navbar"> 
            <input type="checkbox" id="menu-toggle">
            <label for="menu-toggle" class="menu-icon">
                <div class="line"></div>
                <div class="line"></div>
                <div class="line"></div>
            </label>
                <ul class="nav-links">
                    <li><a href="#">Inicio</a></li>
                    <li><a href="#">Conocenos</a></li>
                    <li><a href="#">Destinos</a></li>
                    <li><a href="#">Contacto</a></li>
                </ul>
            </nav>
        <!--texto en imagen-->
        <div class="container">
            <h1>Turismo Al Sur del Mundo</h1>
            <p>Explora destinos increibles y vive experiencias unicas.Podrás realizar actividades ajustadas a tu estilo de turismo, verás paisajes majestuosos de la patagonia de Chile, lugares inimaginables de la Antártida, Fauna autóctona en su habitat. Será una aventura inolvidable. </p>
            <button class="btn" type="button">Descubre más</button>
        </div>
    </section>
    </header>
    <main>
        <div class="container1">
            <div class="card">
                <img src="./img/objetivo.png" alt="img1">
                <h2>Nuestra Historia</h2>
                <p>Creemos que nuestra misión es ser viajeros de la patagonia, aventureros del sur del mundo.  con la fuerte convicción en el mantenimiento de areas y el turismo sustentable y responsable. Somos voceros de los ancestros que habitaron la tierra y el mar de esta maravillosa zona.</p>
            </div>
            <div class="card">
                <img src="./img/vision-compartida.png" alt="img2">
                <h2>Nuestro Sueño</h2>
                <p>Queremos que las personas conozcan y se enamoren de cada lugar de la Patagonia, se asombren de sus paisajes, valoren la esencia de su naturaleza y fauna. Contribuir a la conservación ambiental mediante la conciencia colectiva de aquellos que visitan la Patagonia.</p>
            </div>
        </div>
        <!--efecto-->
        
        <section class="sec1"></section>
        <div class="title"><p>Trekking en el Parque Torres del Paine</p></div>
        <section class="sec2"></section>
        <div class="title"><p>Navegación a la Isla Magdalena</p></div>
        <section class="sec3"></section>
        <div class="title"><p>Kayak con Ballenas</p></div>
        <section class="sec4"></section>
        <div class="title"><p>Atardecer en la Antártica</p></div> 
        
        <!--wave-->
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1400 155">
            <path fill="#ff8000d3" fill-opacity="1" d="M0,64L48,74.7C96,85,192,107,288,112C384,117,480,107,576,96C672,85,768,75,864,90.7C960,107,1056,149,1152,154.7C1248,160,1344,128,1392,112L1440,96L1440,0L1392,0C1344,0,1248,0,1152,0C1056,0,960,0,864,0C768,0,672,0,576,0C480,0,384,0,288,0C192,0,96,0,48,0L0,0Z"></path>
        </svg>
        <h3>Conoce nuestros destinos</h3>
            <div class="grid-container">
                <div class="producto">
                    <img src="./img/producto1.jpg">
                    <h4>Patagonia para todos</h4>
                    <p>Conoce la Patagonia Chile, sus lugares más emblemáticos, su gastronomia y cultura. Una travesia de 5 días por la capital de la Region de Magallanes, Punta arenas, donde podras realizar la navegación a la isla magdalena o hacer un recorrido a las condoreras de la zona.</p>
                </div>
                <div class="producto">
                    <img src="./img/producto2.jpg">
                    <h4>Aventura Extrema</h4>
                    <p>Recorre lugares exclusivos de la Patagonia, realiza Trekking en las Torres del Paine, Trekking o escalada en el Cerro Castillo,Navega por el glaciar Grey, Camina por senderos naturales llenos de aire patonico y naturaleza inhospita, realiza kayak con ballenas en punta arenas.</p>
                </div>
                <div class="producto">
                    <img src="./img/producto3.jpg">
                    <h4>Ruta Ancestral</h4>
                    <p>Un recorrido por la historia ancestral, su cultura y estilo de vida. Recorre fiordos y paisajes australes mediante navegación y carretera, con guias turisticos que te contaran la historia de la gente de  la zona, asentamientos humanos y cómo era vivir en esa época.</p>
                </div>
                <div class="producto">
                    <img src="./img/producto4.webp">
                    <h4>Atardecer en la Antártida</h4>
                    <p>Un viaje unico e inolvidable, una salida desde punta arenas en avioneta, sobrevuela la antartida Chilena y aterriza en la base/campamento, donde podras recorrer en trekking la zona, etc.Y finalmente una cena austral para esperar el atardecer en uno de los lugares más al sur del mundo.</p>
                </div>
            </div>
    </main>
    <footer>
        <div class="container2">
            <div class="tfoot">
                <div class="footer-enlaces">
                    <h5>Politicas de la empresa</h5>
                    <ul>
                        <li><a href="#">Reservas de Servicios</a></li>
                        <li><a href="#">Modalidad de pago</a></li>
                        <li><a href="#">Politica de devoluciones</a></li>
                    </ul>
                </div>
                <div class="footer-enlaces">
                    <h5>Preguntas frecuentes</h5>
                    <ul>
                        <li><a href="#">Idiomas en los recorridos</a></li>
                        <li><a href="#">Asistencia medica</a></li>
                        <li><a href="#">Seguro de viajes</a></li>
                    </ul>
                </div>
                <div class="footer-enlaces">
                    <h5>Normas de turismo</h5>
                    <ul>
                        <li><a href="#">SERNATUR</a></li>
                        <li><a href="#">Conservación ambiental</a></li>
                        <li><a href="#">Ordenanzas municipales</a></li>
                    </ul>
                </div>
                <div class="footer-enlaces">
                    <h5>Comunícate con nosotros</h5>
                    <div class="medios">
                        <a href="#"><i class="fas fa-phone-alt"></i></a>
                        <a href="#"><i class="fas fa-envelope"></i></a>
                        <a href="#"><i class="fab fa-whatsapp"></i></a>
                    </div>
                </div>
                <div class="footer-enlaces">
                    <h5>Politicas de la empresa</h5>
                    <div class="social-media">
                        <a href="#"><i class="fab fa-facebook"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-tiktok"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
            </div>
        </div>
    </footer>
    
</body>
</html>

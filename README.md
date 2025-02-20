<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AlsurdelMundo</title>
    <link rel="stylesheet" href="proyecto3.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/fontawesome.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css">
    <style>
        *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    list-style: none;
}
body {
    font-family: sans-serif bolder;
    margin: 0;
    padding: 0;
    background-color: #fff;
}
.wrapper{
    background: rgba(0,0,0,0.1) url(![torresdelpaine](https://github.com/user-attachments/assets/418b7393-6e94-43ad-85ad-65dce29f0347)
) no-repeat;
    background-position: center;
    background-size: cover;
    min-height: 100vh;
    overflow:hidden;
    background-blend-mode: overlay;
}
.icono-logo{
    height: 0;
}
.logo img{
    height: 40px;
    justify-content: flex-start;
}
.navbar {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    padding: 20px 64px;
    background-color: rgba(250, 123, 49, 0.179);
    position: relative;
}
.nav-links {
    list-style: none;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    padding: 0;
    margin: 0;
    display: flex;
    transition: all 0.5s ease;
}
.nav-links li {
    margin-left: 24px;
}
.nav-links a {
    text-decoration: none;
    color: #ffffff;
    font-size: 17px;
    padding: 8px 24px;
    border-radius: 30px;
    transition: background-color 0.3s ease;
}
.nav-links a:hover {
    background-color: #ff8000d3;
}
.menu-icon {
    display: none;
    flex-direction: column;
    cursor: pointer;
    margin-left: auto;
    position: relative;
    z-index: 1;
}
.menu-icon .line {
    width: 30px;
    height: 3px;
    background-color: #ffffff;
    margin: 5px 0;
    transition: all 0.3s ease;
}
#menu-toggle {
    display: none;
}
@media (max-width: 400px) {
    .navbar {
        padding: 6px;
    }
    .menu-icon {
        display: flex;
    }
    .nav-links {
        position: absolute;
        top: 50px;
        right: 0;
        width: 100%;
        max-height: 0;
        overflow: hidden;
        flex-direction: column;
        letter-spacing: 1px;
        background-color: #ff8000;
        text-align: center;
        transition: max-height 0.5s ease;
    }
    .nav-links li {
        margin: 0;
        padding: 30px 0;
        width: 100%;
    }
    .nav-links a {
        padding: 10px 20px;
        width: 100%;
    }
    #menu-toggle:checked + .menu-icon + .nav-links {
        max-height: 100vh;
    }
    #menu-toggle:checked + .menu-icon .line:nth-child(1) {
        transform: rotate(45deg) translate(15px, 3px);
    }
    #menu-toggle:checked + .menu-icon .line:nth-child(2) {
        transform: scale(0);
    }
    #menu-toggle:checked + .menu-icon .line:nth-child(3) {
        transform: rotate(-45deg) translate(15px, -4px);
    }
}
.container{
    max-width: 50%;
    height: 100vh;
    padding: 200px 80px;
}
.container h1{
    color: white;
    font-size: 3rem;
    text-align: left;
    text-shadow: 1px 1px 2px rgb(179, 179, 179);
}
.container p{
    color: white;
    text-align: justify;
    letter-spacing: 1px;
    font-size: 1.25rem;
    text-shadow: 0px 0px 1px rgb(132, 132, 132);
    padding: 25px 0;
    font-weight: 300;
    font-family: sans-serif;
}
.btn{
    background-color: #ff8000;
    box-shadow: inset 2px 2px 3px rgba(255, 255, 255, 0.6), inset -2px -2px 3px rgba(0, 0, 0, 0.6);
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif bolder;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    font-size: 1.25rem;
    cursor: pointer;
    text-align: center;
}
.btn:hover{
    background-color: #3b3b3b;
}
/*media queries*/
@media(max-width: 400px) {
    
    .container{
        max-width: 90%;
        padding: 200px 30px;
        text-align: center;
        justify-content: center;
    }
    .container h1{
        padding-top: 50%;
        font-size: 2rem;
    }
    .container p{
        font-size: 1rem;
        padding: 15px 0;
    }  
    .btn{
        font-size: 1rem;
        padding: 12px 20px;
    }
}
/*medium devices*/
@media(max-width: 768px) {
    
    .container {
        max-width: 100%;
        padding: 150px 40px;
    }

    .container h1 {
        font-size: 3rem;
    }

    .container p {
        font-size: 1.2rem;
    }

    .btn {
        font-size: 1.2rem;
        padding: 15px 25px;
    }
}
main{
    padding: 0px 0px;
    color:#000;
    text-align: center;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.container1{
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 30px 10px;
    background-color: #ff8000d3;
    flex-wrap: wrap; /*para que se ajuste al tamaño de la pantalla*/
}
.card{
    align-items: center;
    background-color: white;
    max-width: 40%;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin: 10px;
}
.card img{
    height: 30px;
    align-content: center;
    margin: auto;
    border-radius: 10px;
}
.card h2{
    color: #dd7207;
    text-shadow: -1px -1px 1px rgb(13, 13, 13);
    font-size: 24px;
    padding: 10px 0;
}
.card p{
    color: #000;
    text-align: justify;
    font-size: 16px;
    letter-spacing: 1px;
    padding: 10px 0;
}
/*media queries*/
/*small devices*/
@media (max-width: 400px) {
    .card {
        max-width: 100%;
        margin: 10px auto;
        padding: 15px;
    }
}
/*medium devices*/
@media (max-width: 768px) {
    .card {
        max-width: 100%;
        margin: 10px auto;
        padding: 15px;
    }
}
.sec1{
    background: url(![TdelP](https://github.com/user-attachments/assets/7cc94ae0-8c7d-4e78-8df7-d54cc1321ec9)
);
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
}
.sec2{
    background: url(![trestorres](https://github.com/user-attachments/assets/08bfb38f-20ab-45e4-8d2b-f6ae01ce7b27)
);
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
}
.sec3{
    background: url(../img/kayak.avif);
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
}
.sec4{
    background: url(../img/Antarticaovernight.webp);
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
}
section{
    width: 100%;
    height: 100vh;
}
.title{
    width: 100%;
    height: 10vh;
    background-color: #ff8000d3;
    text-align: center;
}
.title p{
    color:#fff;
    font-size: 2rem;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height:normal;
}
.wave{
    position: absolute;
    color: #ff8000d3;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 100px;
    background: url(wave.svg);
    background-size: 100% 100%;
}
h3{
    color: #ff8000d3;
    font-size: 3rem;
    padding: 20px 0;
}
.producto{
    padding: 2em;
    border: 1px solid #ff8000d3;
    border-radius: 10px;
    background-color: #ffffff;
    text-align: center justify;
}
.producto img{
    height:200px;
    padding: 2px 2px;
    justify-content: center;
}
h4{
    font-size: 1.3rem;
    color: #ff8000;
    gap:2px;
}
.producto p{
    text-align: justify;
    font-size: 1rem;
    letter-spacing:1px;
}
.grid-container{
    padding: 10px 10px;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap:15px;
    justify-content: center;
    bottom: 20px;
}
footer{
    background-color: #eb7a09;
    padding: 100px 0;
}
.container2{
    max-width: 1200px;
    margin: 0 auto;
}
.tfoot{
    display: flex;
    flex-wrap: wrap;
}
.footer-enlaces{
    width: 20%;
    padding: 0 0px;
}
.footer-enlaces h5{
    font-size: 20px;
    color: #fff;
    margin-bottom: 25px;
    font-weight: 500;
    padding-bottom: 10px;
    display: inline-block
}
.footer-enlaces ul li a{
    font-size: 18px;
    text-decoration: none;
    color:#fff;
    display: block;
    margin-bottom: 15px;
    transition: all .3s ease;
}
.footer-enlaces ul li a:hover{
    color: #000;
    padding-left: 6px;
}
.medios a{
    display: inline-block;
    min-height: 40px;
    width: 40px;
    background-color: #cf6c1bbe;
    margin: 0 10px 10px 0;
    text-align: center;
    line-height: 40px;
    border-radius: 50%;
    color:#fff;
    transition: all .3s ease;
}
.medios a:hover{
    background-color: #000;
}
.social-media a{
    display: inline-block;
    min-height: 40px;
    width: 40px;
    background-color: #cf6c1bbe;
    margin: 0 10px 10px 0;
    text-align: center;
    line-height: 40px;
    border-radius: 50%;
    color:#fff;
    transition: all .3s ease;
}
.social-media a:hover{
    background-color: #000;
}
@media(max-width:991px){
    .tfoot{
        text-align: center;
    }
    .footer-enlaces{
        width: 100%;
        margin-bottom: 30px;
    }
}
    </style>
</head>
<body>
    <header>
    <section  class="wrapper">
            <div class="icono-logo">
                <div class="logo">
                    <img src=".![Logo png](https://github.com/user-attachments/assets/47a82ae4-aef7-44aa-806f-1d220e40209b)
">
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
                <img src="![objetivo](https://github.com/user-attachments/assets/77820c93-c3ee-4353-b266-c8bb56eeb605)
" alt="img1">
                <h2>Nuestra Historia</h2>
                <p>Creemos que nuestra misión es ser viajeros de la patagonia, aventureros del sur del mundo.  con la fuerte convicción en el mantenimiento de areas y el turismo sustentable y responsable. Somos voceros de los ancestros que habitaron la tierra y el mar de esta maravillosa zona.</p>
            </div>
            <div class="card">
                <img src="![vision-compartida](https://github.com/user-attachments/assets/d657e897-7484-48be-b285-ec074626ce74)
" alt="img2">
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
                    <img src="![producto1](https://github.com/user-attachments/assets/ecc3c45b-e40c-472e-a664-884618370dc5)
">
                    <h4>Patagonia para todos</h4>
                    <p>Conoce la Patagonia Chile, sus lugares más emblemáticos, su gastronomia y cultura. Una travesia de 5 días por la capital de la Region de Magallanes, Punta arenas, donde podras realizar la navegación a la isla magdalena o hacer un recorrido a las condoreras de la zona.</p>
                </div>
                <div class="producto">
                    <img src="![producto2](https://github.com/user-attachments/assets/ba02f62f-2070-4cc3-85ee-d7b88bcf406a)
">
                    <h4>Aventura Extrema</h4>
                    <p>Recorre lugares exclusivos de la Patagonia, realiza Trekking en las Torres del Paine, Trekking o escalada en el Cerro Castillo,Navega por el glaciar Grey, Camina por senderos naturales llenos de aire patonico y naturaleza inhospita, realiza kayak con ballenas en punta arenas.</p>
                </div>
                <div class="producto">
                    <img src="![producto3](https://github.com/user-attachments/assets/155eb1c0-6dba-4ae8-9ff7-4c5566c2ecc9)
">
                    <h4>Ruta Ancestral</h4>
                    <p>Un recorrido por la historia ancestral, su cultura y estilo de vida. Recorre fiordos y paisajes australes mediante navegación y carretera, con guias turisticos que te contaran la historia de la gente de  la zona, asentamientos humanos y cómo era vivir en esa época.</p>
                </div>
                <div class="producto">
                    <img src="![trestorres](https://github.com/user-attachments/assets/0bdd1a2d-7033-4801-8bf2-3c20f0aea97c)
">
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

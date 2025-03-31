# Fundacion-Divina-Esperanza

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fundación Divina Esperanza</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container">
            <a class="navbar-brand" href="#">Fundación Divina Esperanza</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#nosotros">Nosotros</a></li>
                    <li class="nav-item"><a class="nav-link" href="#proyectos">Proyectos</a></li>
                    <li class="nav-item"><a class="nav-link" href="#ayuda">Contacto</a></li>
                    <li class="nav-item"><a class="nav-link" href="#ayuda">Cómo Ayudar</a></li>
                    <li class="nav-item"><a class="nav-link" href="#ubicacion">Ubicación</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <header class="bg-primary text-white text-center py-5">
        <h1>Bienvenidos a Fundación Divina Esperanza</h1>
        <p>Trabajando juntos por un futuro mejor</p>
    </header>
    <section id="nosotros" class="container py-5">
        <h2>Quiénes Somos</h2>
        <p>Somos una entidad al servicio del adulto mayor sin ánimo de lucro, la cual ampara a 30 personas de la tercera edad, brindándoles y dándoles una mejor calidad de vida. Es por ello que acudimos a personas caritativas, con buen corazón y bondadosas para que nos tengan en cuenta para poder seguir albergando a estas personas mayores que no tienen los recursos y en su gran mayoría ni tienen personas que se hagan responsables de ellos.</p>
    </section>
    <section id="proyectos" class="container py-5">
        <h2>Proyectos</h2>
        <p>En nuestra fundación trabajamos en diversos proyectos que buscan mejorar la calidad de vida de los adultos mayores. Desde programas de alimentación hasta actividades recreativas y de integración, cada iniciativa está diseñada para brindar bienestar y apoyo.</p>
    </section>
    <section id="contacto" class="container py-5">
        <h2>Contacto</h2>
    </section>
    <section id="ayuda" class="container py-5">
        <h2>Formas de Colaborar</h2>
        <div class="accordion" id="accordionAyuda">
            <div class="accordion-item">
                <h2 class="accordion-header" id="headingMonetario">
                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseMonetario" aria-expanded="true" aria-controls="collapseMonetario">
                        Donaciones Monetarias
                    </button>
                </h2>
                <div id="collapseMonetario" class="accordion-collapse collapse show" aria-labelledby="headingMonetario" data-bs-parent="#accordionAyuda">
                    <div class="accordion-body">
                        <p>Puedes apoyarnos con donaciones monetarias. Ingresa tus datos y serás dirigido al portal de pago seguro.</p>
                        <form>
                            <div class="mb-3">
                                <label for="nombreDonante" class="form-label">Nombre</label>
                                <input type="text" class="form-control" id="nombreDonante" required>
                            </div>
                            <div class="mb-3">
                                <label for="correoDonante" class="form-label">Correo Electrónico</label>
                                <input type="email" class="form-control" id="correoDonante" required>
                            </div>
                            <div class="mb-3">
                                <label for="telefonoDonante" class="form-label">Número de Celular</label>
                                <input type="tel" class="form-control" id="telefonoDonante" required>
                            </div>
                            <div class="mb-3">
                                <label for="montoDonacion" class="form-label">Monto a Donar</label>
                                <input type="number" class="form-control" id="montoDonacion" required>
                            </div>
                            <button type="submit" class="btn btn-primary">Donar</button>
                        </form>
                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="headingFisico">
                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseFisico" aria-expanded="true" aria-controls="collapseFisico">
                        Donaciones Físicas
                    </button>
                </h2>
                <div id="collapseFisico" class="accordion-collapse collapse" aria-labelledby="headingFisico" data-bs-parent="#accordionAyuda">
                    <div class="accordion-body">
                        <p>Puedes donar artículos como útiles de aseo, muebles o alimentos. Completa el siguiente formulario para coordinar la entrega:</p>
                        <form>
                            <div class="mb-3">
                                <label for="nombreDonanteFisico" class="form-label">Nombre</label>
                                <input type="text" class="form-control" id="nombreDonanteFisico" required>
                            </div>
                            <div class="mb-3">
                                <label for="correoDonanteFisico" class="form-label">Correo Electrónico</label>
                                <input type="email" class="form-control" id="correoDonanteFisico" required>
                            </div>
                            <div class="mb-3">
                                <label for="telefonoDonanteFisico" class="form-label">Número de Celular</label>
                                <input type="tel" class="form-control" id="telefonoDonanteFisico" required>
                            </div>
                            <div class="mb-3">
                                <label for="tipoDonacion" class="form-label">Tipo de Donación</label>
                                <select class="form-control" id="tipoDonacion" required>
                                    <option value="aseo">Utilidad de Aseo</option>
                                    <option value="higiene">Higiene Personal</option>
                                    <option value="muebles">Muebles</option>
                                    <option value="alimentos">Mercado/Alimentación</option>
                                </select>
                            </div>
                            <div class="mb-3">
                                <label for="descripcionDonacion" class="form-label">Descripción de la Donación</label>
                                <textarea class="form-control" id="descripcionDonacion" rows="3"></textarea>
                            </div>
                            <button type="submit" class="btn btn-primary">Enviar</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="ubicacion" class="container py-5">
        <h2>Ubicación</h2>
        <p>Nos encontramos en: Calle 41 bis sur # 1b - 09, Barrio San Martín de Loba, Localidad de San Cristóbal, Bogotá, Colombia.</p>
        <iframe src="https://www.google.com/maps?q=Calle+41+bis+sur+%23+1b+-+09,+Bogotá,+Colombia&output=embed" width="100%" height="400" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </section>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
    <section id="redes-sociales" class="container py-5 text-center">
        <h2>Síguenos en nuestras Redes Sociales</h2>
        <p>Si quieres seguirnos y visitar nuestras redes sociales, síguelas aquí:</p>
        <img src="facebook-logo.png" alt="Facebook" width="50">
        <img src="instagram-logo.png" alt="Instagram" width="50">
    </section>
</body>
</html>




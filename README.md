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
                    <li class="nav-item"><a class="nav-link" href="#ayuda">Cómo Ayudar</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
                    <li class="nav-item"><a class="nav-link" href="#ubicacion">Ubicación</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <header class="bg-primary text-white text-center py-5">
        <h1>Bienvenidos a Fundación Divina Esperanza</h1>
        <p>Trabajando juntos por un futuro mejor</p>
    </header>
    <section id="ayuda" class="container py-5">
        <h2>Cómo Ayudar</h2>
        <div class="accordion" id="accordionAyuda">
            <div class="accordion-item">
                <h2 class="accordion-header" id="headingOne">
                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                        Donaciones Monetarias
                    </button>
                </h2>
                <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionAyuda">
                    <div class="accordion-body">
                        <form action="#" method="POST">
                            <div class="mb-3">
                                <label for="nombre" class="form-label">Nombre Completo</label>
                                <input type="text" class="form-control" id="nombre" required>
                            </div>
                            <div class="mb-3">
                                <label for="correo" class="form-label">Correo Electrónico</label>
                                <input type="email" class="form-control" id="correo" required>
                            </div>
                            <div class="mb-3">
                                <label for="telefono" class="form-label">Número de Celular</label>
                                <input type="tel" class="form-control" id="telefono" required>
                            </div>
                            <div class="mb-3">
                                <label for="monto" class="form-label">Monto a Donar</label>
                                <input type="number" class="form-control" id="monto" required>
                            </div>
                            <button type="submit" class="btn btn-primary">Ir a PSE</button>
                        </form>
                    </div>
                </div>
            </div>
            <div class="accordion-item">
                <h2 class="accordion-header" id="headingTwo">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                        Donaciones Físicas
                    </button>
                </h2>
                <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionAyuda">
                    <div class="accordion-body">
                        <form action="#" method="POST">
                            <div class="mb-3">
                                <label for="nombreDonante" class="form-label">Nombre Completo</label>
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
                                <label for="tipoDonacion" class="form-label">Tipo de Donación</label>
                                <select class="form-control" id="tipoDonacion" required>
                                    <option value="aseo">Utilidad de Aseo</option>
                                    <option value="higiene">Aseo Personal</option>
                                    <option value="muebles">Muebles</option>
                                    <option value="mercado">Mercado/Alimentación</option>
                                </select>
                            </div>
                            <div class="mb-3">
                                <label for="descripcionDonacion" class="form-label">Descripción de la Donación</label>
                                <textarea class="form-control" id="descripcionDonacion" rows="3" required></textarea>
                            </div>
                            <button type="submit" class="btn btn-primary">Enviar</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


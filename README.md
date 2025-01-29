<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Enrique Mendia - Portafolio</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">Enrique Mendia</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link" href="#about">Sobre Mí</a></li>
                    <li class="nav-item"><a class="nav-link" href="#projects">Proyectos</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contact">Contacto</a></li>
                </ul>
            </div>
        </div>
    </nav>
    <!-- Hero Section -->
    <header class="hero text-white text-center">
        <div class="container">
            <h1>¡Hola! Soy Enrique Mendia</h1>
            <p>Ingeniero en Redes & Desarrollador Web</p>
            <a href="#projects" class="btn btn-primary">Ver Proyectos</a>
        </div>
    </header>
    <!-- Sobre Mí -->
    <section id="about" class="container my-5">
        <h2 class="text-center">Sobre Mí</h2>
        <p class="text-center">Soy un apasionado por la tecnología, especializado en redes, seguridad informática y desarrollo web. Me encanta resolver problemas y crear soluciones eficientes.</p>
    </section>
    <!-- Proyectos -->
    <section id="projects" class="container my-5">
        <h2 class="text-center">Mis Proyectos</h2>
        <div class="row">
            <div class="col-md-4">
                <div class="card">
                    <img src="project1.jpg" class="card-img-top" alt="Proyecto 1">
                    <div class="card-body">
                        <h5 class="card-title">Sistema de CCTV</h5>
                        <p class="card-text">Instalación y configuración de un sistema de videovigilancia con monitoreo remoto.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="project2.jpg" class="card-img-top" alt="Proyecto 2">
                    <div class="card-body">
                        <h5 class="card-title">Aplicación de Servicios Técnicos</h5>
                        <p class="card-text">Desarrollo de 'RapiFix', una app de servicios técnicos a domicilio.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card">
                    <img src="project3.jpg" class="card-img-top" alt="Proyecto 3">
                    <div class="card-body">
                        <h5 class="card-title">Servidor UNMS</h5>
                        <p class="card-text">Implementación de un servidor UNMS para la gestión de redes con Ubiquiti.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Contacto -->
    <section id="contact" class="text-center bg-dark text-white p-5">
        <h2>Contáctame</h2>
        <p>Sígueme en mis redes sociales o envíame un mensaje.</p>
        <a href="https://www.linkedin.com/in/enrique-mendia" class="btn btn-light mx-2">LinkedIn</a>
        <a href="https://github.com/enriquemendia" class="btn btn-light mx-2">GitHub</a>
        <a href="mailto:enrique@example.com" class="btn btn-primary mx-2">Email</a>
    </section>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>


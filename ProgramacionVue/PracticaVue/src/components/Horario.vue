<template>
    <div class="container">
        <!-- Barra de navegación -->
       <nav class="navbar navbar-expand-lg navbar-dark bg-success fixed-top">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="bi bi-globe-americas"></i> Explora el Mundo
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a class="nav-link active" href="#">Inicio</a></li>
                    <li class="nav-item"><a class="nav-link" href="#destinos">Destinos</a></li>
                    <li class="nav-item"><a class="nav-link" href="#blog">Blog</a></li>
                    <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="jumbotron jumbotron-fluid bg-dark text-white mt-5 pt-5">
        <div class="container py-5 text-center">
            <h1 class="display-4">Descubre los Lugares Más Increíbles del Planeta</h1>
            <p class="lead">Viajes personalizados y experiencias únicas</p>
            <a href="#destinos" class="btn btn-success btn-lg mt-3">Explorar Destinos</a>
        </div>
    </header>

    <!-- Destinos destacados -->
    <section id="destinos" class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">Destinos Populares</h2>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="card h-100">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSilLrbClSZzzL9K5trfD3RIl9ulAA5mgo--w&s" class="card-img-top" alt="Montañas" width="400" height="400">
                        <div class="card-body">
                            <h5 class="card-title">Aventura en Montaña</h5>
                            <p class="card-text">Descubre los picos más altos y paisajes espectaculares.</p>
                            <div class="d-grid">
                                <a href="#" class="btn btn-outline-success">Ver Paquetes</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card h-100">
                        <img src="https://images.acuarioinbursa.com.mx/img/2022/08/Visita-el-Mar-de-la-ciudad.-scaled.jpg" class="card-img-top" alt="Playa" width="400" height="400">
                        <div class="card-body">
                            <h5 class="card-title">Playas Paradisíacas</h5>
                            <p class="card-text">Arena blanca y aguas cristalinas te esperan.</p>
                            <div class="d-grid">
                                <a href="#" class="btn btn-outline-success">Ver Paquetes</a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card h-100">
                        <img src="https://media.vogue.mx/photos/5f95db10d3489a2988c5d7b6/1:1/w_2011,h_2011,c_limit/Ciudad-de-Me%CC%81xico-A%CC%81ngel-de-la-Independencia.jpg" class="card-img-top" alt="Ciudad" width="400" height="400">
                        <div class="card-body">
                            <h5 class="card-title">Ciudades Vibrantes</h5>
                            <p class="card-text">Experimenta la cultura urbana alrededor del mundo.</p>
                            <div class="d-grid">
                                <a href="#" class="btn btn-outline-success">Ver Paquetes</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Suscribete -->
    <section class="bg-success text-white py-5">
        <div class="container text-center">
            <h3>Suscríbete a nuestro explorador</h3>
            <p>Recibe ofertas exclusivas y novedades de viajes</p>
            <form class="row justify-content-center">
                <div class="col-md-6">
                    <div class="input-group mb-3">
                        <input type="email" class="form-control" placeholder="Ingresa tu email">
                        <button class="btn btn-dark" type="button">Suscribirse</button>
                    </div>
                </div>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-4">
        <div class="container">
            <div class="row">
                <div class="col-md-6">
                    <h5>Contacto</h5>
                    <p>Oliverio, Alain, Josue Angel, Hector Eduardo<br>Tel: +52 953 567 8901</p>
                </div>
                <div class="col-md-6 text-end">
                    <h5>Síguenos</h5>
                    <a href="#" class="text-white me-3"><i class="bi bi-facebook"></i></a>
                    <a href="#" class="text-white me-3"><i class="bi bi-instagram"></i></a>
                    <a href="#" class="text-white"><i class="bi bi-twitter"></i></a>
                </div>
            </div>
            <div class="text-center mt-3">
                <p>&copy; 2024 Explora el Mundo. Todos los derechos reservados.</p>
            </div>
        </div>
    </footer>
    </div>
</template>

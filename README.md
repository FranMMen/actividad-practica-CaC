# actividad-practica-CaC
# Código HTML y de Boostrap correspondiente para la creación de una página web


<!doctype html>
<html lang="en">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
    <title>Actividad práctica obligatoria</title>
</head>

<body>
    <!-- BARRA DE NAVEGACION -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light pe-4 ps-4">
        <!-- LOGO PRINCIPAL -->
        <a class="navbar-brand" href="#">Codo a codo</a>
        <button class="navbar-toggler" type="button">
            <span class="navbar-toggler-icon"></span>
        </button>
        <!-- BARRA Y BOTON DE BUSQUEDA -->
        <div class="collapse navbar-collapse">
            <ul class="navbar-nav me-auto">
                <li class="nav-item active">
                    <a class="nav-link" href="#">Inicio</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Link</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled" href="#" tabindex="-1">Desactivado</a>
                </li>
            </ul>
            <form class="d-flex">
                <input class="form-control me-2" type="search" placeholder="Buscar">
                <button class="btn btn-outline-success" type="submit">Buscar</button>
            </form>
        </div>
    </nav>
    <!-- TARJETAS -->
    <div class="container-fluid">
        <div class="row pe-1 ps-1">
            <!-- CARD 1 (HTML) -->
            <div class="card" style="width:33%">
                <img src="https://disenowebakus.net/imagenes/articulos/html5.jpg" class="card-img-top h-100">
                <div class="card-body">
                    <h5 class="card-title">Titulo 1</h5>
                    <p class="card-text">Contenido de Card</p>
                    <footer class="footer">
                        <small class="form-text text-muted">Ultima actualizacion 1</small>
                    </footer>
                </div>
            </div>
            <!-- CARD 2 (CSS) -->
            <div class="card" style="width:33%">
                <img src="https://armyyazilim.com/wp-content/uploads/2019/10/css.png" class="card-img-top h-100">
                <div class="card-body">
                    <h5 class="card-title">Titulo 2</h5>
                    <p class="card-text">Contenido de Card</p>
                    <footer class="footer">
                        <small class="form-text text-muted">Ultima actualizacion 1</small>
                    </footer>
                </div>
            </div>
            <!-- CARD 3 (BOOTSTRAP) -->
            <div class="card" style="width:33%">
                <img src="https://serv3.raiolanetworks.es/blog/wp-content/uploads/bootstrap-social-share.png"
                    class="card-img-top h-100">
                <div class="card-body">
                    <h5 class="card-title">Titulo 3</h5>
                    <p class="card-text">Contenido de Card</p>
                    <footer class="footer">
                        <small class="form-text text-muted">Ultima actualizacion 1</small>
                    </footer>
                </div>
            </div>
        </div>
    </div>
    <!-- FORMULARIO -->
    <form>
        <div class="form-group pe-1 ps-1">
            <label class="mb-2">Email</label>
            <input type="email" class="form-control">
            <small class="form-text text-muted">Nunca comparte su email.</small>
        </div>
        <br>
        <div class="form-group pe-1 ps-1">
            <label class="mb-2">Contraseña</label>
            <input type="password" class="form-control">
        </div>
        <br>
        <div class="form-group form-check ms-1 mb-1">
            <input type="checkbox" class="form-check-input">
            <label class="form-check-label">Verificar</label>
        </div>
        <br>
        <button class="btn btn-primary ms-1 mb-1" type="submit">Enviar</button>
    </form>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4"
        crossorigin="anonymous"></script>
</body>

</html>

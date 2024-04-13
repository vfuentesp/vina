<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Listado de Solicitudes</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="styles.css" rel="stylesheet">
<style>
     /* Estilos para el contenedor del logo */
        #logo-container {
          position: absolute;
          top: 10px;
          left: 10px;
          width: 100px; /* Ancho del logo */
          height: 100px; /* Altura del logo */
        }
        #logo-container img {
          width: 100%;
          height: 100%;
        }
</style>
</head>
<body>
    <!-- Contenedor del logo con enlace -->
<div id="logo-container">
    <a href="./intex.html">
      <img src="./img/logo.png" alt="Logo">
    </a>
  </div>

    <header>
        <h1>Listado de Solicitudes</h1>
    </header>
    <section>
        <!-- solicitud por pendientes -->
        <div class="card">
            <img src="./img/porhacer.jpg" class="card-img-top" alt="solicitudes pendientes">
            <div class="card-body">
                <h5 class="card-title">Solicitudes Pendientes</h5>
                <p class="card-text">Mantenga revisadas solicitudes</p>
                <a href="./p.solicitudes.html" class="btn btn-primary">Ver Solicitudes Pendientes</a>
            </div>
        </div>
        
        <!-- solicitudes listas -->
        <div class="card">
            <img src="./img/listo.jpg" class="card-img-top" alt="solicitudes listas">
            <div class="card-body">
                <h5 class="card-title">Solicitudes Listas</h5>
                <p class="card-text">Mantenga revisadas solicitudes</p>
                <a href="./l.solicitud.html" class="btn btn-primary">Ver Solicitudes Listas</a>
            </div>
        </div>
        
        <!-- solicitud por nuevas -->
        <div class="card">
            <img src="./img/listas.jpg" class="card-img-top" alt="nuevas solicitudes">
            <div class="card-body">
                <h5 class="card-title">Nuevas solicitudes</h5>
                <p class="card-text">Mantenga revisadas solicitudes</p>
                <a href="./s.nuevas.html" class="btn btn-primary">Ver nuevas solicitudes</a>
            </div>
        </div>
    </section>
    <footer>
        <a href="./intex.html" class="btn btn-volver">Volver al Inicio</a>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="../css/bootstrap.min.css">
    <title>Cartelera Laguna</title>
</head>
<body>
    <!--Navbar-->
    <nav class="navbar navbar-expand-lg navbar-light" style="background-color: red;">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"><img src=""></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll" aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarScroll">
            <ul class="navbar-nav me-auto my-2 my-lg-0 navbar-nav-scroll" style="--bs-scroll-height: 100px;">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarScrollingDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                  Cines
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarScrollingDropdown">
                  <li><a class="dropdown-item" href="#">Cinepolis</a></li>
                  <li><a class="dropdown-item" href="#">Cinemex</a></li>
                  <li><a class="dropdown-item" href="#">City Cinemas</a></li>
                </ul>
              </li>
            </ul>
            <form class="d-flex">
              <input class="form-control me-2" type="search" placeholder="Buscar Pelicula" aria-label="Search">
              <button class="btn btn-secondary" type="submit">Buscar</button>
            </form>
          </div>
        </div>
      </nav>
      <!--Carrusel-->
      <div style="background-color: salmon;">
        <div class="container" style="text-align: center; width: 60%; background-color: salmon;">
      <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-indicators">
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
          <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
        </div>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="../img/Black_Widow.jpg" class="d-block w-100">
            <div class="carousel-caption d-none d-md-block">
                <h5>Black Widow</h5>
                <p>8 de Julio</p>
                <p>Disponible en todos los cines</p>
              </div>
          </div>
          <div class="carousel-item">
            <img src="../img/Cruella.jpeg" class="d-block w-100">
            <div class="carousel-caption d-none d-md-block">
            <h5>Cruella</h5>
                <p>Ya Disponible</p>
                <p>Disponible en todos los cines</p>
            </div>
          </div>
          <div class="carousel-item">
            <img src="../img/Un_Lugar_En_Silencio_Parte_2.jpg" class="d-block w-100">
            <div class="carousel-caption d-none d-md-block">
            <h5>Un Lugar En Silencio: Parte 2</h5>
                <p>Ya Disponible</p>
                <p>Disponible en todos los cines</p>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
        </div>
        </div>
        <br>
      <!--Card-->
      <div class="container" style="text-align: center;">
      <div class="row">
          
          <div class="col-3 col-md-4 col-sm-12" style="text-align: center;">
            <div class="card" style="width: 14rem;">
                <img src="../img/La Purga 5 o 6.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">La purga por siempre</h5>
                  <p class="card-text">Disponible en todos los cines a nuestra disposicion</p>
                  <a href="#" class="btn btn-outline-danger">Ver Mas...</a>
                </div>
              </div>
              <br>
              
          </div>
          <div class="col-3 col-md-4 col-sm-12" style="text-align: center;">
            <div class="card" style="width: 14rem;">
                <img src="../img/La nueva de Spirit.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Spirit Indomable</h5>
                  <p class="card-text">Disponible en todos los cines a nuestra disposicion</p>
                  <a href="#" class="btn btn-outline-danger">Ver Mas...</a>
                </div>
              </div>
              <br>
          </div>
          <div class="col-3 col-md-4 col-sm-12" style="text-align: center;">
            <div class="card" style="width: 14rem;">
                <img src="../img/El Conjuro 3.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">El Conjuro 3</h5>
                  <p class="card-text">Disponible en todos los cines a nuestra disposicion</p>
                  <a href="#" class="btn btn-outline-danger">Ver Mas...</a>
                </div>
              </div>
          </div>
          <br>
      </div>
      
      <div class="row">
        <div class="col-3 col-md-4 col-sm-12" style="text-align: center;">
          <div class="card" style="width: 14rem;">
              <img src="../img/Rapidos y Furiosos.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Rapidos y Furiosos 9</h5>
                <p class="card-text">Disponible en todos los cines a nuestra disposicion</p>
                <a href="#" class="btn btn-outline-danger">Ver Mas...</a>
              </div>
            </div>
            <br>
            
        </div>
        <div class="col-3 col-md-4 col-sm-12" style="text-align: center;">
          <div class="card" style="width: 14rem;">
              <img src="../img/Duro de Cuidar 2.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Duro de Cuidar 2</h5>
                <p class="card-text">Disponible en todos los cines a nuestra disposicion</p>
                <a href="#" class="btn btn-outline-danger">Ver Mas...</a>
              </div>
            </div>
            <br>
        </div>
        <div class="col-3 col-md-4 col-sm-12" style="text-align: center;">
          <div class="card" style="width: 14rem;">
              <img src="../img/Cosas Imposibles.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <h5 class="card-title">Cosas Imposibles</h5>
                <p class="card-text">Disponible en todos los cines a nuestra disposicion</p>
                <a href="#" class="btn btn-outline-danger">Ver Mas...</a>
              </div>
            </div>
        </div>
        <br>
    </div>
      </div>
      Aaron Leonardo Martinez Perales 3B
</body>
<script src="../js/bootstrap.min.js"></script>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Navbar</title>
    <link rel="stylesheet" href="bootstrap-5.3.3-dist/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css">
    <style>
        .navbar {
            background: rgba(101, 134, 145, 0.452);
            box-shadow: 1px 4px 30px rgba(0, 0, 0, 0.192);
            }
        .logo {
            width: 80px;
            height: 45px;
            }
        .mi-link {
            color: white;
            font-size: 23px;
            padding: 2px;
            }
        .m-link {
            font-size: 15px;
            padding: 10px 0;
            }
        .nav-link {
            margin-right: 10px;
            }
        .mi-link:hover {
            color: wheat;
            }
        #hero {
            background: linear-gradient(#59abb157, #60abb157), url(../images/pexels-pixabay-417173.jpg);
            background-position: center;
            background-size: cover;
            }
        .btn {
            font-size: 18px;
            text-align: center;
            border-radius: 0;
            }
        .section-title {
            margin-bottom: 60px;
            }
        .section-title .line {
            width: 60px;
            height: 4px;
            background: #4e57d4;
            margin: 16px auto 24px auto;
            }
        .section-title p {
            max-width: 500px;
            margin-left: auto;
            margin-right: auto; 
            }
        .custom-Ab {
            align-items: center;
            }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg fixed-top">
        <div class="container-fluid">
          <img class="logo" src="../Opciones de ayuda de bootstrap/assets/images/pexels-scottwebb-430205.jpg" width="100" alt="...">
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link mi-link" aria-current="page" href="#Inicio">Inicio</a></li>
                    <li class="nav-item">
                        <a class="nav-link m-link text-white" aria-current="page" href="#Sobre">Sobre</a></li>
                    <li class="nav-item">
                        <a class="nav-link m-link text-white" aria-current="page" href="#Descubre más">Descubre más</a></li>
                    <li class="nav-item">
                        <a class="nav-link m-link text-white" aria-current="page" href="#Reseña">Reseña</a></li>
                    <li class="nav-item">
                        <a class="nav-link m-link text-white" aria-current="page" href="#Staff">Staff</a></li>
                    <li class="nav-item">
                        <a class="nav-link m-link text-white" aria-current="page" href="#Contacto">Contacto</a></li>
                </ul>
          </div>
        </div>
    </nav>
    <section id="hero" class="min-vh-100 d-flex align-items-center text-center">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <h5 class="text-uppercase fw-semibold display-1 mi-h5">Bienvenito to Navbar</h5>
                    <p class="mi-h5">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quas laborum aliquam quidem, maiores nam repudiandae natus aliquid cupiditate explicabo? Dolores ab quia esse consectetur labore repellat minima optio voluptatibus obcaecati.</p>
                    <div class="boton">
                        <a href="#" class="btn btn-info mi-btn px-5 ms-3">Comenzar</a>
                        <a href="#" class="btn btn-light mi-btn px-5 ms-3">Nuestro portal</a>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="about" class="section-padding">
        <div class="container-fluid">
            <div class="row">
                <div class="col-12">
                    <div class="section-title">
                        <h1 class="display-4 fw-semibold text-center mt-5">Sobre</h1>
                        <div class="line"></div>
                        <p class="text-center">Distinctio sint corrupti hic id officia harum suscipit repellat minus porro quos sapiente et, dolore, sit possimus. Quasi distinctio ea quod. Accusantium?</p>
                    <!-- Voy hacer que abajo de Sobre haya dos textos mas que den informacion de sobre para que puedan linkear sobre -->
                    </div>
                    <div class="d-flex justify-content: space-betwen; custom-Ab">
                        <div>
                            <h5 class="text-center mt-5">Acerca</h5>
                            <p class="text-center">et dolore, sit possimus. Quasi distinctio ea quod. Accusantium?</p>
                        </div>
                        <div>
                            <h5 class="text-center mt-5">Staff</h5>
                            <p class="text-center">et dolore, sit possimus. Quasi distinctio ea quod. Accusantium?</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row align-items-right">
                <div class="col-md-6">
                    <img src="assets/images/franco-figueroa-elkVRHxgmGE-unsplash.jpg" class="img-fluid rounded" alt="...">
                </div>
                <div class="col-md-6 d-flex flex-column">
                    <div class="mb-3 py-5">
                        <h2 id="Descubre más">We are awesome</h2>
                        <a type="button" class="btn btn-info px-2" href="#email">Email</a>
                        <p>amet consectetur adipisicing elit dolor sit amet consectetur adipisicing adipisicing elit dolor sit adipisicing elit dolor sit amet consectetur amet consectetur adipisicing  elit elit.</p>
                    </div>
                    <div class="mb-3 py-5">
                        <h2 id="Descubre más">We are awesome</h2>
                        <a type="button" class="btn btn-info px-2" href="#email">Email</a>
                        <p>amet consectetur adipisicing elit dolor sit amet consectetur adipisicing adipisicing elit dolor sit adipisicing elit dolor sit amet consectetur amet consectetur adipisicing  elit elit.</p>
                    </div>
                    <div class="mb-3 py-5">
                        <h2 id="Descubre más">We are awesome</h2>
                        <a type="button" class="btn btn-info px-2" href="#email">Email</a>
                        <p>amet consectetur adipisicing elit dolor sit amet consectetur adipisicing adipisicing elit dolor sit adipisicing elit dolor sit amet consectetur amet consectetur adipisicing  elit elit.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

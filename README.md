# Site-2.0
 
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="shortcut icon" href="./assets/favicon.png" type="image/x-icon">
  <title>Meu Banner</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous" />
  <link rel="stylesheet" href="styles.css">
</head>
 
<body>
  <!-- header/navbar -->
  <nav class="navbar navbar-expand-md navbar-light bg-black navbar-dark navbar-fixed">
    <div class="container-fluid">
      <a class="navbar-brand" href="./index.html">
       
        <h1 class="m-0"><img class="d-block" src="./assets//logo-meteora.png" alt="Logo da loja Meteora"></h1>
      </a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse flex-nowrap" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto gap-3 flex-nowrap mb-3 mb-md-0">
          <li class="nav-item">
            <a class="navbar-link" aria-current="page" href="./index.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="navbar-link" href="https://profrenatopereira.github.io/qmarka/">Moda QMarkª</a>
          </li>
          <li class="nav-item">
            <a class="navbar-link" href="https://profrenatopereira.github.io/pingpong2023/">Pong2023</a>
          </li>
          <li class="nav-item">
            <a class="navbar-link" href="https://profrenatopereira.github.io/tecnotuch2023/">NewTuch2023</a>
          </li>
          <li class="nav-item">
            <a class="navbar-link" href="https://profrenatopereira.github.io/heroinafull/">Super Maria Bros</a>
          </li>
          <li class="nav-item">
            <a class="navbar-link" href="#">Estelar</a>
          </li>
          <li class="nav-item">
            <a class="navbar-link" href="#">Brecho KiBarato</a>
          </li>
          <li class="nav-item">
            <a class="navbar-link" href="#">Gralhas & Araras</a>
          </li>
        </ul>
        <!--<form class="d-flex ms-2">
          <input id="search-field" class="form-control me-2 rounded-0" type="search" placeholder="Digite o Produto"
            aria-label="Pesquisar" />
          <button id="search-btn" class=" btn btn-outline-light rounded-0" type="submit">
            Buscar
          </button>
        </form>-->
      </div>
    </div>
  </nav>

  <!-- carousel. Para alterar o número de slides, altere o número na linha "carousel slide mb-4 carousel"-->
  <div id="carouselExampleCaptions" class="carousel slide mb-4 carousel" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active"
        aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1"
        aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2"
        aria-label="Slide 3"></button>
      <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3"
        aria-label="Slide 4"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img class="img-fluid d-md-none" src="./assets/Mobile/banner1-mobile.png"
          alt="Modelo vestindo blusa rosa fluorescente, em fundo lilás.">
        <img class="img-fluid d-none d-md-block d-xl-none" src="./assets/Tablet/banner1-tablet.png"
          alt="Modelo vestindo blusa rosa fluorescente, em fundo lilás.">
        <img class="img-fluid d-none d-xl-block w-100" src="./assets/Desktop/banner1-desktop.png"
          alt="Modelo vestindo blusa rosa fluorescente, em fundo lilás">
      </div>

      <div class="carousel-item">
        <img class="img-fluid d-md-none" src="./assets/Mobile/banner2-mobile.png"
          alt="Modelo vestindo roupa preta e usando óculos escuro, em um fundo rosa.">
        <img class="img-fluid d-none d-md-block d-xl-none" src="./assets/Tablet/banner2-tablet.png"
          alt="Modelo vestindo roupa preta e usando óculos escuro, em um fundo rosa.">
        <img class="img-fluid d-none d-xl-block" src="./assets/Desktop/banner2-desktop.png"
          alt="Modelo vestindo roupa preta e usando óculos escuro, em um fundo rosa.">
        <div class="carousel-caption">
          <h5 class="fs-1">APRENDER BRINCANDO</h5>
          <p class="fs-4 mb-3 mb-sm-5 mb-xl-4">CONSTRUCT - HTML - CSS.</p>
        </div>
      </div>

      <div class="carousel-item">
        <img class="img-fluid d-md-none" src="./assets/Mobile/banner3-mobile.png"
          alt="Modelo usando vestindo roupa branca e cinza e um chapéu, em um fundo laranja">
        <img class="img-fluid d-none d-md-block d-xl-none" src="./assets/Tablet/banner3-tablet.png"
          alt="Modelo usando vestindo roupa branca e cinza e um chapéu, em um fundo laranja">
        <img class="img-fluid d-none d-xl-block" src="./assets/Desktop/banner3-desktop.png"
          alt="Modelo usando vestindo roupa branca e cinza e um chapéu, em um fundo laranja">
        <div class="carousel-caption">
          <h5 class="fs-1">CONSTITUIR-SE HUMANO</h5>
          <p class="fs-4 mb-3 mb-sm-5 mb-xl-4">BEM-ESTAR SOCIAL & MANUTENÇÃO AMBIENTAL!</p>
        </div>
      </div>

      <div class="carousel-item">
        <img class="img-fluid d-md-none" src="./assets/Mobile/banner4-mobile.png"
          alt="Modelo usando vestindo roupa branca e cinza e um chapéu, em um fundo laranja">
        <img class="img-fluid d-none d-md-block d-xl-none" src="./assets/Tablet/banner4-tablet.png"
          alt="Modelo usando vestindo roupa branca e cinza e um chapéu, em um fundo laranja">
        <img class="img-fluid d-none d-xl-block" src="./assets/Desktop/banner4-desktop.png"
          alt="Modelo usando vestindo roupa branca e cinza e um chapéu, em um fundo laranja">
        <div class="carousel-caption">
          <h5 class="fs-1">CONSTITUIR-SE HUMANO</h5>
          <p class="fs-4 mb-3 mb-sm-5 mb-xl-4">OPORTUNIZAR-SE ÀS DEMANDAS LOCAIS E ÀS GLOBAIS!</p>
        </div>
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Anterior</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Próximo</span>
    </button>
  </div>

  
  <!-- footer -->
  <footer class="text-justify bg-black text-light">
    <p class="p-3 m-0">CRÉDITOS: Equipe Alura/SEED-PR. Autoras e autores de códigos, imagens, sons e demais conhecimentos utilzados e multiplicados neste projeto aberto. Sobretudo, toda gratidão por gentis críticas e generosa motivação creditadas por estimadas e valorosos estudantes.
      <div class="text-center copyright">© Copyright Física Renato Pereira ®ψΣ - 2023</div></p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
    crossorigin="anonymous"></script>
  <script src="./src/scripts/conectar.js" type="module"></script>
  <script src="./src/scripts/writeProducts.js" type="module"></script>
  <script src="./src/scripts/modal.js" type="module"></script>
  <script src="./src/scripts/filter.js" type="module"></script>
  <script src="./src/scripts/search.js" type="module"></script>
  <script src="./src/scripts/emailForm.js" type="module"></script>
</body>
</html>

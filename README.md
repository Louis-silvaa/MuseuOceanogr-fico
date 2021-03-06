# MuseuOceanogr-fico

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4"
    crossorigin="anonymous"></script>

  <link rel="stylesheet" href="style.css">
  <title>Museu Oceanográfico Univali</title>
</head>

<body>
  <nav id="navbar" class="navbar navbar-expand-lg navbar-dark bg-primary">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Museu</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Ingressos</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#história">Sobre</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#Alas">Exposição</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown"
              aria-expanded="false">
              Dropdown
            </a>
            <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
              <li><a class="dropdown-item" href="#">Planeje sua Visita</a></li>
              <li><a class="dropdown-item" href="#">Como chegar</a></li>
              <li>
                <hr class="dropdown-divider">
              </li>
              <li><a class="dropdown-item" href="#">Café</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Exposição</a>
          </li>

        </ul>
        <form class="d-flex">
          <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
          <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
      </div>
    </div>
  </nav>
  <!--CAROSEL-->
  <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
    <div class="carousel-indicators">
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"
        aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
        aria-label="Slide 2"></button>
      <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
        aria-label="Slide 3"></button>
    </div>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img src="1 nemo.jpg" class="d-block w-100" alt="Imagem do peixe nemo em um aquário">
      </div>
      <div class="carousel-item">
        <img src="img2.jpg" class="d-block w-100" alt="Imagem de uma raia">
      </div>
      <div class="carousel-item">
        <img src="img3.jpg" class="d-block w-100" alt="Outra imagem de um peixe">
      </div>
    </div>
    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
      data-bs-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Anterior</span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
      data-bs-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Próximo</span>
    </button>
  </div>

  <!--história-->
  <div class="container mt-5 mb-5" id="história">
    <div class="card text-center">
      <div class="card-header">
        Sobre o Museu
      </div>
      <div class="card-body">
        <h5 class="card-title">Museu Oceanográfico Univali</h5>
        <p class="card-text">O Museu Oceanográfico Univali (MOVI) é o maior museu oceanográfico das Américas e o
          terceiro maior do mundo nesta temática.

          Foi fundado em 1987, pelo seu atual curador geral, Prof. Jules M. R. Soto. Está localizado no campus da
          Universidade do Vale do Itajaí em Balneário Piçarras, Santa Catarina, Brasil.</p>
        <p>
          O acervo do Museu Oceanográfico Univali tem mais de 200.00 peças e a exposição apresenta pouco mais de 1%
          delas, proporcionando ao visitante um panorama da biodiversidade marinha brasileira. Além disso, animais vivos
          em aquários acrescentam vida e movimento ao circuito expositivo.

          O MOVI é filiado ao Conselho Internacional de Museus (ICOM) junto aos museus de história natural (NATHIST),
          desde 1994, e seu sistema de curadoria adota os critérios éticos e técnicos estipulados por este conselho,
          como o Código de Deontologia do ICOM (2002). É cadastrado junto ao Instituto Brasileiro de Museus (IBRAM),
          órgão federal que regula e orienta as ações museais no país e é considerado “Coleção de Excelência” pelo CNPq
          e “Instituição de Referência” pela CAPES, indicado para trabalhos de pós-graduação em nível de pós-doutorado.
        </p>
        <a href="#" class="btn btn-primary">Go somewhere</a>
      </div>
      <div class="card-footer text-muted">
        
      </div>
    </div>
  </div>
  <!--mais fotos-->
  <div class="card-group" id="Alas">
    <div class="card">
      <img src="Ala1.jpg" class="card-img-top" alt="Imagem de um chupa cabra">
      <div class="card-body">
        <h5 class="card-title">Ala 1: Surgimento da vida
          e história do homem com o mar</h5>
        <p class="card-text">Fala sobre desde o ínicio dos homes sapiens até os dias atuais com a sua evolução, com a
          terra e mar.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">Last updated 3 mins ago</small>
      </div>
    </div>
    <div class="card">
      <img src="ala2.jpg" class="card-img-top" alt="Imagem de umas conchas">
      <div class="card-body">
        <h5 class="card-title">Ala 2: Invertebrados</h5>
        <p class="card-text">Conta a história dos corais e das conchas.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">Last updated 3 mins ago</small>
      </div>
    </div>
    <div class="card">
      <img src="ALA3.jpg" class="card-img-top" alt="Peixes agnatas e cartilaginozos">
      <div class="card-body">
        <h5 class="card-title">Ala 3: Peixes agnatas e cartilaginozos</h5>
        <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content.
          This card has even longer content than the first to show that equal height action.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">Last updated 3 mins ago</small>
      </div>
    </div>
    <div class="card">
      <img src="Ala4.jpg" class="card-img-top" alt="Peixes osseos">
      <div class="card-body">
        <h5 class="card-title">Ala 4: Peixes Ósseos</h5>
        <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content.
          This card has even longer content than the first to show that equal height action.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">Last updated 3 mins ago</small>
      </div>
    </div>
    <!--Alas em baixo-->
    <div class="card-group" id="Alas">
      <div class="card">
        <img src="Ala1.jpg" class="card-img-top" alt="Imagem de um chupa cabra">
        <div class="card-body">
          <h5 class="card-title">Ala 1: Surgimento da vida
            e história do homem com o mar</h5>
          <p class="card-text">Fala sobre desde o ínicio dos homes sapiens até os dias atuais com a sua evolução, com a
            terra e mar.</p>
        </div>
        <div class="card-footer">
          <small class="text-muted">Last updated 3 mins ago</small>
        </div>
      </div>
      <div class="card">
        <img src="ala2.jpg" class="card-img-top" alt="Imagem de umas conchas">
        <div class="card-body">
          <h5 class="card-title">Ala 2: Invertebrados</h5>
          <p class="card-text">Conta a história dos corais e das conchas.</p>
        </div>
        <div class="card-footer">
          <small class="text-muted">Last updated 3 mins ago</small>
        </div>
      </div>
      <div class="card">
        <img src="ALA3.jpg" class="card-img-top" alt="Peixes agnatas e cartilaginozos">
        <div class="card-body">
          <h5 class="card-title">Ala 3: Peixes agnatas e cartilaginozos</h5>
          <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content.
            This card has even longer content than the first to show that equal height action.</p>
        </div>
        <div class="card-footer">
          <small class="text-muted">Last updated 3 mins ago</small>
        </div>
      </div>
      <div class="card">
        <img src="Ala4.jpg" class="card-img-top" alt="Peixes osseos">
        <div class="card-body">
          <h5 class="card-title">Ala 4: Peixes Ósseos</h5>
          <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content.
            This card has even longer content than the first to show that equal height action.</p>
        </div>
        <div class="card-footer">
          <small class="text-muted">Last updated 3 mins ago</small>
        </div>
      </div>

  </div>

</body>

</html>

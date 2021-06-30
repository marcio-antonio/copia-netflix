<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="main.css">
    <!--SEMPRE ACESSE O CONSOLE NO INSPECIONAR DO GOOGLE PARA AVERIGUAR ERROS!!-->

    <!--responsividade-->
    <link rel="stylesheet" href="responsive.css">
    
    <!--owl css-->
    <link rel="stylesheet" href="owl.carousel.min.css">
    <link rel="stylesheet" href="owl.theme.default.min.css">
    
    <title>NETFLIX CLONE</title>
  </head>
  <body>
    <header>
      <div class="container">
        <h2 class="logo">NETFLIX</h2>
        <nav>
          <a href="#">Início</a>
          <a href="#">Séries</a>
          <a href="#">Filmes</a>
          <a href="#">Documentários</a>
        </nav>
      </div>
    </header>

    <main>
      <div class="filme-principal">
        <div class="container">
          <h3 class="titulo">HOUSE OF CARDS</h3>
          <p class="descricao">Sinopse do House of Cards.</p>
          <div class="botoes">
            <button role="button" class="botao">
              <i class="fas fa-play"></i>
              ASSISTIR AGORA
            </button>
            <button role="button" class="botao">
              <i class="fas fa-info-circle"></i>
              MAIS INFORMAÇÕES
            </button>
          </div>
        </div>
      </div>
    </main>
    
    <div class="carrossel-filmes">
      <div class="owl-carousel owl-theme">
        <div class="item">
          <img class="box-filme" src="mini1.jpg" alt="" srcset="">
        </div>
        <div class="item">
          <img class="box-filme" src="mini2.jpg" alt="" srcset="">
        </div>
        <div class="item">
          <img class="box-filme" src="mini3.jpg" alt="" srcset="">
        </div>
        <div class="item">
          <img class="box-filme" src="mini4.jpg" alt="" srcset="">
        </div>
        <div class="item">
          <img class="box-filme" src="mini5.jpg" alt="" srcset="">
        </div>
        <div class="item">
          <img class="box-filme" src="mini6.jpg" alt="" srcset="">
        </div>
        <div class="item">
          <img class="box-filme" src="mini7.jpg" alt="" srcset="">
        </div>
        <div class="item">
          <img class="box-filme" src="mini8.jpg" alt="" srcset="">
        </div>
        <div class="item">
          <img class="box-filme" src="mini9.jpg" alt="" srcset="">
        </div>
        <div class="item">
          <img class="box-filme" src="mini10.jpg" alt="" srcset="">
        </div>
      </div>
    </div>
    
    <!--deixar o js por último para não dar problema de carregamento -->
    <script src="https://kit.fontawesome.com/4ba793eaee.js" crossorigin="anonymous"></script>
    <script src="jquery.min.js"></script>
    <script src="owl.carousel.min.js"></script>
    <script src="setup.js"></script>

  </body>
</html>
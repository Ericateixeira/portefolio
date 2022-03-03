# portefolio
<!DOCTYPE html>
<html lang="pt">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"><!--icones: https://fontawesome.com/v4.7/-->
  <link rel="stylesheet" href="style.css">
  <link rel="icon" href="img/favicon.svg" sizes="any" type="image/svg+xml">
  <title>O meu website</title>
  <meta name="description" content="Ao escrever esta meta tag, usa entre 140 e 160 caracteres para que o Google possa exibir toda a descrição deste website. Não te esqueças de incluir uma palavra-chave!">
  <meta name="keywords" content="HTML, CSS: isto são as palavras-chave do website">
  <meta name="author" content="Nome Autor">
</head>

<body>
  <!-- Header -->
  <section id="header">
    <div class="header container">
      <div class="nav-bar">
        <div class="brand">
          <a href="#hero">
            <h1><span>N</span>ome <span>A</span>utor</h1>
          </a>
        </div>
        <div class="nav-list">
          <div class="hamburger">
            <div class="bar"></div>
          </div>
          <ul>
            <li><a href="#hero" data-after="Home">Início</a></li>
            <li><a href="#services" data-after="Service">Serviços</a></li>
            <li><a href="#projects" data-after="Projects">Projetos</a></li>
            <li><a href="#about" data-after="About">Acerca</a></li>
            <li><a href="#contact" data-after="Contact">Contactos</a></li>
          </ul>
        </div>
      </div>
    </div>
  </section>
  <!-- End Header -->


  <!-- Hero Section  -->
  <section id="hero">
    <div class="hero container">
      <div>
        <h1>Olá, <span></span></h1>
        <h1>Eu sou o <span></span></h1>
        <h1>Nome <span></span></h1>
        <a href="#projects" type="button" class="cta">Portfolio</a>
      </div>
    </div>
  </section>
  <!-- End Hero Section  -->

  <!-- Service Section -->
  <section id="services">
    <div class="services container">
      <div class="service-top">
        <h1 class="section-title">Serv<span>i</span>ços</h1>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ipsum deleniti maiores pariatur assumenda quas
          magni et, doloribus quod voluptate quasi molestiae magnam officiis dolorum, dolor provident atque molestias
          voluptatum explicabo!</p>
      </div>
      <div class="service-bottom">
        <div class="service-item">
          <div class="icon"><i class="fa fa-eye" style="font-size:60px;color:CornflowerBlue;"></i></div>
          <h2>Web Design</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis debitis rerum, magni voluptatem sed
            architecto placeat beatae tenetur officia quod</p>
        </div>
        <div class="service-item">
          <div class="icon"><i class="fa fa-code"style="font-size:60px;color:CornflowerBlue;"></i></div>
          <h2>Programação</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis debitis rerum, magni voluptatem sed
            architecto placeat beatae tenetur officia quod</p>
        </div>
        <div class="service-item">
          <div class="icon"><i class="fa fa-microphone"style="font-size:60px;color:CornflowerBlue;"></i></div>
          <h2>Comunicação</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis debitis rerum, magni voluptatem sed
            architecto placeat beatae tenetur officia quod</p>
        </div>
        <div class="service-item">
          <div class="icon"><i class="fa fa-play" style="font-size:60px;color:CornflowerBlue;"></i></div>
          <h2>Media</h2>
          <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis debitis rerum, magni voluptatem sed
            architecto placeat beatae tenetur officia quod</p>
        </div>
      </div>
    </div>
  </section>
  <!-- End Service Section -->

  <!-- Projects Section -->
  <section id="projects">
    <div class="projects container">
      <div class="projects-header">
        <h1 class="section-title">Projetos <span>Recentes</span></h1>
      </div>
      <div class="all-projects">
        <div class="project-item">
          <div class="project-info">
            <h1>Projeto 1</h1>
            <h2>Blá blá blá</h2>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ad, iusto cupiditate voluptatum impedit unde
              rem ipsa distinctio illum quae mollitia ut, accusantium eius odio ducimus illo neque atque libero non sunt
              harum? Ipsum repellat animi, fugit architecto voluptatum odit et!</p>
          </div>
          <div class="project-img">
            <img src="./img/img-1.png" alt="img">
          </div>
        </div>
        <div class="project-item">
          <div class="project-info">
            <h1>Projeto 2</h1>
            <h2>Blá blá blá</h2>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ad, iusto cupiditate voluptatum impedit unde
              rem ipsa distinctio illum quae mollitia ut, accusantium eius odio ducimus illo neque atque libero non sunt
              harum? Ipsum repellat animi, fugit architecto voluptatum odit et!</p>
          </div>
          <div class="project-img">
            <img src="./img/img-1.png" alt="img">
          </div>
        </div>
        <div class="project-item">
          <div class="project-info">
            <h1>Projeto 3</h1>
            <h2>Blá blá blá</h2>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ad, iusto cupiditate voluptatum impedit unde
              rem ipsa distinctio illum quae mollitia ut, accusantium eius odio ducimus illo neque atque libero non sunt
              harum? Ipsum repellat animi, fugit architecto voluptatum odit et!</p>
          </div>
          <div class="project-img">
            <img src="./img/img-1.png" alt="img">
          </div>
        </div>
        <div class="project-item">
          <div class="project-info">
            <h1>Projeto 4</h1>
            <h2>Blá blá blá</h2>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ad, iusto cupiditate voluptatum impedit unde
              rem ipsa distinctio illum quae mollitia ut, accusantium eius odio ducimus illo neque atque libero non sunt
              harum? Ipsum repellat animi, fugit architecto voluptatum odit et!</p>
          </div>
          <div class="project-img">
            <img src="./img/img-1.png" alt="img">
          </div>
        </div>
        
        </div>
      </div>
    </div>
  </section>
  <!-- End Projects Section -->

  <!-- About Section -->
  <section id="about">
    <div class="about container">
      <div class="col-left">
        <div class="about-img">
          <img src="./img/img-2.png" alt="img">
        </div>
      </div>
      <div class="col-right">
        <h1 class="section-title">Quem <span>sou</span></h1>
        <h2>Blá blá blá</h2>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Asperiores, velit alias eius non illum beatae atque
          repellat ratione qui veritatis repudiandae adipisci maiores. At inventore necessitatibus deserunt
          exercitationem cumque earum omnis ipsum rem accusantium quis, quas quia, accusamus provident suscipit magni!
          Expedita sint ad dolore, commodi labore nihil velit earum ducimus nulla quae nostrum fugit aut, deserunt
          reprehenderit libero enim!</p>
        <a href="#" class="cta">Descarregar CV</a>
      </div>
    </div>
  </section>
  <!-- End About Section -->

  <!-- Contact Section -->
  <section id="contact">
    <div class="contact container">
      <div>
        <h1 class="section-title">Ligue <span>Já</span></h1>
      </div>
      <div class="contact-items">
        <div class="contact-item">
          <div class="icon"><i class="fa fa-phone" style="font-size:60px;color:CornflowerBlue;"></i></div>
          <div class="contact-info">
            <h1>Phone</h1>
            <h2>+351 234 123 1234</h2>
            <h2>+351 234 123 1234</h2>
          </div>
        </div>
        <div class="contact-item">
          <div class="icon"><i class="fa fa-envelope" style="font-size:60px;color:CornflowerBlue;"></i></div>
          <div class="contact-info">
            <h1>E-mail</h1>
            <h2>info@gmail.com</h2>
            <h2>abcd@gmail.com</h2>
          </div>
        </div>
        <div class="contact-item">
          <div class="icon"><i class="fa fa-map-pin" style="font-size:60px;color:CornflowerBlue;"></i></div>
          <div class="contact-info">
            <h1>Address</h1>
            <h2>Rua, Algures, Portugal</h2>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- End Contact Section -->

  <!-- Footer -->
  <section id="footer">
    <div class="footer container">
      <div class="brand">
        <h1><span>N</span>ome <span>A</span>utor</h1>
      </div>
      <h2>Sempre aqui para si!</h2>
      <div class="social-icon">
        <div class="social-item">
          <a href="#"><i class="fa fa-facebook-square" style="font-size:40px;color:CornflowerBlue;"></i></a>
        </div>
        <div class="social-item">
          <a href="#"><i class="fa fa-instagram" style="font-size:40px;color:CornflowerBlue;"></i></a>
        </div>
        <div class="social-item">
          <a href="#"><i class="fa fa-twitter-square" style="font-size:40px;color:CornflowerBlue;"></i></a>
        </div>
        <div class="social-item">
          <a href="#"><i class="fa fa-linkedin-square" style="font-size:40px;color:CornflowerBlue;"></i></a>
        </div>
      </div>
      <p>Copyright © 2021 Autor. Todos os direitos reservados.</p>
    </div>
  </section>
  <!-- End Footer -->
  <script src="./app.js"></script>
</body>

</html>

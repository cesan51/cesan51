<html lang="en">
 

<!--Enlace Bootstrap-->
<head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
     
    <!--Enlace Animaciones -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    
    <!-- jQuery -->
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>

    
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width, initial-scale=1">
      <meta name="description" content="Desarrollador de Software. Pagina Web Informativa">
      <meta name="author" content="CESAR ANTONIO GÓMEZ MONTAÑO">
      <meta name="generator" content="CESAN">
      
     
  
      <!-- Favicons -->
      <link rel="icon " href="/assets/github.png">
      <link rel="icon" href="assets/cesan_ico.png" type="image/x-icon">
  
  </head>
  
  <!-- Hoja de estilos -->
  <style>

     @import url('https://fonts.googleapis.com/css2?family=Raleway:wght@700&display=swap');
    
    .container-fluid li a:hover{
            background-color: whitesmoke;
            border: aqua;
            color: #0056b3 ;

        }
        .image_principal {
      position: relative;
      text-align: center;
      margin-top: 2%;
    }

    .image_principal img {
      width: 100%;
      height: 100vh; /* Ocupa toda la pantalla */
      object-fit: cover;
      display: block;
    }

    .image_overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.6); /* Overlay semi-transparente */
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      color: white;

      text-align: center;
      padding: 20px;
    }

    .image_texto {
      animation: fadeIn 2s;
      margin-bottom: 20px;
      font-size: 3rem;
      font-weight: 700;
      
      color: white;
      
      
    }

    .btn-cta {
      background-color: #007bff;
      border: none;
      color: white;
      padding: 15px 30px;
      font-size: 1.2rem;
      cursor: pointer;
      transition: background-color 0.3s ease;
      text-decoration: none;
      border-radius: 5px;
    }

    .btn-cta:hover {
      background-color: #0056b3;
      color: white;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

        .sobre h1{
            font-size: 1.6rem;
            color: #1A73E8;
            
        }
        .sobre h2{
            font-size: 1.4rem;
        }

        .sobre p{
            font-size: 1.2rem;
        }

        .container-fluid button{
            background-color: rgba(240, 248, 255, 0.479);
            border:rgba(240, 248, 255, 0.479) ;
        }
        .sobre{
            margin-left: 7%;
            margin-right: 7%;
            margin-top: 3%;
        }
        .btn:hover{
            background-color: #135CBF;
            border: #135CBF;
            
        }
        .proyects{
            margin-left: 5%;
            margin-right: 5%;
        }
        .col-lg-4 img{
            transition: 0.2s;
            object-fit: cover;
        }
        .col-lg-4 img:hover{
            transform: scale(1.2);
        }
        .col-lg-4{
            text-align: center;
        }
        .col-lg-4 img{
            transition: 0.2s;
            object-fit: cover;
        }
        .col-lg-4 img:hover{
            transform: scale(1.2);
        }
        .col-lg-4 img{
            transition: 0.2s;
            object-fit: cover;
        }
        .col-lg-4 img:hover{
            transform: scale(1.2);
        }
        .container{
            background-color: whitesmoke;
            margin: 2% auto;
            border-radius: 40px;
        }
        h2{
            font-size: 1rem;
        }
        .col-lg-4 img{
            transition: 0.2s;
            object-fit: cover;
        }
        .col-lg-4 img:hover{
            transform: scale(1.2);
        }
        .dark {
            background-color: #000000 !important; /* Fuerza el color de fondo a negro */
        }
        .py-5{
            font-size: 0.8rem;
            background-color: black;
       }
       .float-end h2 {
            background-color: white !important; /* Fuerza el color de fondo a negro */
        }
       .navbar-brand{
        color: white;
       }
       .nav-item .nav-link:hover {
            color: black; /* Cambia el color del texto a negro al hacer hover */
        }

       .btn{
        background-color: #1A73E8;
        border: #1A73E8;
       }
       b{
        font-size: 30px;  
       }
       .nav-item .nav-link {
        color: black;
       }
       .float-end {
        color: white;
       }
       h2 a{
            color: white;
        }
        .container-fluid {
            background-color: white;
        }





    .navbar {
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    .nav-item .navbar-brand img {
      height: 40px; /* Ajusta la altura del logo según tus necesidades */
    }
    .nav-item .nav-link {
      font-size: 1.1rem;
      padding: 0.5rem 1rem;
      transition: color 0.3s ease;
    }
    .nav-item .nav-link:hover {
      color: #007bff;
    }
    .nav-item .navbar-toggler {
      border: none;
    }
    .nav-item .navbar-toggler:focus {
      outline: none;
      box-shadow: none;
    }
    .nav-item .nav-item.dropdown:hover .dropdown-menu {
      display: block;
    }
    .container h2 {
      font-weight: bold;
    }
    


        

  </style>
  
  
  <body><header>
     <!--Cabeza Navbar-->
     <nav class="navbar navbar-expand-md bg-white fixed-top">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="assets/cesan_ico.webp" alt="Icono">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarCollapse">
          <ul class="navbar-nav me-auto mb-2 mb-md-0">
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#sobre_mi"><i class="fas fa-user"></i> Sobre mí</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#skills"><i class="fas fa-cogs"></i> Skills</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#proyectos"><i class="fas fa-project-diagram"></i> Proyectos</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#certificados"><i class="fas fa-certificate"></i> Certificados</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" aria-current="page" href="#contactanos"><i class="fas fa-envelope"></i> Contáctame</a>
            </li>
            <li class="nav-item">
              
              <script src="https://unpkg.com/@dotlottie/player-component@latest/dist/dotlottie-player.mjs" type="module"></script> 

              <dotlottie-player src="https://lottie.host/73c2d490-e28b-4912-b87c-947d720e9968/DWsEB0OCBM.json" background="transparent" speed="1" style="width: 50px; height: 50px; margin-left: 1200%;" loop autoplay></dotlottie-player>
             
           </li>
          </ul>
        </div>
      </div>
    </nav>
   

  </header>


     <!-- Script js-->
     <script src="layout.js"></script>



     <script>
      $(document).ready(function() {
        $('.navbar-collapse a').click(function(){
          $(".navbar-collapse").collapse('hide');
        });
      });
    </script>



    <!--Imagen Principal de desarrollo -->
    <div class="image_principal">
      <img src="assets/source.jpg" alt="Fondo programing">
      <div class="image_overlay">
        <p class="image_texto">Desarrollo Profesional y Creativo</p>
        <a href="#proyectos" class="btn-cta">Ver Proyectos</a>
      </div>
    </div>
    <!--/.Imagen Principal de desarrollo-->


        <!--Descripción de habilidades -->
        <a id="sobre_mi"></a>
         <!--Texto y contenido -->
      <div class="container1"><br>
        <div class="sobre">
            
  
          <a id="sobre_mi"></a>
          
          <div class="row featurette">
            <div class="center">
              <h1 class="featurette-heading fw-normal lh-1">Te cuento un poco sobre mí.</h1><br>
              <h2 class="featurette-heading fw-normal lh-2">Soy Antonio Gómez, Desarrollador Web e Ingeniero de Sistemas.</h2>
              <p class="lead">Soy un desarrollador web independiente. Actualmente, formo parte del equipo de desarrollo y soporte de Infinity Software Innovation SAS, una empresa en la que aplico mis habilidades y conocimientos para llevar a cabo diversos proyectos tecnológicos.<br><br>

                Además de mi trabajo con Infinity Software Innovation, también creo sitios y páginas web para clientes propios, ofreciendo soluciones personalizadas que se adaptan a las necesidades específicas de cada proyecto.<br><br>
                
                Poseo habilidades en manejo de la información y archivística, y destaco por mis competencias sociales y éticas, que me permiten mantener una excelente comunicación con mis compañeros de trabajo y clientes. Esto facilita la ejecución eficiente de los procesos necesarios para el éxito de los proyectos.<br><br>
                
                Gracias a mi formación como ingeniero de sistemas y a las habilidades adquiridas en servicio al cliente, tengo una gran capacidad lógica para la solución de problemas y para ofrecer un servicio de alta calidad..<br><br>
                 
                 
                 

                 
            </p>
              
            
          
              </div>
              <p><a class="btn btn-secondary " href="https://drive.google.com/file/d/1jj0Trj7PVxd9ph-DllCpAkYaZRj2WRkc/view?usp=drive_link" target="_blank">Currículum </a></p>
         </div>
          </div>
          
      </div><!--/.Descripción de habilidades -->


      
      
      <!--Container Skills -->
       <a id="skills"></a><br>
       <div class="container">
           <!-- row skills -->
          <hr class="featurette-divider">
          <h3> Habilidades</h3><br><br>
          <div class="row">

           <div class="col-lg-4">
              <img  src="assets/php.png" class="bd-placeholder-img rounded-circle" width="110" height="110" alt="">
     
             <h2 class="fw-normal">PHP</h2>
             <p><a class="btn btn-secondary" href="https://www.php.net/manual/es/intro-whatis.php" target="_blank">Conoce más »</a></p>
           </div><!-- /php -->


            <div class="col-lg-4">
               <img  src="assets/python_pro.png" class="bd-placeholder-img rounded-circle" width="110" height="110" alt="">
      
              <h2 class="fw-normal">Python</h2>
              <p><a class="btn btn-secondary" href="https://www.python.org/" target="_blank">Conoce más »</a></p>
            </div><!-- /python -->

        

            <div class="col-lg-4">
              <img src="assets/html2.png" class="bd-placeholder-img rounded-circle" width="110" height="110" margin-right="15px" alt="">
              
              <h2 class="fw-normal">HTML</h2>
              
              <p><a class="btn btn-secondary" href="https://www.w3.org/TR/html/" target="_blank">Conoce más »</a></p>
            </div><!-- /HTML -->


            
            <div class="col-lg-4">
                <img src="assets/css1.png" class="bd-placeholder-img rounded-circle" width="110" height="110" margin-right="15px" alt="">
                
                <h2 class="fw-normal">CSS</h2>
                
                <p><a class="btn btn-secondary" href="https://www.w3.org/Style/CSS/" target="_blank">Conoce más »</a></p>
            </div><!-- /CSS -->


            <div class="col-lg-4">
                <img src="assets/angular.jpg" class="bd-placeholder-img rounded-circle" width="110" height="110" margin-right="15px" alt="">
                
                <h2 class="fw-normal">Angular</h2>
                
                <p><a class="btn btn-secondary" href="https://angular.io/docs" target="_blank">Conoce más »</a></p>
              </div><!-- /Angular -->
  
  
              
              <div class="col-lg-4">
                  <img src="assets/bootstrap.png" class="bd-placeholder-img rounded-circle" width="110" height="110" margin-right="15px" alt="">
                  
                  <h2 class="fw-normal">Bootstrap</h2>
                  <p><a class="btn btn-secondary" href="https://getbootstrap.com/docs/" target="_blank">Conoce más »</a></p>
                </div><!-- /Bootsrap -->


                <div class="col-lg-4">
                    <img src="assets/flask_pro.png"  class="bd-placeholder-img rounded-circle" width="110" height="110" margin-right="15px" alt="">
                    
                    <h2 class="fw-normal">Flask</h2>
                    <p><a class="btn btn-secondary" href="https://flask.palletsprojects.com/en/2.1.x/" target="_blank">Conoce más »</a></p>
                </div><!-- /Flask -->


                <div class="col-lg-4">
                  <img src="assets/scriptcase.png"  class="bd-placeholder-img rounded-circle" width="110" height="110" margin-right="15px" alt="">
                  
                  <h2 class="fw-normal">Scriptcase</h2>
                  <p><a class="btn btn-secondary" href="https://www.scriptcase.net/es/" target="_blank">Conoce más »</a></p>
               </div><!-- /Scriptcase -->


               <div class="col-lg-4">
                <img src="assets/computer.png"  class="bd-placeholder-img rounded-circle" width="110" height="110" margin-right="15px" alt="">
                
                <h2 class="fw-normal">Windows</h2>
                <p><a class="btn btn-secondary" href="https://www.microsoft.com/es-es/windows?r=1" target="_blank">Conoce más »</a></p>
               </div><!-- /Windows -->


               <div class="col-lg-4">
                <img src="assets/linux.png"  class="bd-placeholder-img rounded-circle" width="110" height="110" margin-right="15px" alt="">
                
                <h2 class="fw-normal">Linux</h2>
                <p><a class="btn btn-secondary" href="https://www.linux.org/" target="_blank">Conoce más »</a></p>
               </div><!-- /Linux -->


             
          </div><!-- /.row -->
      
        </div><!-- /.Container Skills -->




     <!--Container Proyectos -->
     <a id="proyectos"></a><br>
  <div class="container">
    <div class="proyects">
        <hr class="featurette-divider">
        <h3> Proyectos</h3><br><br>
        <div class="row">

          <div class="col-lg-4">
            <img  src="assets/Infinity.jpg" class="bd-placeholder-img rounded-circle" width="250" height="160" alt="">
   
           <h2 class="fw-normal"><br>INFINITY SOFTWARE INNOVATION</h2>
           <p> Soporte y Desarrollo.<br>
            Prestacion de servicios como Ingeniero de Soporte y Desarrollo. </p>
           <p><a class="btn btn-secondary" href="https://infinitysof.com/" target="_blank">Conoce más »</a></p>
         </div><!-- / .Arsoft --><br>
          

          
          <div class="col-lg-4">
            <img  src="assets/arsoft.png" class="bd-placeholder-img rounded-circle " width="250" height="160" alt="">
   
           <h2 class="fw-normal"><br>ARSOFT</h2>
           <p> Régimen Subsisdiado, Soporte y Actualizaciones.<br>
            Sistema de información diseñado para la administración de recursos financieros en el régimen subsidiado. </p>
           <p><a class="btn btn-secondary" href="https://infinitysof.com/" target="_blank">Conoce más »</a></p>
         </div><!-- / .Arsoft --><br>


          <div class="col-lg-4">
             <img  src="assets/emprender.jpg" class="bd-placeholder-img rounded-circle" width="250" height="160" alt="">
    
            <h2 class="fw-normal"><br>Proyectos IEELS</h2>
            <p>Proyectos de emprendimiento I. E.<br>
               Eleazar Libreros Salamanca. </p>
            <p><a class="btn btn-secondary" href="https://emprendimientoels.surge.sh/" target="_blank">Conoce más »</a></p>
          </div><!-- / .Emprendimientoels --><br>



          <div class="col-lg-4">
             <img  src="assets/perro.jpg" class="bd-placeholder-img rounded-circle " width="250" height="160" alt="">
    
            <h2 class="fw-normal"><br>Clasificador de Perros y Gatos</h2>
            <p>Red neuronal convulucional Python<br>
               Capaz de clasificar mediante video en vivo. </p>
            <p><a class="btn btn-secondary" href="https://iacesan51.surge.sh" target="_blank">Conoce más »</a></p>
          </div><!-- / .Clasificador Perros_Gatos --><br>


          <div class="col-lg-4">
            <img src="assets/docente.jpg" class="bd-placeholder-img rounded-circle " width="250" height="160" margin-right="15px" alt="">
            
            <h2 class="fw-normal"><br>Sitio Web</h2>
            <p>Plantilla de sitio web realizada con Python, Flask, HTML, CSS y Bootstrap<br>
               Logueo de Administrador.</p>  
            <p><a class="btn btn-secondary" href="https://github.com/cesan51/sitio_web_plantilla" target="_blank">Conoce más »</a></p>
          </div><!-- / .Sitio web plantilla --><br>



          <div class="col-lg-4">
            <img src="assets/cgm.jpeg" class="bd-placeholder-img rounded-circle" width="250" height="160" margin-right="15px" alt="">
            
            <h2 class="fw-normal"><br>Servi Constru Gases Montaño.</h2>
            <p>Plantilla de pagina web realizada con angular para la empresa<br>
               Servi Constru Gases Momntaño.</p>  
            <p><a class="btn btn-secondary" href="https://github.com/cesan51/constru_gases_montano" target="_blank">Conoce más »</a></p>
          </div><!-- / .Constru Gases Montaño --><br>




          <div class="col-lg-4">
            <img src="assets/blog.png" class="bd-placeholder-img " width="250" height="160" margin-right="15px" alt="">
            
            <h2 class="fw-normal"><br>Blog Público.</h2>
            <p>Plantilla de blog de uso en web realizada con Python, Flask, HTML y CSS<br>
               Logueo de Usuarios.</p>  
            <p><a class="btn btn-secondary" href="https://github.com/cesan51/blog_plantilla" target="_blank">Conoce más »</a></p>
          </div><!-- / .Blog plantilla --><br>



          <div class="col-lg-4">
              <img src="assets/auditoria.png" class="bd-placeholder-img " width="120" height="160" margin-right="15px" alt="">
              <h2 class="fw-normal"><br>Auditoría de Red de la Alcaldía Municipal de Andalucía, Valle del cauca.</h2>
              <p>Desarrollo de auditoría de redes de la Alcaldía de Andalucia, Valle del Cauca, Colombia.</p>
              <p><a class="btn btn-secondary" href="https://drive.google.com/file/d/1TkDiMhEbD9jFQW0Ji8RzdExNz6Oh8F8d/view?usp=sharing" target="_blank">Conoce más »</a></p>
            </div><!-- / .Auditoría de redes --><br>



            <div class="col-lg-4">
                <img src="assets/informe.png" class="bd-placeholder-img" width="120" height="160" margin-right="15px" alt="">  
                <h2 class="fw-normal"><br> Seguridad informática enfocada en los trabajadore de los entornos empresariales. </h2>
                <p>Informe sobre Seguridad informatica como parte de seminario de Ciber Seguridad.</p>
                <p><a class="btn btn-secondary" href="https://drive.google.com/file/d/14S-2YorW9gdFvO3kMK_Pn4l8YGJZ2ITL/view?usp=share_link" target="_blank">Conoce más »</a></p>
            </div><!-- / .Informe Ciber Seguridad --><br>
  
           
        </div><!-- /.row -->
        
    </div>
   </div><!--/ .Container Proyectos-->


  


    <!--Container Certificados -->
   <a id="certificados"></a><br>
   <div class="container">
    <div class="proyects">
        <hr class="featurette-divider">
        <h3> Certificados</h3>
        <h2>Si deseas mas información contactame</h2><br><br>
        <div class="row">

            <div class="col-lg-4">
                <img  src="assets/ciber.png" class="bd-placeholder-img " width="240" height="160" alt="">
       
               <h2 class="fw-normal"><br>Seminario Ciber Seguridad. Seminario.</h2>
               <p><a class="btn btn-secondary" href="https://drive.google.com/file/d/1igMuQW7BrYyiSYzT8cYQ-eyrSaPVEqYl/view?usp=sharing" target="_blank">Verifica »</a></p>
             </div><!-- / .ciber seguridad Diploma -->
   

             <style> 
                 .col-lg-4 img{
                     transition: 0.2s;
                     object-fit: cover;
                 }
                 .col-lg-4 img:hover{
                     transform: scale(1.2);
                 }
             </style>
         
   
             <div class="col-lg-4">
               <img src="assets/atencion.png" class="bd-placeholder-img " width="240" height="160" margin-right="15px" alt="">
               
               <h2 class="fw-normal"><br>Atención y servicio al cliente. Diploma.</h2>
               
               <p><a class="btn btn-secondary" href="https://drive.google.com/file/d/1hjYWq1v74cXotN3gA6oRCbA6tqq4wDLl/view?usp=sharing" target="_blank">Verifica »</a></p>
             </div><!-- / .Atencion al cliente Diploma -->


          

           
           
        </div><!-- /.row -->
    
        
    </div>
   </div><!--/.Container Certificaciones-->

     
        

            
     <!-- Pie de pagina-->
     <a id="contactanos"></a><br><br>
  <div class="b-example-divider"></div>
  
  <div class="bg-dark text-secondary mt-5 px-4 py-2 text-center">


    <div class="py-5 bg-dark">
      <h3 class="bg-dark display-5 fw-bold text-white">cesan51</h3>
      <div class="col-lg-6 mx-auto">
          <p class="fs-5 mb-4 text-white">Desarrollador de Software</p> <p></p>
          <div class="row">

            <div class="col-lg-4">
                <img  src="assets/whatsapp.webp" class="bd-placeholder-img " width="35" height="35" alt="">
                <p class="fs-1 mb-1 text-white">Whatsapp: 3223823977</p>
               <p><a class="btn btn-secondary text-white" href="https://wa.me/573223823977" target="_blank">whatsapp</a></p>
            </div><!-- / .whatsapp -->
    
         
    
         <div class="col-lg-4">
            <img  src="assets/gmail.webp" class="bd-placeholder-img " width="35" height="35" alt="">
            <p class="fs-1 mb-1 text-white">Gmail: cesantonigo@gmail.com</p>
           <p><a class="btn btn-secondary text-white" href="https://www.google.com/intl/es-419/gmail/about/" target="_blank">Gmail</a></p>
         </div><!-- / .gmail -->


         <div class="col-lg-4">
            <img  src="assets/github.png" class="bd-placeholder-img " width="35" height="35" alt="">
            <p class="fs-1 mb-1 text-white">GitHub: cesan51</p>
           <p><a class="btn btn-secondary text-white" href="https://github.com/cesan51" target="_blank">GitHub</a></p>
         </div><!-- / .whatsapp --> 
           
        </div><!-- /.row contacto-->

      </div>

    </div>


    <h2 class="float-end"><a href="#">Sube</a></h2>

      <h2><a href="https://drive.google.com/file/d/1TtIIvxsPSbF7bMOC21WSoPnSSUYbdN3s/view?usp=sharing" target="_blank">Terminos y Condiciones</a><br><br>
        © 2022. 
      
      Desarrollador: César Antonio Gómez Montaño <br></h2>
  </div><!-- /.Pie de pagina-->

<!--Start of Tawk.to Script-->
<script type="text/javascript">
  var Tawk_API=Tawk_API||{}, Tawk_LoadStart=new Date();
  (function(){
  var s1=document.createElement("script"),s0=document.getElementsByTagName("script")[0];
  s1.async=true;
  s1.src='https://embed.tawk.to/668b6fcceaf3bd8d4d194d9c/1i28apdhj';
  s1.charset='UTF-8';
  s1.setAttribute('crossorigin','*');
  s0.parentNode.insertBefore(s1,s0);
  })();
  </script>
  <!--End of Tawk.to Script-->


<!-- Scripts Bootstrap-->
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js" integrity="sha384-oBqDVmMz9ATKxIep9tiCxS/Z9fNfEXiDAYTujMAeBAsjFuCZSmKbSSUnQlmh/jp3" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js" integrity="sha384-mQ93GR66B00ZXjt0YO5KlohRA5SY2XofN4zfuZxLkoj1gXtW8ANNCe9d5Y3eG5eD" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.3.0/js/bootstrap.bundle.min.js"></script>
 

  </body></html>



<!--
**cesan51/cesan51** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

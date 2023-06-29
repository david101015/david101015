<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" type="image/png" media='screen' href="img/logo.png">
    <link rel="stylesheet" href="css/styleprincipal.css">
    <link href='https://unpkg.com/boxicons@2.1.1/css/boxicons.min.css' rel='stylesheet'>
    <title>Principal</title>
</head>

<body>
    <nav class="sidebar">
        <header>
            <div class="image-text">
                <span class="image">
                    <img src="img/logo.png" alt="">
                </span>

                <div class="text logo-text">
                    <span class="name">Gorras</span>
                    <span class="profession">Urbanas</span>
                </div>
            </div>

            <i class='bx bx-chevron-right toggle'></i>
        </header>

        <div class="menu-bar">
            <div class="menu">

                <li class="search-box">
            
                </li>

                <ul class="menu-links">
                    <li class="nav-link">
                        <a href="principal.html">
                            <i class='bx bx-chevron-right-circle icon' ></i>
                            <span class="text nav-text">Sobre Nosotros</span>
                        </a>
                    </li>

                    <li class="nav-link">
                        <a href="principal2.html">
                            <i class='bx bx-basket icon' ></i>
                            <span class="text nav-text">Algunos Productos</span>
                        </a>
                    </li>

                    <li class="nav-link">
                        <a href="principal3.html">
                            <i class='bx bx-phone icon' ></i>
                            <span class="text nav-text">Contacto</span>
                        </a>
                    </li>

                    <li class="nav-link">
                        <a href="indexregistro.html">
                            <i class='bx bx-user icon' ></i>
                            <span class="text nav-text">Registrarte Aquí</span>
                        </a>
                    </li>

                </ul>
            </div>

            
        </div>

    </nav>

    <br>
    <br>


    <section class="home" id="home">
        <div class="title-conta"><center>Sobre Nosotros</center></div>

        <br>
        
            <div class="containerss">

              <center>

                    <span>Somos un sistema en cargado de vender gorras urbanas , Nuestro objetivo siempre ha sido acercar al público la mayor variedad de </span>
                    <br>
                    <span>modelos posible de las marcas,colores y estilos las  más selectas del mercado son,gorras unisex las cuales son ajustables a cualquier </span>
                    <br>
             </center>

            </div>
            <span style="margin-left: 25px;">tamaño y la gran mayoria son planas y se pueden moldear a semi curvas.</span>
                <br>
                <br>
    
                <center>
               <img src="img/1.png" alt="" height="180" width="200" class="imgagenes"> 
               <img src="img/2.png" alt="" height="180" width="200" class="imgagenes">
               <img src="img/3.png" alt="" height="180" width="200" class="imgagenes">
               </center>
            
               <br>
               <br>
               <br>
                
               <center><a class="descarga" download="CATALOGO GORRAS URBANAS" href="CATALOGO GORRAS_URBANAS.pdf" style="color:#00ca11 ;">
                         <i class='bx bxs-download icon' >
                        <span>Descargar Catalogo.</span></i>
                        </a></center>
              




          <div >
           
            

          </div>
           
    </section>

    <script>
        const body = document.querySelector('body'),
      sidebar = body.querySelector('nav'),
      toggle = body.querySelector(".toggle"),
      searchBtn = body.querySelector(".search-box"),
      modeSwitch = body.querySelector(".toggle-switch"),
      modeText = body.querySelector(".mode-text");


toggle.addEventListener("click" , () =>{
    sidebar.classList.toggle("close");
})

searchBtn.addEventListener("click" , () =>{
    sidebar.classList.remove("close");
})

</script>
  
</body>
</html>

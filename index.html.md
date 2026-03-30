<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
	<title>CocinandoAndamos</title>

<!--Código CSS-->
	<style>
	/* CSS */
    body{ background-color: rgb(250, 218, 165); text-align: justify;  line-height: 27px; }
    header{ color: black;  text-align: center; }
    footer{ color: rgb(142, 52, 0); }
    /*COMBI*/ header, footer{background-color: rgb(255, 255, 255);}
    h2{ color: rgb(84, 29, 6); }
    h3{color: rgb(225, 70, 54)}
    
  /* ID */
    #Titulo{ font-family: "Lucida Handwriting";}
    #Empieza_texto{ font-family: "Georgia"; }
    #Descrip{ font-family: "Trebuchet MS"; text-shadow: yellow 3px 0; }
    #Derechos_autor{text-decoration: underline; }
    #caja1{padding: 10px 0px 10px 0px;}
    #caja2{padding: 10px 0px 10px 0px;}
    #caja3{padding: 10px 0px 10px 0px;}
    #caja4{padding: 10px 0px 10px 0px;}
    
    /*Solo quiero aplicar la posición a las imágenes*/
    #PP{position: relative; top: -3px; left: 10px;}
    
    /*COMBI ID+CLASS*/#Intro,p.Mas_info,footer{font-size: 20px; font-family: "Trebuchet MS";  }
    
  /* CLASES*/
    .titulo{ font-size: 35px; letter-spacing: 5px;}
    .Inicio{ font-size: 30px; }
    .Receta{ font-size: 30px; font-family: "Times New Roman"; text-align: center; }
    .Mas_info{ font-size: 20px; }
  .titulo.Inicio.Receta.Mas_Info {padding: 10px;}
  
  
  /*NAV*/  
    nav{display: block; width: 100%; height: 125px; overflow: auto; }
    /*COMBI*/ aside, nav {background-color: rgb(255, 245, 195); justify-content: left; padding: 0;
    margin: 0; }
    .lista_indice{ display: inline-block; padding: 3px 3px; float: left; }
    
   /*HOVER*/
   button{background: rgb(255,255,255,0.6); color: rgb(130, 92, 55, 51); font-family: "Trebuchet MS";}
   button:hover{ background: rgb(247, 117, 87, 97); color: black; }
    
    
  /*SELEC.DESCENT*/ 
  #Tabla1 .Content { background: rgb(255,255,255,0.6); padding: 8px 12px; border-bottom: 1px solid rgb(0,0,0,0.06); }
  #Tabla1 .Title { background-color: rgb(226, 175, 135); padding: 10px 12px; text-align: left;}
  
  #Tabla2 .Content { background: rgb(255,255,255,0.6); padding: 8px 12px; border-bottom: 1px solid rgb(0,0,0,0.06); }
  #Tabla2 .Title { background-color: rgb(226, 175, 135); padding: 10px 12px; text-align: left;}
    
  /*CAJAS*/  
  .Caja1{ background: rgb(255, 245, 195);
            width: 100%;
            height: 250px;
            overflow-y: auto;
            overflow-x: hidden;
            margin: 10px 10px 0px 0px;
            border: 1px solid rgb(145, 0, 0); }
            
   .Caja2{ background: rgb(255, 245, 195);
            width: 100%;
            height: 90%;
            overflow-y: auto;
            overflow-x: hidden;
            margin: 10px 10px 0px 0px;
            border: 1px solid rgb(145, 0, 0); }
            
   .Caja3{ background: rgb(255, 245, 195);
            width: 100%;
            height: 90%;
            overflow-y: auto;
            overflow-x: hidden;
            margin: 10px 10px 0px 0px; 
            border: 1px solid rgb(145, 0, 0); }
            
   .Caja4{ background: rgb(255, 245, 195);
            width: 100%;
            height: 100px;
            overflow-y: auto;
            overflow-x: hidden;
            margin: 10px 10px 0px 0px;}
            
  </style>
<!--Código CSS-->
</head>

<header>
  <img src="https://st4.depositphotos.com/1496387/38299/v/450/depositphotos_382990074-stock-illustration-hand-drawn-logo-cooking-menu.jpg" 
  alt="Logo" width="120" height="100"> 
  <h1 class="titulo"; id="Titulo">CocinandoAndamos</h1>
  <h2 id="Descrip">Recetas hogareñas</h2>
</header>

<nav>
   <h2 class="Receta"; id="Empieza_texto">Recetas:</h2>
  <p class="Navegador">
    <ul>
      <li class="lista_indice"><a href="#Gelatina"><button >Gelatina</button></a></li>
      <li class="lista_indice"><a href="#Esponjado"><button>Esponjado de Gelatina</button></a></li>
      <li class="lista_indice"><button>Natilla</button></li>
      <li class="lista_indice"><button>Pankequitas</button></li>
      <li class="lista_indice"><button>Coulis de Frutos Rojos</button></li>
    </ul>
  </p>
</nav>


<!--Bootstrap-->
<!--Decidí sólo agregar esta barra de progreso,
puesto que me gusta mucho como está mi pagina ahora y ninguna función del Framework me convence para ser agregada.
Además que me movió algunos valores, lo cual no me agrada D:-->
  <p><strong><em>Contenido agregado:</em></strong></p>
  <div class="progress" role="progressbar" aria-label="Example with label" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">
  <div class="progress-bar" style="width: 40%">40%</div>
  </div>

<body>
   
  <div class="Caja1"; id="caja1">
  <section>
    <h2 class="Inicio"; id="Empieza_texto">Introducción</h2>
    <article>
      <p id="Intro">
        Hola a todos, <em>esta página es hecha para recopilar y difundir algunas recetas hogareñas
      para toda ocasión</em>, sin embargo <strong>la página contará únicamente con recetas dulces</strong>, porque son las únicas que la autora sabe hacer.
      Además, podrán encontrar todos los implementos, medidas y pasos para la elaboración de las recetas.
      <em><strong>Recuerda priorizar las medidas de seguridad y ¡A COCINAR!</strong></em>
      </p>
    </article>
  </section>
  </div>
  
  <div class="Caja2"; id="caja2">
  <section>
    <h2 class="Receta"; id="Gelatina">Gelatina</h2>
    <img id="PP"; src="https://kitchenacademy.es/wp-content/uploads/gelatina.jpg"
    alt="Foto de una Gelatina Roja" width="140" height="160">
    <h3>Lista implementos</h3>
    <div id="Tabla1">
    <table>
      <thead>
       <tr>
        <th class="Title">Ingredientes</th>
        <th class="Title">Cantidades</th>
       </tr>
       <tr>
        <td class="Content">Sobre de Gelatina en polvo</td>
        <td class="Content">1 Unidad</td>
       </tr>
       <tr>
        <td class="Content">Agua caliente y fría</td>
        <td class="Content">1 Taza de agua por cada una</td>
       </tr>
      </thead>
    </table>
    </div>
    <h3>Utensilios</h3>
    <ul>
      <li>Olla</li>
      <li>Cuchara</li>
      <li>Bowl</li>
      <li>Recipiente resistente al calor y apto para la nevera</li>
    </ul>
     <h3>Paso a paso</h3>
    <ol>
      <li>Hierve 1 Taza de agua</li>
      <li>Con el agua caliente, disuelve con la cuchara el sobre de gelatina en el Bowl</li>
      <li>Vierte 1 Taza de agua fría y mezcla</li>
      <li>Deja el Bowl en la nevera o vierte la gelatina en un recipiente para nevera </li>
      <li>Deja refrigerar en promedio, <em>4 horas</em>. Luego de este tiempo, estará lista para consumir</li>
    </ol>
    <p>
      En caso de querer una <strong>contextura más dura</strong> solo vierte 1/2 Taza de agua caliente con 1 y 1/2 de agua fría.<br>
      Si quieres una <strong>contextura más blanda</strong>, invierte las cantidades.
    </p>
    <h3>Porciones: Entre 6 y 10 unidades</h3>
  </section>
  </div>
  
  <div class="Caja3"; id="caja3">
  <section>
    <h2 class="Receta"; id="Esponjado"> Esponjado de Gelatina</h2>
    <img id="PP"; src="https://img-global.cpcdn.com/recipes/1fe742e9e9138ece/680x781cq80/postre-esponjado-de-gelatina-foto-principal.jpg"
    alt="Foto de un Esponjado de 2 colores" width="140" height="160">
    <h3>Lista implementos</h3>
    <div id="Tabla2">
    <table>
      <thead>
       <tr>
        <th class="Title">Ingredientes</th>
        <th class="Title">Cantidades</th>
       </tr>
       <tr>
        <td class="Content">Sobre de Gelatina en polvo</td>
        <td class="Content">1 Unidad</td>
       </tr>
       <tr>
        <td class="Content">Leche caliente y fría</td>
        <td class="Content">1 Taza de leche por cada una</td>
       </tr>
      </thead>
    </table>
    </div>
    <h3>Utensilios</h3>
    <ul>
      <li>Olla</li>
      <li>Cuchara</li>
      <li>Bowl</li>
      <li>Recipiente resistente al calor y apto para la nevera</li>
    </ul>
     <h3>Paso a paso</h3>
    <ol>
      <li>Hierve 1 Taza de leche</li>
      <li>Con la leche caliente, disuelve con la cuchara el sobre de gelatina en el Bowl</li>
      <li>Vierte 1 Taza de leche fría y mezcla</li>
      <li>Deja el Bowl en la nevera o vierte el esponjado en un recipiente para nevera </li>
      <li>Deja refrigerar en promedio, <em>5 horas</em>. Luego de este tiempo, estará listo para consumir</li>
    </ol>
    <p>
      <strong>Esta es una variante de la primer receta y no tiene verisón dura o suave</strong>, <em>se recomienda acompañar con leche condensada.</em>
    </p>
    <h3>Porciones: Entre 6 y 10 unidades</h3>
  </section>
  </div>
  
<div class="Caja4" ; id="caja1">  
<aside class="Mas_info"; id="Descrip">
  <a target="_blank" href="https://omnivoro.mx/"><strong>Página de alimentos salados</strong></a>
  <p id="Derechos_autor">Derechos Reservados al Autor de esa página: Josue Flores</p>
</aside>
</div>
</body>

<div>
<footer>
  <em>Autor:</em> <img src="https://i.pinimg.com/736x/c7/1a/77/c71a7758b9be480fcb8954146b9fe18b.jpg" width="30"height="33">
  Juana Carolina Cruz <br>
  <em>Institución:</em> Skolmi <br>
  <em>Contacto:</em> +57 ******0489 <br>
  <em>Correo:</em> juanaccruzc03@gmail.com <br>
</footer>
</div>
</html>

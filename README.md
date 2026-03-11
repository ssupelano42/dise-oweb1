<!DOCTYPE html>
<html lang="es">
<head>
      <script src="https://cdn.tailwindcss.com"></script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi primera pagina</title>
</head>
<body>

    
    <header>
        <div> 
            
            <h1 class="text-4xl font-bold text-center text-blue-500 bg-red-400  mb-4 p-4">
                MI EMPRESA
            </h1>

            

            <nav>
                <a href="#inicio">Inicio</a>
                <a href="#servicios">servicios</a>
                <a href="#contacto">contacto</a>

            </nav>
        </div>
    </header>

    <!--SECCION PRINCIPAL-->
    <main>
<!--SECCION: Agrupa contenido tematico-->
<section id="Inicio">
    <h2>Bienvenidos</h2>
    <p>somos una empresa dedicada a crear soluciones digitales</p>
    <button>ver mas</button>
    <button>contactar</button>
</section>

<!--SECCION DE SERVICIOS-->
<section id="servicios">
    <h2>nuetros servicios</h2>
  <!--ARTICULO: Contenido independiente y reutilizable-->
    <article>
        <h3>diseño web</h3>
        <p>creamaos sitis web modernos y funcionales,</p>
    </article>

    <article>
        <h3>desarrollo</h3>
        <p>programamos aplicaciones a medida,</p>
    </article>
    <article>
        <h3>marketing</h3>
        <p>aunmentamos tu presencia digital,</p>
    </article>
</section>
<!--SECCION DE CONTACTO-->
<section id="contacto">
    <h2>contacto</h2>
    <form>
        <div>
            <label for="nombre" nombre; label>
                <input type="text" id="nombre" placeholder="tu nombre"
            
            <label for="email">email</label>
            <input type="email" id="email" placeholder="tu email.com" 
            <button type="submit" enviar button></button>


        </div>
    </form>
    </main>




</body>
</html>

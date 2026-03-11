<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi primera Pagina</title>
     <script src="https://cdn.tailwindcss.com"></script>
</head>
<body>

 <header>
    <div class="bg-blue-500">
        
        <h1 class="text-center">Mi empresa</h1>
        <nav>
            <a href="inicio">Inicio</a>
            <a href="servicios">Servicios</a>
       </nav>
    </div>
 </header>

 <main class="bg-red-300 text-center" >
    <selection id="inicio">
        <h2 class="text-center">Bienvenidos</h2>
      <p class="bg-gray-250">Somos una empresa dedicada a crear soluciones digitales.</p>  
      <button class="text-center">Ver mas</button>
      <button class="text-center">Contactar</button>
      <div class="bg-red-500">
    </selection>
    <section id="Servicios">
    <h2 class="text-center">Nuestro servicios</h2>

    <article>  
        <h3><Data class="text-center">Diseño web</Data></h3>
        <p class="text-center">Creamos sitios web modernos y funcionales.</p>
        
     </article>

     <article>
        <h3 class="text-center">Desarrollo</h3>
        <p class="text-center">Programamos aplicaciones a medida</p>
     </article>

     <article >
      <h3 class="text-center">Marketing</h3>
      <p class="text-center">Creamos sitios web modernos y funcionales.</p>
      
     </article>

     <arcicle>
     <h3 class="text-center">Desarrollo</h3>
     <p class="text-center">Programamos aplicaciones o medidas.</p>
     </arcicle>

    <arcicle>
      <h3 class="text-center">Marketing</h3>
      <p class="text-center">Aumentamos tu presencia digital.</p>
     </arcicle>
     </selection>

     <selection id="contacto">
     <h2 class="text-center">Contacto</h2>
     <form>
        <div>
                    <label for="nombre">Nombre:</label>
                    <input type="text" id="nombre" placeholder="Tu nombre">
                </div>
                <div>
                    <label for="email">Email:</label>
                    <input type="email" id="email" placeholder="tu@email.com">
                </div>
                <button type="submit">Enviar</button>
            </form>
        </selection>
    </main>

    <footer>
        <pclass="text-center">© 2024 Mi Empresa</p>
    </footer>

</body>
</html>

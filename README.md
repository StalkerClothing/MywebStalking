<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Stalker Clothing and Desing</title>
  <style>
    /* Estilos básicos */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Arial', sans-serif;
      background-color: #111;
      color: #fff;
      line-height: 1.6;
    }
    /* Navegación */
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background: rgba(0,0,0,0.8);
      padding: 1rem;
      display: flex;
      justify-content: center;
      z-index: 1000;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 1rem;
      font-size: 1.1rem;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #f39c12;
    }
    /* Sección Hero */
    header {
      background: url('https://via.placeholder.com/1500x600?text=Stalker+Background') no-repeat center center/cover;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      position: relative;
    }
    header::after {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0,0,0,0.5);
    }
    header h1 {
      font-size: 4rem;
      z-index: 1;
      margin-bottom: 1rem;
    }
    header p {
      font-size: 1.5rem;
      z-index: 1;
    }
    /* Secciones generales */
    section {
      padding: 4rem 2rem;
    }
    section h2 {
      text-align: center;
      margin-bottom: 2rem;
      font-size: 2.5rem;
      position: relative;
    }
    section p {
      max-width: 800px;
      margin: 0 auto;
      font-size: 1.1rem;
      text-align: center;
    }
    /* Galería de diseños */
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      grid-gap: 1rem;
      padding: 0 2rem;
    }
    .gallery img {
      width: 100%;
      height: auto;
      border: 5px solid #fff;
      transition: transform 0.3s;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    /* Formulario de contacto */
    .contact form {
      max-width: 600px;
      margin: 0 auto;
      display: flex;
      flex-direction: column;
    }
    .contact input, .contact textarea {
      padding: 1rem;
      margin: 0.5rem 0;
      border: none;
      border-radius: 5px;
    }
    .contact button {
      padding: 1rem;
      background: #f39c12;
      border: none;
      border-radius: 5px;
      color: #fff;
      font-size: 1.1rem;
      cursor: pointer;
      transition: background 0.3s;
    }
    .contact button:hover {
      background: #e67e22;
    }
    /* Pie de página */
    footer {
      background: #000;
      text-align: center;
      padding: 2rem;
    }
  </style>
</head>
<body>
  <!-- Menú de navegación -->
  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#acerca">Acerca</a>
    <a href="#diseños">Diseños</a>
    <a href="#contacto">Contacto</a>
  </nav>
  
  <!-- Sección principal o "Hero" -->
  <header id="inicio">
    <h1>Stalker Clothing and Desing</h1>
    <p>Depredador de marcas: Estilo urbano que desafía lo convencional</p>
  </header>
  
  <!-- Sección Acerca de -->
  <section id="acerca">
    <h2>Acerca de la marca</h2>
    <p>Stalker Clothing and Desing es una marca única de ropa que fusiona elementos del reggaetón, trap latino y rap con diseños gráficos inspirados en animales e insectos. La palabra “Desing” se emplea en lugar de “Design” como un homenaje a mis raíces portuguesas, reinterpretando “stalker” como la fuerza y astucia de un depredador urbano.</p>
  </section>
  
  <!-- Sección Galería de Diseños -->
  <section id="diseños">
    <h2>Galería de Diseños</h2>
    <div class="gallery">
      <!-- Ejemplos de imágenes. Reemplaza los enlaces por tus diseños reales -->
      <img src="https://via.placeholder.com/400x400?text=Diseño+1" alt="Diseño 1">
      <img src="https://via.placeholder.com/400x400?text=Diseño+2" alt="Diseño 2">
      <img src="https://via.placeholder.com/400x400?text=Diseño+3" alt="Diseño 3">
      <img src="https://via.placeholder.com/400x400?text=Diseño+4" alt="Diseño 4">
      <img src="https://via.placeholder.com/400x400?text=Diseño+5" alt="Diseño 5">
      <img src="https://via.placeholder.com/400x400?text=Diseño+6" alt="Diseño 6">
      <!-- Agrega aquí el resto de tus diseños -->
    </div>
  </section>
  
  <!-- Sección de Contacto -->
  <section id="contacto" class="contact">
    <h2>Contacto</h2>
    <form action="#" method="post">
      <input type="text" name="nombre" placeholder="Tu nombre" required>
      <input type="email" name="email" placeholder="Tu email" required>
      <textarea name="mensaje" rows="5" placeholder="Tu mensaje" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>
  
  <!-- Pie de página -->
  <footer>
    <p>&copy; 2025 Stalker Clothing and Desing. Todos los derechos reservados.</p>
  </footer>
</body>
</html>

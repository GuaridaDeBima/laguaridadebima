<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>La Guarida de Bima Puerto Montt</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Header y navegación -->
  <header>
    <div class="container header-container">
      <h1>La Guarida de Bima</h1>
      <nav>
        <ul>
          <li><a href="#hero">Inicio</a></li>
          <li><a href="#menu">Menú</a></li>
          <li><a href="#ubicacion">Ubicación</a></li>
          <li><a href="#contacto">Contacto</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <!-- Sección Hero -->
  <section id="hero">
    <div class="hero-container">
      <!-- Placeholder para imagen principal -->
      <div class="hero-image">
        <img src="burger-food-sq.jpg" alt="">
      </div>
      <div class="hero-text">
        <h2>¡Bienvenido a La Guarida de Bima</h2>
        <p>Rápido, delicioso y siempre a tu alcance.</p>
      </div>
    </div>
  </section>

  <!-- Sección Menú -->
  <section id="menu">
    <div class="container">
      <h2>Preparaciones Mas Destadacadas</h2>
      <div class="menu-grid">
        <!-- Tarjeta de menú: Hamburguesa -->
        <div class="menu-item">
          <div class="img-placeholder" style="background-color: #f39c12;">
            <img src="burger-sm.jpeg" alt="">
          </div>
          <h3>Sandwich de Vacuno</h3>
          <p>Con Carne jugosa, queso derretido y palta, tomate frescos.</p>
        </div>
        <!-- Tarjeta de menú: Papas Fritas -->
        <div class="menu-item">
          <div class="img-placeholder" style="background-color: #27ae60;">
            <img src="papas-fritas-sm.jpg" width="300px" alt="q">
          </div>
          <h3>Papas Fritas</h3>
          <p>Papas crujientes, el acompañante perfecto.</p>
        </div>
        <!-- Tarjeta de menú: Batido -->
        <div class="menu-item">
          <div class="img-placeholder" style="background-color: #2980b9;">
            <img src="sopaipillas-sm.jpg" width="300" height="200" alt="">
          </div>
          <h3>Sopaipillas</h3>
          <p>Ricas, Crocantes, Sabrosas, ideal para cualquier momento.</p>
        </div>
      </div>
    </div>
  </section>

  <section id="hero">
    <div class="hero-container">
      <!-- Placeholder para imagen principal -->
      <div class="hero-image">
        <img src="refrescos-sm.jpg" alt="">
      </div>
      <div class="hero-text">
        <h2>Todo en un solo lugar</h2>
        <p>Sopaipillas crujientes, papas fritas doradas y Después de un refresco, un bocado sabroso y fresco.</p>
      </div>
    </div>
  </section>

  <!-- Sección Ubicación -->
  <section id="ubicacion">
    <div class="container">
      <h2>Ubicación</h2>
      <a href="https://www.google.cl/maps/place/La+Guarida+De+Bima/@-41.456447,-72.9611845,101m/data=!3m1!1e3!4m6!3m5!1s0x96183b0b6c76d169:0x1bb2bd7a98be66!8m2!3d-41.4564426!4d-72.9614788!16s%2Fg%2F11v3jtl0zg?entry=ttu&g_ep=EgoyMDI1MDEyOS4xIKXMDSoASAFQAw%3D%3D" target="_blank">Ver ubicación en Google Maps</a>
      <div class="map-placeholder" style="background-color: #bdc3c7;">
        <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d2990.1980957803107!2d-72.961986780422!3d-41.456618637808425!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x96183b0b6c76d169%3A0x1bb2bd7a98be66!2sLa%20Guarida%20De%20Bima!5e0!3m2!1ses!2scl!4v1738596227704!5m2!1ses!2scl" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>  
    </div>
    <br>
      <p>Nos encontramos en Calle Bima S/N, Puerto Montt</p>
    </div>
  </section>

  <!-- Sección Contacto -->
  <section id="contacto">
    <div class="container">
     <center> <h2>Contacto</h2></center>
      <form>
        <label for="name">Nombre:</label>
        <input type="text" id="name" placeholder="Tu nombre" required>

        <label for="email">Email:</label>
        <input type="email" id="email" placeholder="Tu email" required>

        <label for="message">Mensaje:</label>
        <textarea id="message" rows="4" placeholder="Tu mensaje" required></textarea>

        <button type="submit">Enviar</button>
      </form>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">
      <p>&copy; 2025 La Guarida de Bima. Todos los derechos reservados.</p>
    </div>
  </footer>
</body>
</html>

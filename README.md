# Empanadia
# ¡Bienvenido a EmpanadIA! 🥟  **El delicioso mundo de las empanadas está a solo un clic de distancia.**  Las empanadas son mucho más que una comida: representan tradición, cultura, creatividad y una gran variedad de sabores que han conquistado cocinas alrededor del mundo. 
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="EmpanadIA: descubre el delicioso mundo de las empanadas.">
  <title>EmpanadIA | El sabor que nos une</title>

  <style>
    :root {
      --crema: #fff8e9;
      --dorado: #d9a441;
      --cafe: #593923;
      --cafe-claro: #805638;
      --blanco: #ffffff;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: var(--crema);
      color: var(--cafe);
      line-height: 1.6;
    }

    header {
      background: var(--cafe);
      color: var(--blanco);
      padding: 18px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 15px;
    }

    .logo {
      font-size: 28px;
      font-weight: bold;
      color: var(--dorado);
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      color: var(--dorado);
    }

    .hero {
      min-height: 440px;
      padding: 80px 8%;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      background: linear-gradient(135deg, #fff1d1, #f3d59d);
    }

    .hero-content {
      max-width: 750px;
    }

    .hero h1 {
      font-size: clamp(38px, 7vw, 65px);
      margin-bottom: 18px;
      color: var(--cafe);
    }

    .hero p {
      font-size: 19px;
      margin-bottom: 28px;
    }

    .btn {
      display: inline-block;
      background: var(--cafe);
      color: white;
      text-decoration: none;
      padding: 13px 25px;
      border-radius: 30px;
      font-weight: bold;
      transition: 0.2s;
    }

    .btn:hover {
      background: var(--cafe-claro);
      transform: translateY(-2px);
    }

    section {
      padding: 65px 8%;
      text-align: center;
    }

    section h2 {
      font-size: 34px;
      margin-bottom: 18px;
      color: var(--cafe);
    }

    .intro {
      max-width: 800px;
      margin: auto;
      font-size: 17px;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 22px;
      margin-top: 35px;
    }

    .card {
      background: var(--blanco);
      padding: 28px 22px;
      border-radius: 16px;
      box-shadow: 0 5px 18px #59392318;
      border-bottom: 5px solid var(--dorado);
    }

    .card .emoji {
      font-size: 42px;
      margin-bottom: 10px;
    }

    .card h3 {
      margin-bottom: 10px;
      color: var(--cafe);
    }

    .assistant-section {
      background: #f4e3c1;
    }

    .chat-container {
      max-width: 800px;
      margin: 30px auto 0;
      padding: 35px 20px;
      background: white;
      border-radius: 18px;
      box-shadow: 0 5px 18px #59392318;
    }

    .chat-container p {
      margin-bottom: 12px;
    }

    .chat-placeholder {
      padding: 25px;
      border: 2px dashed var(--dorado);
      border-radius: 12px;
      color: var(--cafe-claro);
      background: var(--crema);
    }

    footer {
      background: var(--cafe);
      color: white;
      padding: 28px 8%;
      text-align: center;
    }

    footer strong {
      color: var(--dorado);
    }

    @media (max-width: 600px) {
      header {
        justify-content: center;
        text-align: center;
      }

      nav {
        justify-content: center;
      }

      .hero {
        padding: 65px 6%;
      }

      section {
        padding: 50px 6%;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">🥟 EmpanadIA</div>

    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#nosotros">Nosotros</a>
      <a href="#informacion">Información</a>
      <a href="#asistente">Asistente IA</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="inicio">
      <div class="hero-content">
        <h1>¡Bienvenido a EmpanadIA!</h1>

        <p>
          Un espacio dedicado al delicioso mundo de las empanadas.
          Descubre, aprende y encuentra respuestas con nuestra
          asistente inteligente.
        </p>

        <a href="#asistente" class="btn">
          Conoce a nuestra asistente
        </a>
      </div>
    </section>

    <section id="nosotros">
      <h2>¿Qué es EmpanadIA?</h2>

      <p class="intro">
        EmpanadIA es un proyecto que combina la tradición
        gastronómica con la tecnología. Queremos compartir
        información sobre las empanadas y ofrecer una experiencia
        interactiva mediante inteligencia artificial.
      </p>
    </section>

    <section id="informacion">
      <h2>Descubre más</h2>

      <p class="intro">
        Las empanadas tienen una gran variedad de sabores,
        ingredientes y formas de preparación.
      </p>

      <div class="cards">
        <article class="card">
          <div class="emoji">🥟</div>
          <h3>Tradición</h3>
          <p>
            Conoce la historia y las tradiciones que rodean
            a las empanadas.
          </p>
        </article>

        <article class="card">
          <div class="emoji">🧀</div>
          <h3>Ingredientes</h3>
          <p>
            Descubre diferentes ingredientes, rellenos
            y combinaciones.
          </p>
        </article>

        <article class="card">
          <div class="emoji">👩‍🍳</div>
          <h3>Preparación</h3>
          <p>
            Aprende sobre las distintas maneras de preparar
            este delicioso alimento.
          </p>
        </article>

        <article class="card">
          <div class="emoji">🤖</div>
          <h3>Inteligencia artificial</h3>
          <p>
            Utiliza nuestra asistente virtual para resolver
            tus dudas sobre el proyecto.
          </p>
        </article>
      </div>
    </section>

    <section class="assistant-section" id="asistente">
      <h2>Conoce a nuestra asistente</h2>

      <p class="intro">
        ¿Tienes alguna pregunta? Nuestra asistente de EmpanadIA
        está preparada para ayudarte.
      </p>

      <div class="chat-container">
        <div class="chat-placeholder">
          <h3>🤖 Asistente EmpanadIA</h3>

          <p>
            Aquí aparecerá nuestro chat interactivo.
          </p>

          <p>
            ¡Muy pronto podrás conversar con EmpanadIA!
          </p>
        </div>

        <!--  --<script src="https://cdn.botpress.cloud/webchat/v5.0/inject.js"></script>
<script src="https://files.bpcontent.cloud/2026/11/24/05/20261124055625-UN4KXAED.js" defer></script>
      </div>
    </section>
  </main>

  <footer>
    <p>
      <strong>EmpanadIA</strong> · Tecnología y tradición en un solo lugar.
    </p>

    <p>© 2026 EmpanadIA. Todos los derechos reservados.</p>
  </footer>

</body>
</html>

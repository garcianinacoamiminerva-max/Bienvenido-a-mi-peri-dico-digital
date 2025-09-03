<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mi Periódico Digital</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f8f9fa;
      color: #212529;
    }
    header {
      background: #212529;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
    }
    main {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    .principal {
      background: #fff;
      padding: 1rem;
      border-radius: 10px;
      margin-bottom: 2rem;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1rem;
    }
    article {
      background: #fff;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    footer {
      background: #212529;
      color: #fff;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bienvenido a mi Periódico Digital</h1>
    <p>Noticias, cultura y opinión</p>
  </header>

  <main>
    <section class="principal">
      <h2>Titular Principal</h2>
      <p>Este es el espacio para tu noticia más importante del día. Aquí puedes colocar un resumen llamativo que despierte la curiosidad de tus lectores.</p>
    </section>

    <section class="grid">
      <article>
        <h3>Actualidad</h3>
        <p>Descripción breve de la noticia de actualidad. <a href="#">Leer más</a></p>
      </article>
      <article>
        <h3>Cultura</h3>
        <p>Contenido sobre cine, arte o eventos culturales. <a href="#">Leer más</a></p>
      </article>
      <article>
        <h3>Opinión</h3>
        <p>Un espacio para columnas editoriales y reflexiones. <a href="#">Leer más</a></p>
      </article>
    </section>
  </main>

  <footer>
    <p>© 2025 Mi Periódico Digital | Todos los derechos reservados</p>
  </footer>
</body>
</html>

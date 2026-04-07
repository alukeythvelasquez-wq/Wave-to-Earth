<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Wave to Earth</title>
  <link rel="stylesheet" href="style.css">
  @import url('https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600&display=swap');
<style>
body {
  font-family: 'Outfit', sans-serif;
  margin: 0;
  color: #e2e8f0;

  background-color: #c2e7fc;
  background-size: cover;
  background-position: bottom;
  background-repeat: no-repeat;
}


header {
  background-color: #e2e8f0;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;

  padding: 60px 20px;
  text-align: center;
  position: relative;
  color: #c2e7fc ;
}

header::before {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.5);
}

header h1,
header p {
  position: relative;
  z-index: 1;
}

header h1 {
  font-size: 3.5em;
  font-weight: 600;
  letter-spacing: 3px;
  text-transform: uppercase;
  color: #ffffff;

  text-shadow: 
    0 0 10px rgba(56, 189, 248, 0.8),
    0 0 20px rgba(56, 189, 248, 0.6),
    0 0 40px rgba(56, 189, 248, 0.4);

  animation: glow 2s infinite alternate;
}

@keyframes glow {
  0% {
    text-shadow: 
      0 0 5px rgba(56, 189, 248, 0.6),
      0 0 10px rgba(56, 189, 248, 0.4);
  }
  100% {
    text-shadow: 
      0 0 20px rgba(56, 189, 248, 1),
      0 0 40px rgba(56, 189, 248, 0.8);
  }
}

nav {
  background: rgba(30, 41, 59, 0.9);
  padding: 15px;
  text-align: center;
  backdrop-filter: none;
}

nav a {
  color: #e2e8f0;
  margin: 0 15px;
  text-decoration: none;
  font-weight: 500;
  position: relative;
  transition: all 0.3s ease;
}

nav a::after {
  content: "";
  position: absolute;
  width: 0%;
  height: 2px;
  left: 0;
  bottom: -5px;
  background-color: #38bdf8;
  transition: width 0.2s ease;
}

nav a:hover {
  color: #38bdf8;
}

nav a:hover::after {
  width: 100%;
}

section {
  padding: 30px;
  max-width: 900px;
  margin: 30px auto;
  background-color: rgba(15, 23, 42, 0.8);
  border-radius: 10px;
}

h2 {
  border-bottom: 2px solid #38bdf8;
  padding-bottom: 5px;
}

.video-container {
  display: flex;
  justify-content: center;
  margin: 20px 0;
}

iframe {
  width: 100%;
  max-width: 560px;
  height: 315px;
  border: none;
  border-radius: 10px;
}

table {
  width: 100%;
  border-collapse: collapse;
  margin-top: 20px;
  background-color: rgba(30, 41, 59, 0.8);
}

th, td {
  border: 1px solid #94a3b8;
  padding: 10px;
  text-align: center;
}

th {
  background-color: #38bdf8;
  color: black;
}

footer {
  text-align: center;
  padding: 15px;
  background: rgba(30, 41, 59, 0.9);
  margin-top: 20px;
}
</style>
</head>
<body>

<header>
  <h1>Wave to Earth</h1>
  <p>Grupo musical coreano de indie y lo-fi</p>
</header>

<nav>
  <a href="#info">Información</a>
  <a href="#miembros">Miembros</a>
  <a href="#musica">Música</a>
</nav>

<section id="info">
  <h2>Sobre el grupo</h2>
  <p>Wave to Earth es una banda surcoreana conocida por su estilo indie, lo-fi y alternativo. Su música transmite emociones suaves y atmósferas relajadas.</p>

  <table>
    <tr>
      <th>Origen</th>
      <th>Género</th>
      <th>Año debut</th>
    </tr>
    <tr>
      <td>Corea del Sur</td>
      <td>Indie / Lo-fi</td>
      <td>2019</td>
    </tr>
  </table>
</section>

<section id="miembros">
  <h2>Miembros</h2>

  <table>
    <tr>
      <th>Nombre</th>
      <th>Rol</th>
    </tr>
    <tr>
      <td>Daniel Kim</td>
      <td>Voz / Guitarra</td>
    </tr>
    <tr>
      <td>John Cha</td>
      <td>Bajo</td>
    </tr>
    <tr>
      <td>Dong Q</td>
      <td>Batería</td>
    </tr>
  </table>
</section>

<section id="musica">
  <h2>Música destacada</h2>
  <p>Uno de sus temas más populares es "bad", que representa muy bien su estilo relajado.</p>

  <div class="video-container">
    <iframe src="https://www.youtube.com/embed/6Q5xqNkCk7w" allowfullscreen></iframe>
  </div>

  <table>
    <tr>
      <th>Canción</th>
      <th>Año</th>
    </tr>
    <tr>
      <td>bad</td>
      <td>2023</td>
    </tr>
    <tr>
      <td>love.</td>
      <td>2023</td>
    </tr>
  </table>
</section>

<footer>
  <p>Página creada por keyth</p>
</footer>

</body>
</html>


# Wave-to-Earth

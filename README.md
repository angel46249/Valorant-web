<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Valorant Fan Page</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Valorant</h1>
    <nav>
      <a href="#agentes">Agentes</a>
      <a href="#mapas">Mapas</a>
      <a href="#armas">Armas</a>
      <a href="#curiosidades">Curiosidades</a>
      <a href="#habilidades">Habilidades</a>
      <a href="#noticias">Noticias</a>
      <a href="#galeria">Galería</a>
    </nav>
  </header>

  <section id="inicio">
    <div class="container">
      <h2>Bienvenido a Valorant</h2>
      <p>
        Valorant es un shooter táctico 5v5 desarrollado por Riot Games. Cada jugador elige un "agente" con habilidades únicas. El objetivo es colocar o desactivar la Spike, eliminando al equipo contrario o cumpliendo los objetivos del mapa.
      </p>
      <img
        src="https://images.contentstack.io/v3/assets/bltb6530b271fddd0b1/blt318843fe7a1a82db/61f42351b1f14274d3662511/VAL_EP4_Act1_KeyArt_Jett.jpg"
        alt="Valorant"
        width="800"
      />
    </div>
  </section>

  <section id="agentes">
    <div class="container">
      <h2>Agentes Destacados</h2>
      <ul>
        <li><strong>Jett</strong> – Ágil y letal, especialista en movimiento rápido.</li>
        <li><strong>Reyna</strong> – Ideal para duelos, se fortalece con cada baja.</li>
        <li><strong>Sova</strong> – Rastreador que revela enemigos con su dron y flechas.</li>
        <li><strong>Killjoy</strong> – Usa torretas y nanobots para defender zonas.</li>
        <li><strong>Phoenix</strong> – Controlador de fuego, se puede curar con sus propias habilidades.</li>
        <li><strong>Omen</strong> – Maestro de las sombras, confunde al enemigo con teletransportes.</li>
      </ul>
    </div>
  </section>

  <section id="mapas">
    <div class="container">
      <h2>Mapas Populares</h2>
      <ul>
        <li><strong>Ascent</strong> – Mapa con puertas mecánicas y dos sitios abiertos.</li>
        <li><strong>Bind</strong> – No tiene medio, pero tiene teletransportadores únicos.</li>
        <li><strong>Haven</strong> – Tres sitios de bomba, lo que cambia la estrategia clásica.</li>
        <li><strong>Icebox</strong> – Terreno vertical, ideal para enfrentamientos rápidos.</li>
        <li><strong>Split</strong> – Alturas y zonas cerradas, favorece a defensores.</li>
        <li><strong>Lotus</strong> – Un mapa místico con puertas giratorias y 3 sitios.</li>
      </ul>
    </div>
  </section>

  <section id="armas">
    <div class="container">
      <h2>Armas Principales</h2>
      <ul>
        <li><strong>Vandal</strong> – Rifle de disparo único y daño alto a cualquier distancia.</li>
        <li><strong>Phantom</strong> – Rifle con silenciador, ideal para fuego sostenido.</li>
        <li><strong>Operator</strong> – Rifle de francotirador, letal con un solo disparo.</li>
        <li><strong>Guardian</strong> – Rifle semiautomático preciso y económico.</li>
        <li><strong>Sheriff</strong> – Pistola potente, puede matar de un disparo a la cabeza.</li>
        <li><strong>Judge</strong> – Escopeta automática, letal a corta distancia.</li>
      </ul>
    </div>
  </section>

  <section id="curiosidades">
    <div class="container">
      <h2>Curiosidades del Juego</h2>
      <ul>
        <li>Valorant fue anunciado oficialmente en 2020 bajo el nombre clave "Project A".</li>
        <li>Los servidores de Valorant funcionan a 128 ticks, lo que mejora la precisión.</li>
        <li>Todos los agentes tienen una historia y pertenecen a regiones específicas del mundo.</li>
        <li>El juego es gratuito y financiado mediante microtransacciones cosméticas.</li>
      </ul>
    </div>
  </section>

  <section id="habilidades">
    <div class="container">
      <h2>Habilidades Populares</h2>
      <ul>
        <li><strong>Jett - Dash</strong>: Se desplaza rápidamente hacia adelante.</li>
        <li><strong>Sova - Recon Bolt</strong>: Flecha que revela enemigos en su área.</li>
        <li><strong>Phoenix - Curveball</strong>: Lanza una bola de fuego que ciega.</li>
        <li><strong>Killjoy - Lockdown (Ultimate)</strong>: Detiene a todos los enemigos en el área.</li>
      </ul>
    </div>
  </section>

  <section id="noticias">
    <div class="container">
      <h2>Noticias Recientes</h2>
      <ul>
        <li><strong>Nuevo agente revelado:</strong> Riot anuncia a su próximo controlador.</li>
        <li><strong>Actualización 8.05:</strong> Cambios a los mapas y balance de armas.</li>
        <li><strong>Evento de verano:</strong> Nuevos modos de juego y recompensas.</li>
      </ul>
    </div>
  </section>

  <section id="galeria">
    <div class="container">
      <h2>Galería de Imágenes</h2>
      <img
        src="https://images.contentstack.io/v3/assets/bltb6530b271fddd0b1/blt8d69f6e0e57f7079/646c4e8a1e1b3a124a697dc9/07012023_Val_EP7_Act1_Article_Thumb.jpg"
        alt="Nuevo agente"
        width="600"
      />
      <img
        src="https://cdn1.dotesports.com/wp-content/uploads/2022/06/10144910/valorant-2.jpg"
        alt="Partida en acción"
        width="600"
        style="margin-top: 20px"
      />
    </div>
  </section>

  <footer>
    <p>Fan page no oficial de Valorant - Creado por un fan.</p>
  </footer>
</body>
</html>
styles.css
css
Copiar código
body {
  font-family: 'Segoe UI', sans-serif;
  background-color: #0f1923;
  color: #ffffff;
  margin: 0;
  padding: 0;
  font-size: 18px;
  line-height: 1.6;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 40px 20px;
}

header {
  background-color: #ff4655;
  padding: 40px 20px;
  text-align: center;
}

header h1 {
  margin: 0;
  font-size: 3.5rem;
}

nav {
  margin-top: 15px;
}

nav a {
  color: white;
  margin: 0 20px;
  text-decoration: none;
  font-weight: bold;
  font-size: 1.2rem;
}

section {
  padding: 60px 0;
  border-bottom: 1px solid #333;
}

h2 {
  color: #ff4655;
  font-size: 2.5rem;
  margin-bottom: 20px;
}

ul {
  list-style: none;
  padding-left: 0;
  font-size: 1.2rem;
}

img {
  max-width: 100%;
  height: auto;
  margin-top: 20px;
}

footer {
  background-color: #111;
  color: #888;
  text-align: center;
  padding: 40px;
  font-size: 1rem;
}
script.js
js
Copiar código
console.log("Bienvenido a la fan page de Valorant");
2. Cómo subirlo a GitHub Pages
Crea un repositorio nuevo en GitHub con cualquier nombre (ejemplo: valorant-web).

Sube estos tres archivos (index.html, styles.css, script.js) a la raíz del repositorio.

Ve a Settings > Pages y en la sección Source selecciona la rama main y la carpeta /root.

Guarda y espera unos minutos.

GitHub te dará una URL donde estará publicada tu web, algo así:

arduino
Copiar código
https://TUUSUARIO.github.io/valorant-web/
Si quieres, puedo ayudarte a generar un .zip con estos archivos listos para que subas directamente a GitHub. ¿Quieres?











Herramientas



ChatGPT puede cometer errores. Considera verificar la información i

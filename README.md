# blog-animes
<main class="container">
  <section class="grid">
    <!-- Card 1 -->
    <article class="card">
      <div class="card-badge">1988</div>
      <div class="card-content">
        <h2>Akira</h2>
        <p>A obra-prima cyberpunk de Katsuhiro Otomo que revolucionou a animação mundial com sua complexidade visual e narrativa distópica.</p>
        <button class="like-btn" onclick="toggleLike(this)">❤️ <span>0</span></button>
      </div>
    </article>

    <!-- Card 2 -->
    <article class="card">
      <div class="card-badge">1995</div>
      <div class="card-content">
        <h2>Neon Genesis Evangelion</h2>
        <p>Mais que um anime de robôs gigantes, uma jornada psicológica profunda sobre depressão, identidade e a essência da humanidade.</p>
        <button class="like-btn" onclick="toggleLike(this)">❤️ <span>0</span></button>
      </div>
    </article>

    <!-- Card 3 -->
    <article class="card">
      <div class="card-badge">1998</div>
      <div class="card-content">
        <h2>Cowboy Bebop</h2>
        <p>Uma mistura perfeita de ficção científica, jazz, filosofia e caçadores de recompensa espaciais com muito estilo.</p>
        <button class="like-btn" onclick="toggleLike(this)">❤️ <span>0</span></button>
      </div>
    </article>

    <!-- Card 4 -->
    <article class="card">
      <div class="card-badge">1992</div>
      <div class="card-content">
        <h2>Sailor Moon</h2>
        <p>O ícone do gênero Mahou Shoujo (garotas mágicas) que conquistou o mundo com sua mensagem de amor, justiça e poder feminino.</p>
        <button class="like-btn" onclick="toggleLike(this)">❤️ <span>0</span></button>
      </div>
    </article>
  </section>
</main>

<footer>
  <p>Criado com 💜 para os amantes da era de ouro da animação japonesa.</p>
</footer>

@import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Poppins:wght@300;400;600&display=swap');

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  background-color: #0d0c1d;
  color: #e0e0e0;
  font-family: 'Poppins', sans-serif;
  line-height: 1.6;
  padding-bottom: 40px;
}

/* Header */
.blog-header {
  text-align: center;
  padding: 60px 20px;
  background: radial-gradient(circle, #1a0f30 0%, #0d0c1d 100%);
  border-bottom: 2px solid #ff007f;
}

.logo {
  font-family: 'Orbitron', sans-serif;
  font-size: 3rem;
  font-weight: 700;
  color: #00f0ff;
  text-transform: uppercase;
  letter-spacing: 4px;
  text-shadow: 0 0 10px #00f0ff, 0 0 20px #ff007f;
}

.logo span {
  color: #ff007f;
}

.subtitle {
  font-size: 1.1rem;
  color: #a0a0c0;
  margin-top: 10px;
}

/* Container & Grid */
.container {
  max-width: 1200px;
  margin: 40px auto;
  padding: 0 20px;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 30px;
}

/* Cards */
.card {
  background: #161224;
  border: 1px solid #2d1d4c;
  border-radius: 12px;
  overflow: hidden;
  position: relative;
  transition: transform 0.3s ease, border-color 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
  transform: translateY(-5px);
  border-color: #ff007f;
  box-shadow: 0 5px 20px rgba(255, 0, 127, 0.2);
}

.card-badge {
  position: absolute;
  top: 15px;
  right: 15px;
  background: #ff007f;
  color: #fff;
  font-family:

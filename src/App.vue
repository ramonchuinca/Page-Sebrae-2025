<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
<!-- Navbar personalizada -->
<nav class="navbar navbar-expand-lg custom-navbar">
  <div class="container">
    <div class="collapse navbar-collapse justify-content-center">
      <ul class="navbar-nav gap-4">
        <li class="nav-item">
          <a class="nav-link text-white fw-semibold" href="#">O que é?</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-white fw-semibold" href="#">Missões Nacionais</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-white fw-semibold" href="#">Missões Internacionais</a>
        </li>
        <li class="nav-item">
          <a class="nav-link text-white fw-semibold" href="#">Dúvidas</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

<!-- Section de imagem customizável -->
<section class="hero-section d-flex align-items-center text-white">
  <div class="container">
    <div class="row align-items-center">
      <div class="col-md-6">
        <h2 class="text-info fw-bold">MISSÕES</h2>
        <h1 class="fw-bold display-4">EMPRESARIAIS<br>SEBRAE</h1>
        <p class="mt-3">Eventos que estimulam o aprendizado, geram networking e abrem novas oportunidades de mercado.</p>
      </div>

      <div class="col-md-6 position-relative">
        <!-- Imagem principal -->
        <img src="/src/assets/" class="img-fluid main-image" alt="Missão Sebrae" />

        <!-- Forma roxa inferior esquerda -->
        <img src="forma-roxa-inferior.png" class="shape shape-bottom" alt="Forma Roxa Inferior" />

        <!-- Forma roxa superior direita -->
        <img src="forma-roxa-superior.png" class="shape shape-top" alt="Forma Roxa Superior" />
      </div>
    </div>
  </div>
</section>



    <section class="content">
      <!-- Outros elementos -->
    </section>
  </div>
</template>

<style scoped>
.navbar, .content {
  position: relative;
  z-index: 1;
}
</style>



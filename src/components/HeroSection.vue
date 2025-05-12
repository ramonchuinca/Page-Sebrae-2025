<template>
  <section class="hero-section d-flex align-items-center text-white">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-6 position-relative">
          <h2 class="text-missão">MISSÕES</h2>
          <h1 class="titulo-sobreposicao fw-bold display-1">
            EMPRESARIAIS<br />SEBRAE
          </h1>
          <p class=" texto-missão-1 mt-3">
            Eventos que estimulam o aprendizado, geram <br> networking e abrem novas
            oportunidades de<br> mercado.
          </p>
        </div>

        <div class="col-md-6 position-relative">
          <!-- Imagem principal -->
          <img
            src="../assets/images/logos/FOTO PRINCIPAL.png"
            class="img-fluid main-image"
            alt="Missão Sebrae"
          />

          <!-- Forma roxa inferior esquerda -->
          <img
            src="../assets/images/logos/Shape 2.png"
            class="shape shape-bottom"
            alt="Forma Roxa Inferior"
            
          />

          <!-- Forma roxa superior direita -->
          <img
            src="../assets/images/logos/Shape 1.png"
            class="shape shape-top"
            alt="Forma Roxa Superior"
            
          />
        </div>
      </div>
    </div>
  </section>
</template>



<script>
export default {
  name: 'HeroSection'
}
</script>



<style scoped>
.hero-section {
  min-height: 60vh;
  padding: 6rem 0;
}
.text-missão {
  color: #0ADAB9 !important;
  font-size: 4em;
  font-weight: bold;
}

.titulo-sobreposicao {
  position: relative;
  z-index: 2;
  color:white;
  text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.5);
  font-size: 7.3rem;
 text-transform: uppercase;
}

.texto-missão-1{
  position: relative;
  z-index: 2;
  color:white;
  text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.5);
  font-size: 1.3rem;
 text-transform: uppercase;
}



.main-image {
  max-width: 120%;
  left: -15%;
  position: relative;
  transform: skewX(-10deg);
}

.shape {
  position: absolute;
  z-index:-2;
  left: 32vh;
  /* width: 60%;  */
}

/* Forma roxa inferior esquerda */
.shape-bottom {
    bottom: -20px;
    left: -26vh;
    z-index: 2;
    width: 50%;
    top: 48vh;
}
/* Forma roxa superior direita */
.shape-top {
  top: -7%;
}
</style>

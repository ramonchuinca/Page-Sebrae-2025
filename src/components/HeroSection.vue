<template>
  <section class="hero-section d-flex align-items-center text-white relative top-[5vh]">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-md-6 position-relative">
          <h2 class="text-missão">MISSÕES</h2>
          <h1 class="titulo-sobreposicao fw-bold display-1">
            EMPRESARIAIS<br />
            SEBRAE
          </h1>
          <p class="texto-missão-1 mt-">
            Eventos que estimulam o aprendizado, geram <br />
            networking e abrem novas oportunidades de<br />
            mercado.
          </p>
        </div>

        <div class="w-full md:w-1/2 relative">
          <img
            src="../assets/images/logos/FOTO PRINCIPAL 02.png"
            class="w-full max-w-[100vh] h-auto object-contain mt-[-42%] ml-[32%]"
            alt="Missão Sebrae"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "HeroSection",
};
</script>

<style scoped>
.container {
  position: relative;
  top: 10vh;
  width: 100%;
}
.hero-section {
  min-height: 50vh;
  padding: 6rem 0;
}
.text-missão {
  color: #0adab9 !important;
  font-size: 4em;
  font-weight: bold;
  width: 100%;
}

.titulo-sobreposicao {
  position: relative;
  z-index: 2;
  color: white;
  text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.5);
  font-size: 7.2rem;
  text-transform: uppercase;
}

.texto-missão-1 {
  position: relative;
  z-index: 2;
  color: white;
  text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.5);
  font-size: 1.3rem;
  text-transform: uppercase;
  width: 100%;
}

</style>

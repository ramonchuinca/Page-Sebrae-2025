<template>
  <div>
    <Navbar />
    <main>
      <HeroSection />
      <MissaoEmpresarial />
      <MissoesNacionais />
      <MissoesInternacionais />  
    </main>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import HeroSection from './components/HeroSection.vue'
import MissaoEmpresarial from './components/MissaoEmpresarial.vue'
import MissoesNacionais from './components/MissoesNacionais.vue'
import MissoesInternacionais from './components/MissoesInternacionais.vue'

export default {
  components: {
    Navbar,
    HeroSection,
    MissaoEmpresarial,
    MissoesNacionais,
    MissoesInternacionais
  }
}
</script>

<style scoped>
.navbar, .content {
  position: relative;
  z-index: 1;
}
</style>



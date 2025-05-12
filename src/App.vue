<template>
  <div>
    <Navbar />
    <main>
      <HeroSection />
      <MissaoEmpresarial />
    </main>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import HeroSection from './components/HeroSection.vue'
import MissaoEmpresarial from './components/MissaoEmpresarial.vue'

export default {
  components: {
    Navbar,
    HeroSection,
    MissaoEmpresarial
  }
}
</script>



<style scoped>
.navbar, .content {
  position: relative;
  z-index: 1;
}
</style>



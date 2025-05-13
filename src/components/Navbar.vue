<template>
  <nav class="absolute top-8 w-full bg-transparent z-50">
    <div class="flex items-center justify-center md:justify-center h-16 px-4">

      <!-- Logo à esquerda (opcional, pode remover) -->
      

      <!-- Botão Hamburger (Mobile) -->
      <div class="md:hidden absolute right-16">
        <button @click="toggleMenu" id="hamburger">
          <img v-if="!menuOpen" src="https://img.icons8.com/fluent-systems-regular/2x/menu-squared-2.png" width="50" height="50" />
          <img v-else src="https://img.icons8.com/fluent-systems-regular/2x/close-window.png" width="50" height="50" />
        </button>
      </div>

      <!-- Menu de Navegação -->
      <ul
        :class="['flex-col md:flex-row flex gap-6 text-2xl text-center md:gap-10 font-semibold', menuOpen ? 'flex' : 'hidden md:flex']">
        <li>
          <a href="#" class="text-white hover:underline">O que é?</a>
        </li>
        <li>
          <a href="#" class="text-white hover:underline">Missões Nacionais</a>
        </li>
        <li>
          <a href="#" class="text-white hover:underline">Missões Internacionais</a>
        </li>
        <li>
          <a href="#" class="text-white hover:underline">Dúvidas</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script setup>
import { ref } from 'vue'
const menuOpen = ref(false)
const toggleMenu = () => {
  menuOpen.value = !menuOpen.value
}
</script>



<script>
export default {
  name: 'Navbar'
}

</script>



<style scoped>
.custom-navbar {
  background: transparent;
  padding-top: 1rem;
  font-size: 2rem;
}

.custom-navbar .nav-link {
  color: white !important;
  transition: color 0.3s ease;
}

.custom-navbar .nav-link:hover {
  color: #0ADAB9 !important; /* Azul claro Bootstrap */
}


.custom-photo {
  max-width: 100%;
  transform: skewX(-10deg);
}
</style>

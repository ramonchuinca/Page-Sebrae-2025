<template>
<nav class="absolute top-0 w-full h-16 bg-transparent z-50">
  <div class="w-full h-full flex justify-center items-center">
    <ul class="flex gap-8 md:gap-12">
      <li>
        <a href="#" class="text-white font-semibold hover:underline">O que é?</a>
      </li>
      <li>
        <a href="#" class="text-white font-semibold hover:underline">Missões Nacionais</a>
      </li>
      <li>
        <a href="#" class="text-white font-semibold hover:underline">Missões Internacionais</a>
      </li>
      <li>
        <a href="#" class="text-white font-semibold hover:underline">Dúvidas</a>
      </li>
    </ul>
  </div>
</nav>

</template>



<script>
export default {
  name: 'Navbar'
}
</script>



<style scoped>
.custom-navbar {
  background: transparent;
  padding-top: 1rem;
  font-size: 1.8rem;
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

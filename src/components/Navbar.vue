<template>
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

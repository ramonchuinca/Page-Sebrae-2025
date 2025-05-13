<template>
  <section class="relative text-center py-10 text-white mt-[120vh]">
    <div class="container mx-auto px-4 mt-[5%]">
      
      <!-- Título com ícone -->
      <div class="flex justify-center items-center gap-4 mt-[-50%]">
        <img src="../assets/images/logos/MAP internacional.png" alt="Ícone Missão" class="w-15 h-auto" />
        <h3 class="font-bold" style="font-size: 2.8rem;">Missões Internacionais</h3>
      </div>

      <!-- Cards -->
      <div class="grid grid-cols-2 md:grid-cols-4 gap-4 gap-y-8 justify-center mt-[4%]">
        <div
          v-for="(card, index) in cards"
          :key="index"
          class="rounded-2xl shadow-md text-center bg-white text-gray-800 w-[270px] mx-auto p-2"
        >
          <div class="bg-gradient-to-bl from-blue-800 to-sky-400 w-[250px] h-[164px] rounded-3xl flex items-center justify-center mx-auto">
            <img :src="card.img" class="w-40 h-auto" />
          </div>
          <div class="font-semibold uppercase text-xs mt-4">{{ card.mes }}</div>
        </div>
      </div>

      <!-- Botão com detalhe verde -->
      <div class="mt-10">
        <p class="mb-4 text-2xl font-bold">Quer se inscrever em uma missão empresarial internacional?</p>
       <div class="flex justify-center items-center mt-6">
  <a href=" https://forms.office.com/Pages/ResponsePage.aspx?id=cYIpl9cbxUqTW4it3vY2zBlze9nat6tGjosrbDWGkaBUMzQyMzQ1UlhZSTQ4QllKSDFMQ1JQMDhRVS4u" target="_blank"
     class="relative px-10 py-3 rounded-full text-white font-bold 
            bg-gradient-to-r from-[#1e1126] to-[#1d3557] border-4 border-[#00ff84] w-[280px] h-[70px] animate-border-glow flex items-center justify-center"
     style="border-radius:35px;">
    ACESSE
  </a>
</div>
      </div>
    </div>
  </section>

 <section class="FOOTERS text-white text-center py-12">
  <div class="max-w-4xl mx-auto px-4">
    <p class="text-2xl md:text-7xl font-bold mb-2">Dúvidas? Fale conosco:</p>
    <p class="text-3xl md:text-6xl font-bold">0800 570 0800</p>
  </div>
</section>

  
</template>



<script setup>
import fipan from '../assets/images/logos/LOGO FIPAN NACIONAL.png'
import Pet from '../assets/images/logos/LOGO PET NACIONAL.png'
import Intersolar from '../assets/images/logos/LOGO INTER SOLAR NACIONAL.png'
import GLASS from '../assets/images/logos/LOGO GLASS NACIONAL.png'
import BeautyFair from '../assets/images/logos/LOGO BAUTYFAIR NACIONAL.png'
import Mulher from '../assets/images/logos/LOGO MULHER NACIONAL.png'
import Forum from '../assets/images/logos/LOGO FORUM N NACIONAL.png'
import EcoExpo from '../assets/images/logos/LOGO ECO EXPO NACIONAL.png'
const cards = [
  { img: fipan, mes: 'em julho' },
  { img: Pet, mes: 'em agosto' },
  { img: Intersolar, mes: 'em agosto' },
  { img: GLASS, mes: 'em setembro' },
  { img: BeautyFair, mes: 'em setembro' },
  { img: Mulher, mes: 'em setembro' },
  { img: Forum, mes: 'em outubro' },
  { img: EcoExpo, mes: 'em outubro' }
]
</script>

<style scoped>
.glow-button {
  position: relative;
  padding: 0.75rem 2.5rem;
  font-weight: bold;
  color: white;
  background: linear-gradient(to right, #1e1126, #1d3557);
  border: none;
  width: 280px;
  height: 70px;
  border-radius: 35px;
  border-bottom: 7px solid #00ff84;
  transition: box-shadow 0.3s ease-in-out;
  z-index: 1;
}

/* Define a animação */
@keyframes border-glow {
  0%, 100% {
    box-shadow: 0 4px 0 #00ff84;
  }
  50% {
    box-shadow: 0 4px 15px 4px #00ff84;
  }
}

/* Ativa a animação apenas ao hover */
.glow-button:hover {
  animation: border-glow 1.8s infinite ease-in-out;
}

</style>

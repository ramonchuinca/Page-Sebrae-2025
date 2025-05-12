<template>
<section class="relative text-center py-10  text-white mt-[120vh]">
  <div class="container mx-auto px-4 mt-[5%]">
    
   <div class="flex justify-center items-center gap-4 mt-[-50%] ">
  <img src="../assets/images/logos/MAP internacional.png" alt="Ícone Missão" class="w-15 h-auto" />
  <h3 class="font-bold" style="font-size: 2.8rem; font-weight:bold;">Missões Internacionais</h3>
</div>


<div class="grid grid-cols-2 md:grid-cols-4 gap-4 gap-y-8 justify-center mt-[4%]">
  <div
    v-for="(card, index) in cards"
    :key="index"
    class="rounded-2xl shadow-md text-center bg-white text-gray-800 w-[270px] mx-auto p-2"
  >
    <!-- Área azul semelhante ao botão -->
    <div class="bg-gradient-to-bl from-blue-400 to-sky-400 w-[250px] h-[164px] rounded-3xl flex items-center justify-center mx-auto">
      <img :src="card.img" class="w-40 h-auto" />
    </div>

    <div class="font-semibold uppercase text-xs mt-4">{{ card.mes }}</div>
  </div>
</div>




    <div class="mt-10">
      <p class="mb-4 text-2xl font-bold">Quer se inscrever em uma missão empresarial internacional?</p>
      <a href="#" class="bg-black text-white px-6 py-2 text-lg rounded-full inline-block">ACESSE</a>
    </div>
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
/* Você pode adicionar estilos específicos aqui, se desejar */
</style>

<template>
  <section class="relative top-[108vh] text-center py-10 text-white ">
    <div class="container mx-auto px-4 mt-[3%]">
      <h2 class="font-bold text-2xl mb-6" style="font-size: 3rem">
        Confira as próximas Missões Empresariais:
      </h2>

      <div class="flex justify-center items-center gap-4 mt-[8%]">
        <img
          src="../assets/images/logos/MAP nacional.png"
          alt="Ícone Missão"
          class="w-15 h-auto"
        />
        <h3 class="font-bold" style="font-size: 2.8rem; font-weight: bold">
          Missões Nacionais
        </h3>
      </div>

      <div
        class="grid grid-cols-2 md:grid-cols-4 gap-4 gap-y-8 justify-center mt-[4%]"
      >
        <div
          v-for="(card, index) in cards"
          :key="index"
          class="rounded-3xl shadow-md text-center bg-white text-gray-800 w-[100%] h-[215px] mx-auto p-2"
        >
          <div
            class="bg-gradient-to-bl from-blue-800 to-sky-400 w-[100%] h-[165px] rounded-3xl flex items-center justify-center mx-auto"
          >
            <img :src="card.img" class="w-40 h-auto" />
          </div>

          <div class="font-semibold uppercase text-xs mt-4">{{ card.mes }}</div>
        </div>
      </div>

      <div class="mt-10">
        <p class="mb-4 text-2xl font-bold">
          Quer se inscrever em uma missão empresarial internacional?
        </p>
        <div class="flex justify-center items-center mt-6">
          <a
            href="https://ro.loja.sebrae.com.br/catalogsearch/result/?q=missão"
            target="_blank"
            class="relative px-10 py-3 rounded-full text-white font-bold bg-gradient-to-r from-[#1e1126] to-[#1d3557] w-[280px] h-[70px] flex items-center justify-center overflow-hidden"
          >
            ACESSE
            <span
              class="absolute bottom-0 left-0 w-full h-[4px] bg-[#00ff84] animate-glow-line"
            ></span>
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import fipan from "../assets/images/logos/LOGO FIPAN NACIONAL.png";
import Pet from "../assets/images/logos/LOGO PET NACIONAL.png";
import Intersolar from "../assets/images/logos/LOGO INTER SOLAR NACIONAL.png";
import GLASS from "../assets/images/logos/LOGO GLASS NACIONAL.png";
import BeautyFair from "../assets/images/logos/LOGO BAUTYFAIR NACIONAL.png";
import Mulher from "../assets/images/logos/LOGO MULHER NACIONAL.png";
import Forum from "../assets/images/logos/LOGO FORUM N NACIONAL.png";
import EcoExpo from "../assets/images/logos/LOGO ECO EXPO NACIONAL.png";
const cards = [
  { img: fipan, mes: "em julho" },
  { img: Pet, mes: "em agosto" },
  { img: Intersolar, mes: "em agosto" },
  { img: GLASS, mes: "em setembro" },
  { img: BeautyFair, mes: "em setembro" },
  { img: Mulher, mes: "em setembro" },
  { img: Forum, mes: "em outubro" },
  { img: EcoExpo, mes: "em outubro" },
];
</script>

<style scoped>
/* Você pode adicionar estilos específicos aqui, se desejar */
</style>

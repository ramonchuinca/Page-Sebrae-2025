<template>
 <section class="py-20 text-white relative top-[-8vh]">
  <div class="container  mx-auto text-center px-4">
    <h2 class="text-2xl sm:text-3xl md:text-4xl font-bold mb-6 uppercase" style="color: #20c997; font-size: 2.5rem;">
      O que é uma missão empresarial?
    </h2>
    <p class="text-lg md:text-xl mx-auto font-bold leading-relaxed max-w-4xl" style="font-size: 1.5rem; width: 100%; ">
      A Missão Empresarial é uma ação em que o Sebrae organiza e viabiliza o deslocamento de grupos com a
      finalidade de participação em agendas técnicas ou eventos (feiras, exposições e outros centros de
      referências), tanto no Brasil quanto no exterior. Essa é uma oportunidade para aprendizado e também para
      conexão com outros empreendedores da mesma área.
    </p>
  </div>



 <div class="container-1 mt-[10%]">
  <div class="row align-items-center justify-content-center">
    <div class="col-lg-5 pe-lg-4 text-end">
      <h3 class="fw-bold text-primary m-0" style="font-size: 2.5rem; line-height: 1.2;">
        Principais objetivos<br />
        de uma<br />
        Missão Empresarial<br />
        do Sebrae:
      </h3>

    </div>
    <div class="col-lg-5 ps-lg-4">
      <ul class="list-unstyled fs-5 mb-0" style="color: #1F2B80; line-height: 1.6;">
        <li class="mb-3">• Conhecer novas tecnologias, tendências e boas práticas do setor.</li>
        <li class="mb-3">• Promover troca de experiências entre empresários.</li>
        <li class="mb-3">• Facilitar acesso a novos mercados e parcerias comerciais.</li>
        <li class="mb-3">• Estimular a inovação e a competitividade dos pequenos negócios.</li>
      </ul>
    </div>
  </div>
</div>
  </section>
</template>

<script>
export default {
  name: 'MissaoEmpresarial'
}
</script>

<style scoped>

.text-teal {
  color: #20c997; /* Bootstrap teal */
  font-size: 2.5rem;
}

.container{
  position:relative;
  top: 45vh;
}

.container-1{
position: relative;
top: 50vh;
}

.text-primary {
  color: #1F2B80 !important; /* Bootstrap primary */
  
}

h2, h3 {
  line-height: 1.3;
}

ul li::marker {
  font-size: 1.5em;
}

/* Responsivo adicional: ajusta fontes e espaçamentos em telas pequenas */
@media (max-width: 576px) {
  h2 {
    font-size: 1.5rem;
  }

  h3 {
    font-size: 1.25rem;
  }

  p, ul li {
    font-size: 1rem;
  }

  .container {
    padding-left: 1rem;
    padding-right: 1rem;
  }
}

</style>

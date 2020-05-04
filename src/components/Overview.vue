<template>
  <div class="overview container">
    <div class="columns">
      <div class="column">
        <h1 class="title">Atrair clientes e alavancar o seu negócio!</h1>
        <p>
          Chatbot inteligente, responsivo e atrelado à inteligência artificial,
          que tem o intuito de solucionar 90% dos chamados dos clientes à um
          sistema de gestão simplificado que gerencia todos os processos da
          venda, utilizando QR code para liberação e envio de produtos, além da
          gestão de estoque.
        </p>
        <p class="overview-link">
          <a href="#" class="nav-link">Saiba mais...</a>
        </p>
      </div>
      <div class="column">
        <div class="overview-costumer">
          <img
            src="../assets/images/sonnar-overview.png"
            style="float: right;"
            class="has-text-left-mobile"
            alt
            srcset
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Overview"
};
</script>

<style lang="sass" scoped>
.overview
  padding: 6em 0em 6em 0em

  h1
    font-family: 'Lato', sans-serif, 'Semibold'
    font-size: 2.5em
    padding-bottom: 1.2em

    p
      font-family: 'Lato', sans-serif, 'Regular'
      font-size: 1.1em
      text-align: justify

    .overview-costumer
      float: right

    .overview-link
      padding-top: .8em

      a
        color: #0275D8 !important
        &:hover
          background-color: transparent
          border-bottom: 1px solid #0275D8
</style>

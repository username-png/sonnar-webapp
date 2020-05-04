<template>
  <div id="marketplace" class="marketplace">
    <div class="container">
      <div class="columns">
        <div class="column">
          <h1 class="title">Atrair clientes e alavancar o seu negócio!</h1>
          <p>
            Chatbot inteligente, responsivo e atrelado à inteligência
            artificial, que tem o intuito de solucionar 90% dos chamados dos
            clientes à um sistema de gestão simplificado que gerencia todos os
            processos da venda, utilizando QR code para liberação e envio de
            produtos, além da gestão de estoque.
          </p>
        </div>
        <div class="column marketplace-illustration">
          <img
            src="../assets/images/sonnar-chabot.png"
            class="marketplace-image has-text-left-mobile"
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
  name: "Marketplace"
};
</script>

<style lang="sass" scoped>
.marketplace
  padding: 6em 0em 6em 0em
  background-color: #0275D8
  color: #FFF

  .marketplace-illustration
    justify-content: center

    .marketplace-image
      padding-left: 11em

h1
  font-family: 'Lato', sans-serif, 'Semibold'
  font-size: 2.5em
  padding-bottom: 1.2em
  color: #FFF

  p
    font-family: 'Lato', sans-serif, 'Regular'
    font-size: 1.1em
    text-align: justify

    .marketplace-costumer
      float: right
</style>

<template>
  <div class="sonnar-hero">
    <Navbar />
    <div class="hero column is-two-fifths">
      <h1 class="title">Sonnar ChatBot Gestão</h1>
      <h2 class="subtitle">
        Otimização das vendas de seu negócio online, com um sistema de gestão
        simplificado que gerencia todos os processos da venda.
      </h2>
      <a class="button is-fullwidth" href="#contact">Quero Conhecer o Sonnar</a>
    </div>
  </div>
</template>

<script>
import Navbar from "./Navbar";

export default {
  name: "Hero",
  components: {
    Navbar
  }
};
</script>

<style lang="sass" scoped>
.sonnar-hero
  width: 100%
  height: 100vh
  background-image: url('../assets/images/sonnar-hero-bg.png')
  -webkit-background-size: cover
  -moz-background-size: cover
  -o-background-size: cover
  background-size: cover

  .hero
    margin: 8em auto

    h1, h2
      color: #FFF
      text-align: center

    h1
      font-family: 'Lato', sans-serif, 'Bold'
      font-size: 3.5em
      text-transform: uppercase
      padding-bottom: .6em

    h2
      font-family: 'Lato', sans-serif, 'Semibold'
      font-size: 1.5em
      padding-bottom: 1.7em
      width: 34rem
      margin: auto

    .button.is-fullwidth
      width: 65%
      margin: auto
      text-transform: uppercase
      color: #0275D8
</style>

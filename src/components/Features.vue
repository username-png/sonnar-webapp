<template>
  <div id="features" class="features">
    <div class="container">
      <h2 class="subtitle has-text-centered">Funcionalidades</h2>
      <div class="columns">
        <div class="column is-one-quarter">
          <div>
            <img src="../assets/images/sonnar-money.png" alt />
          </div>
          <div class="features-description">
            <h3>Aumente suas Vendas</h3>
            <p>
              Utilizamos de recursos de inteligência artificial para tornarmos
              nosso bot o máximo independente possível, num formato que permita
              maior disponibilidade de tempo para o lojista e maior rapidez de
              atendimento para o comprador.
            </p>
          </div>
        </div>
        <div class="column is-one-quarter">
          <div>
            <img src="../assets/images/sonnar-alert.png" alt />
          </div>
          <div class="features-description">
            <h3>Receba alertas dos seus chamados</h3>
            <p>
              Gerencie os seus chamados na nossa plataforma e receba
              notificações ou chamada via WhatSapp informando um novo chamado.
            </p>
          </div>
        </div>
        <div class="column is-one-quarter">
          <div>
            <img src="../assets/images/sonnar-ranking.png" alt />
          </div>
          <div class="features-description">
            <h3>Ranking e Bonificação</h3>
            <p>
              Gamificando nosso sistema para pontuar e ranquear os vendedores
              com melhores taxas de resposta e tempo de envio, dando destaque na
              plataforma e sanando uma necessidade exposta pelo cliente de
              precisar de confiança.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Features"
};
</script>

<style scope lang="sass">
.features
  padding: 6em 0em 6em 0em
  background-color: #E5E5E5
  color: #000

  .features-description
    background-color: #FFF
    padding: 1.2em
    width: 283px
    margin: 0 auto
    border-radius: 5px
    transform: translateY(-90px)

  h2
    font-family: 'Lato', sans-serif, 'Semibold'
    font-size: 2.5em
    padding-bottom: 1.2em
    color: #000

  .columns
    justify-content: center

    .column

      div > h3
        font-family: 'Lato', sans-serif, 'Bold'
        font-size: 18px
        text-align: center
        padding-bottom: .5em
        text-transform: capitalize
        font-weight: bold

      div > p
        font-family: 'Lato', sans-serif, 'Regular'
        font-size: 14px
        text-align: center
</style>

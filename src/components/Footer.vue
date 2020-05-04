<template>
  <footer class="footer">
    <div class="container">
      <div class="columns">
        <div class="column">
          <h4 class="title">Endereço</h4>
          <div>
            <p>Avenida Brasil,</p>
            <p>81-83 Jacovides Tower, 1st Floor</p>
            <p>1090 Brasil</p>
          </div>
        </div>
        <div class="column">
          <h4 class="title">Serviços</h4>
          <p>
            <a
              href="#"
              class="navbar-item"
              style="padding-top: none !important;"
              >Overview</a
            >
          </p>
          <p>
            <a href="#" class="navbar-item">Funcionalidades</a>
          </p>
          <p>
            <a href="#" class="navbar-item">Tecnologia</a>
          </p>
          <p>
            <a href="#" class="navbar-item">Termos & Condições</a>
          </p>
          <p>
            <a href="#" class="navbar-item">Privacidade</a>
          </p>
        </div>
        <div class="column">
          <h4 class="title">Contactos</h4>
          <p>info@sonnar.app</p>
          <p>+1 844-721-7120</p>
          <p></p>
        </div>
        <div class="column">
          <h4 class="title">Apoio</h4>
          <p>
            <img src="../assets/images/logos/shawee-logo.png" alt srcset />
          </p>
          <p>
            <img src="../assets/images/logos/olist-logo.png" alt srcset />
          </p>
          <p>
            <img src="../assets/images/logos/twilio-logo.png" alt srcset />
          </p>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer"
};
</script>

<style lang="sass" scoped>
.footer
    h4
        font-family: 'Lato', sans-serif, 'Bold'
        font-size: 1.1em
        padding-bottom: .7em
        color: #000

    .column > div
        p
            font-family: 'Lato', sans-serif, 'Regular'
            font-size: .9em

    .navbar-item
        color: #000
</style>

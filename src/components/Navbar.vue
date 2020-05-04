<template>
  <div class="container">
    <nav class="navbar" role="navigation" aria-label="main navigation">
      <div class="navbar-brand">
        <a class="navbar-item" href="/">
          <img
            src="../assets/images/logos/sonnar-logo-white.png"
            width="55"
            height="57"
          />
        </a>

        <a
          role="button"
          class="navbar-burger burger"
          aria-label="menu"
          aria-expanded="false"
          data-target="navbarBasicExample"
        >
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
          <span aria-hidden="true"></span>
        </a>
      </div>

      <div id="navbarBasicExample" class="navbar-menu">
        <div class="navbar-start">
          <a class="navbar-item" href="#overview">Overview</a>
          <a class="navbar-item" href="#features">Funcionalidades</a>
          <a class="navbar-item" href="#contact">Contacto</a>
        </div>

        <div class="navbar-end">
          <a
            class="navbar-item login"
            href="https://sonnar-dashboard.netlify.app/"
            target="_blank"
            >Entrar</a
          >
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar"
};
</script>

<style lang="sass" scoped>
.navbar
  background-color: transparent
  padding-top: 40px

  .navbar-item img
    max-height: none

  .navbar-item
    color: #FFF
    text-transform: uppercase

  .navbar-end
    .login
      &:hover
        font-weight: bold
        background-color: transparent
        border-bottom: none !important

    .navbar-item
      &:hover
        background-color: transparent
        border-bottom: 1px solid #FFF

  .navbar-start
    margin: auto

    .navbar-item
      color: #FFF
      text-transform: uppercase

      &:hover
        background-color: transparent
        border-bottom: 1px solid #FFF
</style>

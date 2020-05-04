<template>
  <div id="contact" class="contact">
    <div class="container">
      <div class="columns">
        <div class="column">
          <h1 class="title">Contacto</h1>
          <p>Alguma questão ou dúvida? Conte-nos como podemos ajudar você.</p>
        </div>
        <div class="column is-two-fifths contact-form">
          <form action class method="post">
            <div class="columns">
              <div class="column">
                <div class="field">
                  <div class="control">
                    <input
                      class="input"
                      type="text"
                      placeholder="Primeiro Nome"
                    />
                  </div>
                </div>
              </div>
              <div class="column">
                <div class="field">
                  <div class="control">
                    <input
                      class="input"
                      type="text"
                      placeholder="Segundo Nome"
                    />
                  </div>
                </div>
              </div>
            </div>
            <div class="field">
              <div class="control">
                <input class="input" type="text" placeholder="Celular" />
              </div>
            </div>
            <div class="control">
              <textarea
                rows="3"
                style="margin-top: 22px;"
                class="textarea"
                placeholder="Mensagem"
              ></textarea>
            </div>
            <button
              style="margin-top: 22px;"
              class="button is-link is-uppercase is-medium"
            >
              Enviar
            </button>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact"
};
</script>

<style lang="sass" scoped>
.contact
  padding: 6em 0em 6em 0em
  background-color: #FFF
  color: #000

  h1
    font-family: 'Lato', sans-serif, 'Semibold'
    font-size: 2.5em
    padding-bottom: 1.2em
    color: #000

    p
      font-family: 'Lato', sans-serif, 'Regular'
      font-size: 1.1em
      text-align: justify

    .contact-form
      float: right

      .input
        border-color: #333333
        padding: 25px

        .textarea
          border-color: #333333
          padding: 25px
          margin-top: 25px

        button
          margin-top: 16px
</style>

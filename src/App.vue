<template lang="pug">
  #app
    img(src="./assets/logo.png")
    h1(class="title") Registro estación Platzi
    form(action="/new_movie", method="POST")
      p
        |  Nombre
        input(type="text", name="title", value="")
        |  Apellido
        input(type="text", name="year", value="")
        |  Cargo
        input(type="text", name="imdb", value="")
      input(class="button-env" type="submit", value="Enviar")
</template>

<script>
export default {
  name: 'app',

  data () {
    return {
      msg: 'Registro estación Platzi'
    }
  }
}
</script>

<style lang="scss">
  @import './scss/main.scss'
</style>

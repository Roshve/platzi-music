<template lang="pug">
  #app
    div(class="container")
      img(src="./assets/logo.png")
      h1(class="title") Registro estación Platzi
      form(action="/new_movie", method="POST")
        |
        label Nombre
        input(type="text", name="Nombre", value="")
        |
        label Apellido
        input(type="text", name="Apellido", value="")
        |
        label Cargo
        input(type="text", name="Cargo", value="")
        |
        input(class="button-env" type="submit", value="ENVIAR")
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

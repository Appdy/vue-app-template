<template lang="pug">
  #app
    img(alt="Vue logo" src="./assets/logo.png")
    HelloWorld(msg="Welcome to Your Vue.js App")
</template>

<script>
import HelloWorld from "./components/HelloWorld"

export default {
  name: "app",
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss" scoped>
  @import "styles/style.scss"
</style>

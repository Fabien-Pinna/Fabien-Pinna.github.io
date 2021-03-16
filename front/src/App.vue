<template>
  <Nav />
  <router-view />
</template>

<script>
import Nav from "./components/Nav/Nav";
export default {
  name: "App",
  components: {
    Nav
  }
}
</script>

<style lang="scss">
@import "./assets/styles/reset.scss";
</style>

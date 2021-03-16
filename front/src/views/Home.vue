<template>
  <div class="home">
    <img alt="webinfab logo" src="../assets/img/logo.jpg" />
    <Header/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header/Header";

export default {
  name: "Home",
  components: {
    Header
  }
};
</script>

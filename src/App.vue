<script>
import Title from "./components/AppTitle.vue";
import Jumbo from "./components/AppHero.vue";

export default {
  data() {
    return {

    }
  },
  components: {

    Title,
    Jumbo
  }
}

</script>

<template>

  <Title class="title"></Title>

  <Jumbo></Jumbo>

</template>

<style>

.title{
  position: fixed;
  top: 0;
  left: 0;

  width: 100%;

  background-color: #242424;

  box-shadow: 10px 15px 20px rgba(0, 0, 0, 0.5);

  z-index: 2;
}

</style>
<script>
//qui va il codice JavaScript

import HelloWorld from "./components/HelloWorld.vue";
import Jumbotron from "./components/Jumbotron.vue";

export default {
  components: {
    HelloWorld,
    Jumbotron,
  },
};
</script>

<template>
  <section>
    <!--qui va il nostro HTML-->
    <HelloWorld></HelloWorld>
  </section>
  <section>
    <!--qui va il nostro HTML-->
    <Jumbotron></Jumbotron>
  </section>
</template>

<style scoped>
/*qui aggiungeremo CSS*/
</style>

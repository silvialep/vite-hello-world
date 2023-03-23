<script>

import AppTitle from "./components/AppTitle.vue";
import AppHero from "./components/AppHero.vue";

export default {
  data() {
    return {

    }
  },

  components: {
    AppTitle,
    AppHero,
  },

  
  
}


</script>

<template>
  <div>
    <AppTitle></AppTitle>
    <section>
      <AppHero></AppHero>
    </section>

  </div>
</template>

<style>
</style>


/*
Create un nuovo progetto utilizzando Vite: aiutatevi con le slide per ripercorrere i vari passaggi dell'installazione come visti a lezione.
Create e utilizzate un componente AppTitle, il quale contiene un titolo che recita "La mia prima app con Vite!"
Bonus:
Creare un secondo componente AppHero, che visualizza un jumbotron.
*/
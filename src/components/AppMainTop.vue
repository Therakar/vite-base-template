<script>
import AppHero from './AppHero.vue'; //importo l'hero
import AppCatalogue from './AppCatalogue.vue'; //importo l'hero
export default {
  name: 'AppMainTop',
  components: {
    AppHero,
    AppCatalogue
  }
}
</script>

<template>
  <main>
    <AppHero/>
    <AppCatalogue/>
  </main>
</template>

<style scoped>
  main{
    background-color: var(--darker-secondary-color);
  }
  .container{
    padding: 50px;
    max-width: 81.25rem;
    /* debug */
    color: #fff;   
  }
</style>
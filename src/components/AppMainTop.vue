<script>
import AppHero from './AppHero.vue'; //importo l'hero
export default {
  name: 'AppMainTop',
  components: {
    AppHero
  }
}
</script>

<template>
  <main>
    <AppHero/>
    <div class="container">
      <p>-->Qui ci vanno le card con i fumetti&lt--</p>
    </div>
   
  </main>
</template>

<style scoped>
  main{
    background-color: var(--darker-secondary-color);
  }
  .container{
    padding: 50px;
    /* debug */
    color: #fff;   
  }
</style>
<script> 
// importo i componenti
import AppHeader from './components/AppHeader.vue';
import AppMainTop from './components/AppMainTop.vue';
import AppMainBottom from './components/AppMainBottom.vue';
import AppFooterTop from './components/AppFooterTop.vue';
import AppFooterBottom from './components/AppFooterBottom.vue';

//registro i componenti
export default {
  components: {
    AppHeader,
    AppMainTop,
    AppMainBottom,
    AppFooterTop,
    AppFooterBottom
  }
}
</script>

<!-- inserisco i componenti nell'html -->
<template>
  <AppHeader/>
  <AppMainTop/>
  <AppMainBottom/>
  <AppFooterTop/>
  <AppFooterBottom/>
</template>


<style lang="scss">
@import './style/global.scss'; // importo il documento css principale nel quale sono importti tutti gli altri documenti css più specifici
</style>

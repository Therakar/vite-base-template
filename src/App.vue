<script>
import AppHeader from './components/AppHeader.vue';
import AppMainTop from './components/AppMainTop.vue';
import AppMainBottom from './components/AppMainBottom.vue';
import AppFooterTop from './components/AppFooterTop.vue';
import AppFooterBottom from './components/AppFooterBottom.vue';


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

<template>
  <AppHeader/>
  <AppMainTop/>
  <AppMainBottom/>
  <AppFooterTop/>
  <AppFooterBottom/>
</template>


<style lang="scss">
@import './style/global.scss';
</style>

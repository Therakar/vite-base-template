<script>
import AppHeader from './components/AppHeader.vue';
import AppMainTop from './components/AppMainTop.vue';
import AppMainBottom from './components/AppMainBottom.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppMainTop,
    AppMainBottom,
    AppFooter
  }
}
</script>

<template>
  <AppHeader/>
  <AppMainTop/>
  <AppMainBottom/>
  <AppFooter/>
</template>


<style lang="scss">
@import './style/global.scss';
</style>

<script>
import AppFooterLists from './AppFooterTopComponents/AppFooterLists.vue';
export default {
  name: 'AppFooterTop',
  components: {
    AppFooterLists,
  }
}
</script>

<template>
  <footer >
    <AppFooterLists/>
  </footer>
</template>

<style lang="scss" scoped>
  footer{
    background-image: url(./assets/footer-bg.jpg);
    background-size: cover;
    
  }
</style>
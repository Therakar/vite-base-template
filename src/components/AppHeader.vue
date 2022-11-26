<!-- HEADER -->
<script>
import AppLogo from './AppHeaderComponents/AppLogo.vue'; //importo il logo 
import AppHeaderNav from './AppHeaderComponents/AppHeaderNav.vue'; //importo il nav 
export default {
  name: 'AppHeader',
  components: {
    AppLogo, //registro il logo
    AppHeaderNav, //registro il nav
  },
}
</script>

<template>
  <header class="container flex sp-bw al-cnt">
    <AppLogo/> <!--inserisco il logo nell'html-->
    <AppHeaderNav/> <!--inserisco il nav nell'html-->
  </header>
</template>

<style lang="scss" scoped>
  .container{ 
    padding: 10px 0;
    }
</style>
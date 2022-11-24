<!-- HEADER -->
<script>
import AppIcon from './AppIcon.vue';
import AppHeaderNav from './AppHeaderNav.vue';
export default {
  name: 'AppHeader',
  components: {
    AppIcon,
    AppHeaderNav,
  },
}
</script>

<template>
  <header class="container flex sp-bw al-cnt">
    <AppIcon/>
    <AppHeaderNav/>
  </header>
</template>

<style scoped>
  .container{
    padding: 10px;
    }
</style>
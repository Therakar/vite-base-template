<script>
import AppIcon from './AppIcon.vue';
export default {
  name: 'AppHeader',
  components: {
    AppIcon,
  }
}
</script>

<template>
  <header class="container">
    <AppIcon/>
  </header>
</template>

<style scoped>
  .container{
    padding: 20px;
    }
</style>
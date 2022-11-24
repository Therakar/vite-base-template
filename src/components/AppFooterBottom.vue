<script>
import AppButton from './AppButton.vue';
import AppSocials from './AppSocials.vue';
export default {
  name: 'AppFooterBottom',
  components: {
    AppButton,
    AppSocials
  }
}
</script>

<template>
  <footer>
    <div class="container flex sp-bw al-cnt">
      <AppButton/>
      <AppSocials/>
    </div>
  </footer>
</template>

<style scoped>
footer{
  background-color: var(--secondary-color);
}
.container{
    padding: 35px 0;
        /* debug */
        height: 120px; 
        
    }
</style>
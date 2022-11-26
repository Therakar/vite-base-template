<script>
import AppSignUpButton from './AppFooterBottomComponents/AppSignUpButton.vue';
import AppSocials from './AppFooterBottomComponents/AppSocials.vue';
export default {
  name: 'AppFooterBottom',
  components: {
    AppSignUpButton,
    AppSocials
  }
}
</script>

<template>
  <footer>
    <div class="container flex sp-bw al-cnt">
      <AppSignUpButton/>
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
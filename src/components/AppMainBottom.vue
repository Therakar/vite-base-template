<script>
export default {
  name: 'AppMainBottom',
}
</script>

<template>
  <main class="container flex sp-bw al-cnt">
    <ul class="flex">
      <li class="flex al-cnt">
        <img src="../assets/buy-comics-digital-comics.png" alt="">
        <span>DIGITAL COMICS</span>
      </li>
      <li class="flex al-cnt">
        <img src="../assets/buy-comics-merchandise.png" alt="">
        <span>DC MERCHANDISE</span>
      </li>
      <li class="flex al-cnt">
        <img src="../assets/buy-comics-subscriptions.png" alt="">
        <span>SUBSCRIPTION</span>
      </li>
      <li class="flex al-cnt">
        <img src="../assets/buy-comics-shop-locator.png" alt="">
        <span>COMIC SHOP LOCATOR</span>
      </li>
      <li class="flex al-cnt">
        <img src="../assets/buy-dc-power-visa.svg" alt="">
        <span>DC POWER VISA</span>
      </li>
    </ul>
  </main>
</template>

<style lang="scss" scoped>
  .container{
    padding: 50px;
    background-color: var(--primary-color);
        
    }
    ul{
      width: 100%;
      li{
        width:calc(100% /5); 

        img{
         max-height: 50px;
         max-width: 50px;
        
        }
        span{
          padding-left: 10px;
          font-size: 13px; 
         
          color: #fff;
        }
      
      }
    }
    
    
</style>
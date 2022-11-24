<script>
export default {
  name: 'AppFooterTop',
}
</script>

<template>
  <footer >
   <div class="container flex">
    <div class="col">
      <h3>DC COMICS</h3>
      <ul>
        <li>Character</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>Games</li>
        <li>Videos</li>
        <li>News</li>
      </ul>

      <h3>SHOP</h3>
      <ul>
        <li>Shop DC</li>
        <li>Shop DC Collectibles</li>
      </ul>
    </div>
    <div class="col">
      <h3>DC</h3>
      <ul>
        <li>Terms Of Use</li>
        <li>Privacy Policy (New)</li>
        <li>Ad Choices</li>
        <li>Advertising</li>
        <li>Jobs</li>
        <li>Subscriptions</li>
        <li>Talent Workshop</li>
        <li>CPSC Certificates</li>
        <li>Ratings</li>
        <li>Shop Help</li>
        <li>Contact Us</li>
      </ul>
    </div>
    <div class="col">
      <h3>SITES</h3>
      <ul>
        <li>DC</li>
        <li>MAD Magazine</li>
        <li>DC Kids</li>
        <li>DC Universe</li>
        <li>DC Power Visa</li>
      </ul>
    </div>
   </div>
  </footer>
</template>

<style lang="scss" scoped>
  footer{
    background-image: url(../assets/footer-bg.jpg);
    background-size: cover;
  }
  .container{
      padding: 40px 0 ;
  }

  .col{
    margin-right: 30px;
  }

  ul{
    margin-bottom: 20px;
    li{
        color: var(--secondary-color-clear);
        margin-bottom: 5px;
      }
  }
  
  h3{
    margin: 10px 0;
    color: #fff;
  }

  
  
</style>
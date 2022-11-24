<script>

export default {
  name: 'AppSocials',
}
</script>

<template>
  <div>
    <ul class="flex al-cnt">
        <li><a href="#">FOLLOW US</a></li>
        <li><img src="../assets/footer-facebook.png" alt=""></li>
        <li><img src="../assets/footer-twitter.png" alt=""></li>
        <li><img src="../assets/footer-youtube.png" alt=""></li>
        <li><img src="../assets/footer-pinterest.png" alt=""></li>
        <li><img src="../assets/footer-periscope.png" alt=""></li>

    </ul>
  </div>
</template>

<style lang="scss" scoped>
footer{
  background-color: var(--secondary-color);
}
.container{
    padding: 50px 0;
        /* debug */
        height: 120px; 
    }
    a{
        display: inline-block;
        padding: 15px 15px;
        text-decoration: none;
        color:var(--primary-color);
        font-size: 16px;
    }

    li{
        margin-right: 10px;

        img{
            max-width: 30px;
        }
    }
</style>
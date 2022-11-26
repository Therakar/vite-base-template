<script>
    
    export default {
    name: 'AppFooterLists',
    data() {
    return {
        // lista di elementi che rappresentano i valori da inserire nei li che compongono le liste del nav top
        dcComics: [
            'Character',
            'Comics',
            'Movies',
            'TV',
            'Games',
            'Videos',
            'News'
        ],
        shops : [
            'Shop DC',
            'Shop DC Collectibles'
        ],
        dc: [
            'Terms Of Use',
            'Privacy Policy (New)',
            'Ad Choices',
            'Advertising',
            'Jobs',
            'Subscriptions',
            'Talent Workshop',
            'CPSC Certificates',
            'Ratings',
            'Shop Help',
            'Contact Us'
        ],
        sites: [
            'DC',
            'MAD Magazine',
            'DC Kids',
            'DC Universe',
            'DC Power Visa'
        ]

    }
  }
}
</script>

<template>
    <div class="container flex">
    <div class="col">

      <h3>DC COMICS</h3>
      <ul>
        <li v-for="elm in dcComics">{{elm}}</li>
      </ul>

      <h3>SHOP</h3>
      <ul>
        <li v-for="shop in shops">{{shop}}</li>
      </ul>

    </div>

    <div class="col">
      <h3>DC</h3>
      <ul>
        <li v-for="elm in dc">{{elm}}</li>
      </ul>
    </div>
    <div class="col">
      <h3>SITES</h3>
      <ul>
        <li v-for="site in sites">{{site}}</li>
      </ul>
    </div>
   </div>
    
</template>



<style lang="scss" scoped>
    .container{
      padding: 40px 0 ;
  
    }

  .col{
    margin-right: 30px;
        
        h3 {
        margin: 10px 0;
        color: #fff;
        }

        ul {
            margin-bottom: 20px;

            li {
                color: var(--secondary-color-clear);
                margin-bottom: 5px;
                font-size: 13px;

                &:hover {
                    cursor: pointer;
                    color: #fff;
                }
            }
        }
    }
  
  
</style>
<script>
export default {
  name: 'AppHeaderNav',
  data() {
    return {
        // lista di elementi che rappresentano i valori da inserire nei link che compongono il nav
        links: [
            'CHARACTERS',
            'COMICS',
            'MOVIES',
            'TV',
            'GAMES',
            'COLLECTIBLES',
            'VIDEOS',
            'FANS',
            'NEWS',
            'SHOP'
        ]
    }
  }
}
</script>

<template>
  <nav>
    <ul class="flex">
        <li v-for="link in links"><a href="#">{{link}}</a></li> <!-- li con al suo interno un v-for che cicla sull'array di link -->
    </ul>
</nav>
</template>

<style lang="scss" scoped>
  ul{
    list-style: none;

    a{
        display: inline-block;
        padding: 15px 15px;
        text-decoration: none;
        color: #000;
    }
  }
</style>
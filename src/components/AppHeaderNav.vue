<script>
export default {
  name: 'AppHeaderNav',
  data() {
    return {
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
        <li v-for="link in links"><a href="">{{link}}</a></li>
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
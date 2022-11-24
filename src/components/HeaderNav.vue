<script>
export default {
  name: 'HeaderNav',
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
  <nav class="main-nav">
            <ul>
                <li v-for="link in links"><a href="#">{{link}}</a></li>
            </ul>
        </nav>
</template>

<style lang="scss" scoped>
.main-nav {
        ul {
            display: flex;
            list-style: none;
            justify-content: center;
            a {
                display: inline-block;
                padding: 20px 10px;
                text-decoration: none;
                color: #000;
                font-weight: bold;
                &.active {
                    color: var(--primary-color);
                }
            }
        }
    }
</style>
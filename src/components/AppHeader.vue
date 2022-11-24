<script>
import HeaderNav from './HeaderNav.vue';


export default {
  name: 'AppHeader',
  components: {
    HeaderNav
  },
  data() {
    return {
      
    }
  }
}
</script>

<template>
  <header>
    <div class="container">
      <img src="../assets/dc-logo.png" alt="dc-logo">
      <HeaderNav/>
    </div>
  </header>
</template>

<style lang="scss" scoped></style>

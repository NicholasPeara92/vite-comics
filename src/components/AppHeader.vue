<script>
import HeaderNav from "./HeaderNav.vue";

export default {
  name: "AppHeader",
  components: {
    HeaderNav,
  },
  data() {
    return {};
  },
};
</script>

<template>
  <header>
    <div class="container">
      <img src="../assets/dc-logo.png" alt="dc-logo" />
      <HeaderNav />
    </div>
  </header>
</template>

<style lang="scss" scoped>
header {
  height: 7.5rem;
  .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px 10px;

    img {
      max-width: 5rem;
    }
  }
}
</style>

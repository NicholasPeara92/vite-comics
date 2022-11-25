<script>
export default {
  name: "HeaderNav",
  data() {
    return {
      links: [
        "CHARACTERS",
        "COMICS",
        "MOVIES",
        "TV",
        "GAMES",
        "COLLECTIBLES",
        "VIDEOS",
        "FANS",
        "NEWS",
        "SHOP",
      ],
    };
  },
};
</script>

<template>
  <nav class="main-nav">
    <ul>
      <li v-for="link in links">
        <a href="#">{{ link }}</a>
      </li>
    </ul>
  </nav>
</template>

<style lang="scss" scoped>
.main-nav {
  ul {
    display: flex;
    list-style: none;
    justify-content: center;
    li {
      position: relative;
      &:nth-child(2) {
        color: var(--primary-color);
      }
      &:nth-child(2)::after {
        content: "";
        position: absolute;
        bottom: -30px;
        right: 0px;
        height: 6px;
        width: 100%;
        background-color: var(--primary-color);
      }
      a {
        display: inline-block;
        padding: 20px 10px;
        text-decoration: none;
        color: inherit;
        font-weight: bold;
        &.active {
          color: var(--primary-color);
        }
      }
    }
  }
}
</style>

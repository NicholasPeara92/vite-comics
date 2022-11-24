<script>
export default {
  name: 'AppPrefooter',
  data() {
    return {
      links: [
        'DIGITAL COMICS',
        'DC MERCHANDISE',
        'SUBSCRIPTION',
        'COMIC SHOP LOCATOR',
        'DC POWER VISA',
      ]
    }
  }
}
</script>

<template>
  <section>
    <div class="container">
      <ul>
        <li>
          <img src="../assets/buy-comics-digital-comics.png" alt="">
          <a href="#">DIGITAL COMICS</a>
        </li>
        <li>
          <img src="../assets/buy-comics-merchandise.png" alt="">
          <a href="#">DC MERCHANDISE</a>
        </li>
        <li>
          <img src="../assets/buy-comics-subscriptions.png" alt="">
          <a href="#">SUBSCRIPTION</a>
        </li>
        <li>
          <img src="../assetS/buy-comics-shop-locator.png" alt="">
          <a href="#">COMIC SHOP LOCATOR</a>
        </li>
        <li>
          <img src="../assets/buy-dc-power-visa.svg" alt="">
          <a href="#">DC POWER VISA</a>
        </li>
      </ul>
    </div>
  </section>
</template>

<style lang="scss" scoped>
section {
  background-color: var(--primary-color);
  height: 9.6875rem;
  display: flex;
  align-items: center;
}
.container {
  display: flex;
  ul {
    display: flex;
    list-style: none;
    justify-content: space-between;
    margin: 0 20px;
    li {
      display: flex;
      align-items: center;
      margin: 0 10px;
      img {
        height: 3.4375rem;
  
      }
      a {
        display: inline-block;
        padding: 20px 10px;
        text-decoration: none;
        color: white;
        font-weight: bold;
      }
    }
  }
}
</style>
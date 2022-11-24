<script>
export default {
  name: 'AppFooter',
  data() {
    return {
      
    }
  }
}
</script>

<template>
  <footer>
    <div class="bg">
      <div class="container">
        <div class="col">
          <ul>
            <li><h3>DC COMICS</h3></li>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Comics</a></li>
            <li><a href="#">Movies</a></li>
            <li><a href="#">TV</a></li>
            <li><a href="#">Games</a></li>
            <li><a href="#">Videos</a></li>
            <li><a href="#">News</a></li>
          </ul>
          <ul>
            <li><h3>SHOP</h3></li>
            <li><a href="#">Shop DC</a></li>
            <li><a href="#">Shop DC Collectibles</a></li>
          </ul>
        </div>
        <div class="col">
          <ul>
            <li><h3>DC</h3></li>
            <li><a href="#">Terms Of Use</a></li>
            <li><a href="#">Privacy Policy (New)</a></li>
            <li><a href="#">Ad Choices</a></li>
            <li><a href="#">Advertising</a></li>
            <li><a href="#">Jobs</a></li>
            <li><a href="#">Subscriptions</a></li>
            <li><a href="#">Talent Workshops</a></li>
            <li><a href="#">CPSC Certificates</a></li>
            <li><a href="#">Ratings</a></li>
            <li><a href="#">Shop Help</a></li>
            <li><a href="#">Contact Us</a></li>
          </ul>
        </div>
        <div class="col">
          <ul>
            <li><h3>SITES</h3></li>
            <li><a href="#">DC</a></li>
            <li><a href="#">MAD Magazine</a></li>
            <li><a href="#">DC Kids</a></li>
            <li><a href="#">DC Universe</a></li>
            <li><a href="#">DC Power Visa</a></li>
          </ul>
        </div>
      </div>
    </div>
    <div id="copyright" class="container">
      <button><a href="#">SIGN-UP NOW</a></button>
      <div class="follow">
        <ul>
          <li>FOLLOW US</li>
          <li><img src="../assets/footer-facebook.png" alt=""></li>
          <li><img src="../assets/footer-twitter.png" alt=""></li>
          <li><img src="../assets/footer-youtube.png" alt=""></li>
          <li><img src="../assets/footer-pinterest.png" alt=""></li>
          <li><img src="../assets/footer-periscope.png" alt=""></li>
        </ul>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
footer {
  background-color: var(--tertiary-color);
  height: 30rem;
  .bg {
    background-image: url(../assets/footer-bg.jpg);
    height: 23.125rem;
    .container {
      height: 100%;
      background-repeat: no-repeat;
      background-position: right;
      display: flex;
      &:first-child {
        background-image: url(../assets/dc-logo-bg.png);
        .col {
          margin: 0 20px;
          ul {
            list-style: none;
            color: white;
            li {
              margin-bottom: 5px;
              font-size: 14px;
              &:first-child {
                margin: 20px 0;
              }
              a {
                text-decoration: none;
                color: var(--quaternary-color);
              }
            }
          }
        }
      }
    }
  }
  #copyright {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 6.875rem;
    button {
      background-color: transparent;
      border: 2px solid var(--primary-color);
      padding: 10px;
      a {
        text-decoration: none;
        color: white;
        font-weight: bold;
      }
    }
    ul {
      list-style: none;
      display: flex;
      align-items: center;
      justify-content: space-between;
      li {
        margin: 0 10px;
        color: var(--primary-color);
        font-weight: bold;
        &:last-child {
          margin-right: 0;
        }
      }
    }
  }
}
</style>


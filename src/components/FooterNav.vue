<template>
  <nav>
    <div class="container">
      <ul>
        <h2>DC COMICS</h2>
        <li>
          <a href="">
            Characters
          </a>
        </li>
        <li>
          <a href="">
            Comics
          </a>
        </li>
        <li>
          <a href="">
            Movies
          </a>
        </li>
        <li>
          <a href="">
            TV
          </a>
        </li>
        <li>
          <a href="">
            Games
          </a>
        </li>
        <li>
          <a href="">
            Videos
          </a>
        </li>
        <li>
          <a href="">
            News
          </a>
        </li>
      </ul>

      <ul>
        <h2>SHOP</h2>
        <li>
          <a href="">
            Shop DC
          </a>
        </li>
        <li>
          <a href="">
            Shop DC Collectibles
          </a>
        </li>
      </ul>

      <ul>
        <h2>DC</h2>
        <li>
          <a href="">
            Terms Of Use
          </a>
        </li>
        <li>
          <a href="">
            Privacy Policy (New)
          </a>
        </li>
        <li>
          <a href="">
            Ad Choices
          </a>
        </li>
        <li>
          <a href="">
            Advertising
          </a>
        </li>
        <li>
          <a href="">
            Jobs
            </a>
        </li>
        <li>
          <a href="">
            Subscriptions
          </a>
        </li>
        <li>
          <a href="">
            Talent Workshops
          </a>
        </li>
        <li>
          <a href="">
            CPSC Certificates
          </a>
        </li>
        <li>
          <a href="">
            Ratings
          </a>
        </li>
        <li>
          <a href="">
            Shop Help
          </a>
        </li>
        <li>
          <a href="">
            Contact Us
          </a>
        </li>
      </ul>

      <ul>
        <h2>SITES</h2>
        <li>
          <a href="">
            DC
          </a>
        </li>
        <li>
          <a href="">
            MAD Magazine
          </a>
        </li>
        <li>
          <a href="">
            DC Kids
          </a>
        </li>
        <li>
          <a href="">
            DC Universe
          </a>
        </li>
        <li>
          <a href="">
            DC Power Visa
          </a>
        </li>
      </ul>
      <img src="..\assets\dc-logo-bg.png" alt="">
    </div>

  </nav>
</template>

<script>
export default {
  name: 'FooterNav'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
nav {
  height: 400px;
  color: white;
  background-image: url('../assets/footer-bg.jpg');
  padding: 25px 0;
  overflow: hidden;
    .container {
      height: 100%;
      display: flex;
      flex-direction: column;
      flex-wrap: wrap;
}
}

ul  {
  margin: 15px 0;
  margin-right: 50px;
  display: inline-block;
  list-style: none;
}

li {
  margin: 5px 0;
    a {
      color: grey;
      text-decoration: none;
      display: inline-block;
    }
}

img {
    position: relative;
    bottom: 120px
}

</style>

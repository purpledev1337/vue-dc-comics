<template>
  <header class="container">
    <img src="..\assets\dc-logo.png" alt="">
    <ul>
      <li>
        <a href="">
          Characters
        </a>
      </li>
      <li class="active">
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
          Collectibles
        </a>
      </li>
      <li>
        <a href="">
          Videos
        </a>
      </li>
      <li>
        <a href="">
          Fans
        </a>
      </li>
      <li>
        <a href="">
          News
        </a>
      </li>
      <li>
        <a href="">
          Shop
        </a>
      </li>
    </ul>
  </header>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header {
  height: 150px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

li {
  display: inline-block;
  margin: 0 15px;
  line-height: 150px;
    a {
      text-decoration: none;
      text-transform: uppercase;
    }
  &.active {
      border-bottom: 5px solid rgb(2,130,249);
    }
}
</style>

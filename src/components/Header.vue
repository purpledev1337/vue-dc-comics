<template>
  <header class="container">
    <img src="..\assets\dc-logo.png" alt="">
    <ul>
      <li :class="link.here ? 'active' : ''" v-for="link, i in links" :key="i" @click="navClick(i)" >
        <a href="link.url">
          {{link.text}}
        </a>
      </li>
    </ul>
  </header>
</template>

<script>
export default {
  name: 'Header',
  data() {
    return {
      links: [
        {
          text: "Characters",
          url: "#",
          here: false
        },
        {
          text: "Comics",
          url: "#",
          here: true
        },
        {
          text: "Movies",
          url: "#",
          here: false
        },
        {
          text: "TV",
          url: "#",
          here: false
        },
        {
          text: "Games",
          url: "#",
          here: false
        },
        {
          text: "Collectibles",
          url: "#",
          here: false
        },
        {
          text: "Videos",
          url: "#",
          here: false
        },
        {
          text: "Fans",
          url: "#",
          here: false
        },
        {
          text: "News",
          url: "#",
          here: false
        },
        {
          text: "Shop",
          url: "#",
          here: false
        }
      ]
    }
  },
  methods: {
    navClick: function(index) {
      for (let i = 0; i < this.links.length; i++) {
        this.links[i].here = false;
      }
      this.links[index].here = true;
    }
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
  height: 150px;
  display: inline-block;
  margin: 0 15px;
  font-size: 0.8em;
  font-weight: 900;

    a {
      display: inline-block;
      line-height: 150px;
      text-decoration: none;
      text-transform: uppercase;
    }

    &.active {
      border-bottom: 5px solid rgb(2,130,249);
    }
}
</style>

<template>
    <main>
      <div class="container">
        --> Content goes here
      </div>
    </main>
</template>

<script>
export default {
  name: 'Main',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
main {
  padding: 70px 0;
  color: white;
  background-color: black;
  // temporary fix to the active border in header
  margin-top: 3px;
}

</style>

<template>
  <div id="container">
      <img src="../assets/img/jumbotron.jpg" alt="">
  </div>
</template>

<script>
export default {
  name: 'Jumbotron'
}
</script>

<style lang="scss" scoped>

  #container {
    width: 100%;
    height: 400px;

    img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      object-position: 0 0 ;
    }
  }

</style>
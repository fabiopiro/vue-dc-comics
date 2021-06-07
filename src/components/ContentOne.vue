<template>
  <div>
      <div class="container">
        <h2>Content goes here</h2>
      </div>
  </div>
</template>

<script>

export default {
  name: 'ContentOne'
}
</script>

<style lang="scss" scoped>
    div {
        height: 100px;
        background-color: black;

    }

    .container {
        width: 70%;
        margin: auto;
        display: flex;
        align-items: center;
    }

    h2 {
        color: white;
    }
</style>
<template>
  <div>
    <div class="container">
      <div id="logo">
          <img src="../assets/img/dc-logo.png" alt="logo">
      </div>
      <ul>
          <li><a href="#">characters</a></li>
      </ul>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Nav'
}
</script>

<style lang="scss" scoped>
    
    .container {
        width: 70%;
        margin: auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px 0;
    }

    #logo {
        img {
        height: 75px;
        width: 75px;
        }
    }

    ul {
        display: flex;
        list-style: none;

        li {

            height: 100%;

            a {
                text-decoration: none;
                color: grey;
                text-transform: uppercase;
                font-weight: bold;
                font-size: 10px;
            }
            a:hover,
            a.active {
                color: blue;
                border-bottom: 5px solid;
            }

        }


    }

</style>
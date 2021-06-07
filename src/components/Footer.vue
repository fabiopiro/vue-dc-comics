<template>
  <div id="background">
      <div class="container">
          <div id="lists">
              <div id="first-column">
                <ul>
                    <li>dc comics</li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                </ul>
                <ul>
                    <li>Shop</li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Characters</a></li>
                </ul>
              </div>
              <ul>
                <li>dc</li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Characters</a></li>
              </ul>
              <ul>
                <li>sites</li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Characters</a></li>
              </ul>
          </div>
          <div id="big-logo">
              <img src="../assets/img/dc-logo-bg.png" alt="big logo">
          </div>
      </div>
  </div>
</template>

<script>

export default {
  name: 'Footer'
}
</script>

<style lang="scss" scoped>
    #background {
        background: url("../assets/img/footer-bg.jpg");
        background-repeat: no-repeat;
        background-size: cover;
    }

    .container {
        width: 70%;
        margin: auto;
        display: flex;
        justify-content: space-between;
    }

    #lists {
        display: flex;
        margin: 20px;
    }

    #first-column {
        display: flex;
        flex-direction: column;
    }

    ul {
        list-style: none;
        margin-bottom: 15px;
        margin-right: 30px;

        li:first-child {
            font-size: 20px;
            font-weight: bold;
            text-transform: uppercase;
            color: white;
            margin-bottom: 15px;
        }

        a {
            text-decoration: none;
            color: grey;
        }
    }

    #big-logo {
        img {
            height: 250px;
            width: 250px;
        }
    }

</style>
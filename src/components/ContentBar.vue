<template>
  <div id="background">
      <div class="container">
        <div class="element">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
            <span>digital comics</span>
        </div>
        <div class="element">
            <img src="../assets/img/buy-comics-merchandise.png" alt="">
            <span>dc merchandise</span>
        </div>
        <div class="element">
            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
            <span>subscription</span>
        </div>
        <div class="element">
            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
            <span>comic shop locator</span>
        </div>
        <div class="element">
            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
            <span>dc power visa</span>
        </div>
      </div>
  </div>
</template>

<script>

export default {
  name: 'ContentBar'
}
</script>

<style lang="scss" scoped>

    @import "../style/variables.scss";

    #background {
        background-color: $brandColor;
    }

    .container {
        width: 65%;
        margin: auto;
        display: flex;
        justify-content: center;
        padding: 30px 0;
    }

    .element {
        display: flex;
        align-items: center;
        margin: 0 15px;

        img {
            width: 45px;
        }
        
    }
</style>
<template>
  <div id="background">
    <div class="container">
      <div id="button">
        <a href="#">sign-up now!</a>
      </div>
      <div>
        <ul>
          <li>follow us</li>
          <li><a href="#"><img src="../assets/img/footer-facebook.png" alt="facebook"></a></li>
          <li><a href="#"><img src="../assets/img/footer-twitter.png" alt="twitter"></a></li>
          <li><a href="#"><img src="../assets/img/footer-youtube.png" alt="youtube"></a></li>
          <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt="pinterest"></a></li>
          <li><a href="#"><img src="../assets/img/footer-periscope.png" alt="periscope"></a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Social'
}
</script>

<style lang="scss" scoped>
  #background {
    padding:20px 0;
    background-color: #303030;
  }
  .container {
        width: 70%;
        margin: auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
  }
  
  #button {
    a {
      padding: 15px;
      border: 2px solid blue;
      text-decoration: none;
    }
  }

  ul {
    display: flex;
    align-items: center;
    list-style: none;

    li:first-child{
      font-size: 30px;
      color: blue;
    }

    li {
      margin-left: 15px;
    }
  }

</style>
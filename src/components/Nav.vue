<template>
  <div>
    <div class="container">
      <div id="logo">
          <img src="../assets/img/dc-logo.png" alt="logo">
      </div>
      <ul>
          <li v-for="(link, index) in links" :key="index">
              <a :href="link.url" :class="{ active : link.current }"> {{link.text}} </a>
          </li>
      </ul>
    </div>
  </div>
</template>

<script>

export default {
  name: 'Nav',
  data: function() {
      return {
          links: [
              {
                text: "characters",
                url: "#",
                current: false
              },
              {
                text: "comics",
                url: "#",
                current: false
              },
              {
                text: "movies",
                url: "#",
                current: false
              },
              {
                text: "tv",
                url: "#",
                current: false
              },
              {
                text: "games",
                url: "#",
                current: false
              },
              {
                text: "collectibles",
                url: "#",
                current: false
              },
              {
                text: "videos",
                url: "#",
                current: false
              },
              {
                text: "fans",
                url: "#",
                current: false
              },
              {
                text: "news",
                url: "#",
                current: false
              },
              {
                text: "shop",
                url: "#",
                current: false
              },
          ]
      }
  }
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
            margin-right: 15px;

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
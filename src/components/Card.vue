<template>
    <div id="container">
        <div class="image-container">
            <img :src="item.thumb" alt="">
        </div>
        <span>{{ item.series }}</span>
    </div>
</template>

<script>
    export default {
    name: 'Card',
    props: ["item"]
    }
</script>

<style lang="scss" scoped>
    #container {
        width: calc(100% / 6);
        display: flex;
        flex-direction: column;
        padding: 10px;

        span {
            text-transform: uppercase;
            color: white;
        }
    }

    .image-container {
        img {
            height: 150px;
            width: 150px;
            object-fit: cover;
            object-position: 0 0;
        }
    }
</style>
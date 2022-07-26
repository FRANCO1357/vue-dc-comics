<template>
    <figure>
        <img :src="comic.thumb" alt="">
        <figcaption>{{comic.series}}</figcaption>
    </figure>
</template>

<script>
export default{
    name: "ComicsCard",
    props: {
        comic: Object,
    }
    
}
</script>

<style lang="scss" scoped>

figure{
    width: calc(100% / 6);
    padding: 20px 8px;

    img{
        max-width: 100%;
    }

    figcaption{
        color: white;
        margin-top: 10px;
    }
}
</style>
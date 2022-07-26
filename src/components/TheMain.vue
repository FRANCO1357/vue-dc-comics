<template>
    <main>
        <div class="jumbotron">
            <div class="all-series">
                <div class="container">
                    <ComicsCard v-for="(comic, i) in comics" :key="i" :comic="comic"/>
                </div>
            </div>
        </div>
    </main>
</template>

<script>
import ComicsCard from "./ComicsCard.vue";
    export default{
    name: "TheMain",
    props: {
        comics: Array,
    },
    data() {
    },
    components: { 
        ComicsCard 
        }
};
</script>

<style lang="scss" scoped>

main{
    min-height: 100px;
    background-color: rgb(28,28,28);

    .container{
        display: flex;
        flex-wrap: wrap;
    }
}
</style>
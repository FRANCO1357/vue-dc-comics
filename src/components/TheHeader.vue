<template>
    <header>
        <div class="container">
            <figure>
                <img src="../assets/img/dc-logo.png" alt="">
            </figure>
            <nav>
                <ul>
                    <li v-for="link in links" :key="link.id">
                        <a :href="link.url" :class="{'active' : link.current}">{{link.text}}</a>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default{
    name: 'TheHeader',
    data(){
        return{
            links:[
                {
                    id: 1,
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    id: 2,
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    id: 3,
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    id: 4,
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    id: 5,
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    id: 6,
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    id: 7,
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    id: 8,
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    id: 9,
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    id: 10,
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
            ]
        }
    }
};
</script>

<style lang="scss" scoped>
header{
    background-color: white;
    height: 100px;

    .container{
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;

        img{
            height: 70px;
        }

        ul{
            display: flex;

            li{
                list-style-type: none;
                color: rgb(19, 19, 19);

                a{
                    text-decoration: none;
                    margin: 0 10px;

                    &:visited{
                        color: black;
                    }

                    &.active{
                        color: rgb(13,130,249);
                    }
                }
            }
        }
    }
}

</style>
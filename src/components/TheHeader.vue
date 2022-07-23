<template>
    <header>
        <div class="container">
            <figure>
                <img src="../assets/img/dc-logo.png" alt="">
            </figure>
            <nav>
                <ul>
                    <li><a href="#">CHARACTERS</a></li>
                    <li><a class="active" href="#">COMICS</a></li>
                    <li><a href="#">MOVIES</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">GAMES</a></li>
                    <li><a href="#">COLLECTIBLES</a></li>
                    <li><a href="#">VIDEOS</a></li>
                    <li><a href="#">FANS</a></li>
                    <li><a href="#">NEWS</a></li>
                    <li><a href="#">SHOP</a></li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default{
    name: 'TheHeader',
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
                        color: blue;
                    }
                }
            }
        }
    }
}

</style>
<template>
    <div class="footer-top">
        <div class="container">
            <nav>
                <h3>DC COMICS</h3>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">Tv</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
                <h3>SHOP</h3>
                <ul>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
            </nav>
            <nav>
                <h3>DC COMICS</h3>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">Tv</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
            </nav>
            <nav>
                <h3>DC COMICS</h3>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">Tv</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                </ul>
            </nav>        
        </div>
    </div>
</template>

<script>
    export default{
        name: 'TheFooterTop',
    };
</script>

<style lang="scss" scoped>

.footer-top{
    color: white;

    .container{
        display: flex;
        padding: 20px 0;
        background-image: url('../assets/img/dc-logo-bg.png');
        background-repeat: no-repeat;
        background-position: center right;

        nav{
            margin-right: 30px;

            h3{
            padding: 10px 0;
            }

            ul li{
                list-style-type: none;

                a{
                    color: white;
                    text-decoration: none;
                }
            }
        }
    }
}
</style>
<template>
    <div class="footer-bottom">
        <div class="container">
            <div class="button">
                <a href="">SIGN UP NOW!</a>
            </div>
            <div class="social">
                <h3>FOLLOW US</h3>
                <a href="#"><i class="fa-brands fa-facebook-f"></i></a>
                <a href="#"><i class="fa-brands fa-twitter"></i></a>
                <a href="#"><i class="fa-brands fa-youtube"></i></a>
                <a href="#"><i class="fa-brands fa-pinterest"></i></a>
                <a href="#"><i class="fa-solid fa-location-dot"></i></a>
            </div>
        </div>
    </div>
</template>

<script>
    export default{
        name: 'TheFooterBottom',
    };
</script>

<style lang="scss" scoped>
.footer-bottom{
    height: 100px;
    background-color: rgb(28,28,28);

    .container{
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;

        .button{
            a{
            text-decoration: none;
            color: white;
            border: 1px solid rgb(13,130,249);
            padding: 10px 18px;
        }
        }

        .social{
            display: flex;
            align-items: center;

            h3{
                color: rgb(13,130,249);
                margin-right: 10px;
            }

            a{
                width: 30px;
                height: 30px;
                margin: 0 5px;
                background-color: grey;
                border-radius: 50%;
                display: flex;
                justify-content: center;
                align-items: center;
                color: rgb(28,28,28);
                text-decoration: none;
            }
        }
    }
}
</style>
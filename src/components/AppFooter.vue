<script>
    export default {
        name: "AppMain",
    }
</script>

<template>
    <footer>
        <div id="footerUP">
            <div id="footerupRIGHT">
                <div id="col1">
                    <div class="lista">
                        <p>DC COMICS</p>
                        <ul>
                            <li>characters</li>
                            <li>comics</li>
                            <li>movies</li>
                            <li>tv</li>
                            <li>games</li>
                            <li>videos</li>
                            <li>news</li>
                        </ul>
                    </div>
                    <div class="lista">
                        <p>SHOP</p>
                        <ul>
                            <li>shop DC</li>
                            <li>shop DC collectibles</li>
                        </ul>
                    </div>
                </div>
                <div id="col2">
                    <div class="lista">
                        <p>DC</p>
                        <ul>
                            <li>Terms Of Use</li>
                            <li>Privacy policy (New)</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Subscriptions</li>
                            <li>Talent Workshops</li>
                            <li>CPSC Certificates</li>
                            <li>Ratings</li>
                            <li>Shop Help</li>
                            <li>Contact Us</li>
                        </ul>
                    </div>
                </div>
                <div id="col3">
                    <div class="lista">
                        <p>SITES</p>
                        <ul>
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC Power Visa</li>
                        </ul>
                    </div>
                </div>
            </div>

            <div id="footerupLEFT">
                <img id="footerLOGO" src="/img/dc-logo-bg.png" alt="">
            </div>
        </div>

        <div id="footerDOWN">
            <div id="footerdownRIGHT">
                <div class="bottone">
                    <p>SING-UP</p>
                </div>
            </div>

            <div id="footerdownLEFT">
                <p>FOLLOW US</p>
                <div id="loghi">
                    <img src="/img/footer-facebook.png" alt="">
                    <img src="/img/footer-twitter.png" alt="">
                    <img src="/img/footer-youtube.png" alt="">
                    <img src="/img/footer-pinterest.png" alt="">
                    <img src="/img/footer-periscope.png" alt="">
                </div>
            </div>
        </div>

    </footer>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

footer{

    #footerUP{
        padding-top: 10px;
        display: flex;
        justify-content: space-around;
        // height: 1000px;
        background-image: url("/img/footer-bg.jpg");

        #footerupRIGHT{
            display: flex;

            .lista{
                margin-left: 50px;
                margin-top: 20px;
                color: white;

                ul{
                color: darkgray;
                margin-left: -40px;
                line-height: 20px;
                list-style: none;
                }
            }

           
        }
    }
    
    #footerDOWN{
        padding-top: 10px;
        display: flex;
        justify-content: space-around;
        min-height: 100px;
        background-color: rgb(51, 51, 51);
        position: fixed;
        overflow: hidden;
        z-index: 20;
        width: 100%;
        bottom: 0;

        #footerdownRIGHT{
             .bottone{

                p{
                    border:1px solid dodgerblue;
                    color: white;
                    padding: 20px;
                }
             }
        }


        #footerdownLEFT{
            display: flex;
            text-align: center;
            align-items: center;
        }

        p{
            color: dodgerblue;
            font-weight: 900;
            font-size: x-large;
        }

        img{
            margin-left: 10px;
            margin-right: 10px;
        }
    }
}

</style>

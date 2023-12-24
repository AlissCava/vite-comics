<script>
    export default {
        name: "AppMain",
    }
</script>
<template>
  <main>

    <div id="containerContent">
        <p> -> Content goes here </p>
    </div>

    <div id="containericon">
        <div class="section">
            <img src="/img/buy-comics-digital-comics.png" alt="">
            <p>BUY DIGITAL COMICS</p>
        </div>

        <div class="section">
            <img src="/img/buy-comics-merchandise.png" alt="">
            <p>BUY MERCHANDISE</p>
        </div>

        <div class="section">
            <img src="/img/buy-comics-subscriptions.png" alt="">
            <p>SUBCRIPTION</p>
        </div>

        <div class="section">
            <img src="/img/buy-comics-subscriptions.png" alt="">
            <p>COMICS SHOP LOCATOR</p>
        </div>

        <div class="section">
            <img src="/img/buy-comics-subscriptions.png" alt="">
            <p>CD POWER VISA</p>
        </div>
    </div>
   
  </main>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

main{
    position: fixed;
    overflow: hidden;
    z-index: 10;
    width: 100%;

    #containerContent{
    padding-top: 10px;
    display: flex;
    justify-content: space-around;
    background-color: rgb(0, 0, 0); 
    min-height: 100px;

        p{
            color: white;
            font-size: 50px;
            font-weight: 900;
        }
    }   

    #containericon{
        align-items: center;
        padding-left: 50px;
        padding-right: 50px;
        display: flex;
        justify-content: space-around;
        background-color: dodgerblue;
        min-height: 200px;

        .section{
            text-align: center;
            display: flex;

            img{
            width: 40%;
            height: 50%;
            }

            p{
                padding-left: 10px;
                color: white;
                width: 100%;
            }
        }

        

    }


}


</style>

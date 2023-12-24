<script>
    export default {
        name: "AppHeader",
    }
</script>
<template>
  <header>
    <div>
        <img src=" /img/dc-logo.png">
    </div>

    <div id="navbar">
        <a href="/">CHARACTER</a>
        <a href="/">COMICS</a>
        <a href="/">MOVIES</a>
        <a href="/">TV</a>
        <a href="/">GAMES</a>
        <a href="/">COLLECTIONARY</a>
        <a href="/">VIDEOS</a>
        <a href="/">FANS</a>
        <a href="/">NEWS</a>
        <a href="/">SHOP</a>
    </div>
  </header>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as *;

header{
    padding-top: 10px;
    display: flex;
    justify-content: space-around;
    text-align: center;
    // position: fixed;
    // overflow: hidden;
    //  z-index: 10;
    // width: 100%;
    top: 0;
   
    #navbar{
        list-style: none;
        margin: 2.5rem 1rem 4rem;

        a {
            color: rgb(0, 0, 0);
            display: inline-block;
            padding: 1rem;
            text-decoration: none;
            font-weight: 600;
        }
    }
}

</style>

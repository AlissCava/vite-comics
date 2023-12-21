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
        <a href="/">CHARACTER</a>
        <a href="/">CHARACTER</a>
        <a href="/">CHARACTER</a>
        <a href="/">CHARACTER</a>
        <a href="/">CHARACTER</a>
        <a href="/">CHARACTER</a>
        <a href="/">CHARACTER</a>
        <a href="/">CHARACTER</a>
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

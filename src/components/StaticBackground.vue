<template>
    <div class="bg__back">
    </div>
    <div class="bg__front">
        <div class="bg__menu">
            <a class="menu__bio" href="#">Bio</a>
            <a class="memu__work" href="#">Work</a>
            <a class="menu__contact" href="#">Contact</a>
        </div>
        <img class="bg__logo" src='../assets/logo-250.png' alt='alex logo'>
    </div>
    <div class="bg__botton">
    </div>
</template>

<script>
export default {
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.bg__back {
    position: fixed;
    z-index: -2;
    top: 0;
    right: 0;
    width: 100vw;
    height: 100vh;
    background-color: white;
}
.bg__front {
    position: fixed;
    z-index: -1;
    top: 50px;
    right: 50px;
    width: calc(100vw - 100px);
    height: calc(100vh - 100px);
    background-color: #ff5851;
}
.bg__botton{
    position: fixed;
    z-index: 999;
    bottom: 0;
    right: 0;
    width: 100vw;
    height: 50px;
    background-color: white;
}
.bg__logo{
    position: absolute;
    bottom:0px;
    left: 0px;
}
.bg__menu{
    position: absolute;
    top: 0px;
    right: 10px;
}
a{
 text-decoration: none;
 color: white;
 margin: 0 10px;
}
</style>

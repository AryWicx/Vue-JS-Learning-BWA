<template>
    <div class="logos-wrapper">
        <h2 class="title-header">Find Best Logos</h2>
        <div class="item-logos">
            <img class="logo" src="../assets/1.png" alt="Gucci">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/2.png" alt="Adidas">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/3.png" alt="New Balance">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/4.png" alt="CAT">
        </div>
        <div class="item-logos">
            <img class="logo" src="../assets/5.png" alt="Nike">
        </div>
    </div>
</template>

<script>
export default {
    name: 'FindLogos',
}
</script>

<style scoped>
.title-header{
    margin-bottom: 80px;
    text-align: left;
}
.logos-wrapper{
    width: 70%;
    overflow: hidden;
    margin: auto;
}
.item-logos{
    float: left;
    margin-right: 70px;
    margin-bottom: 70px;
    width: 150px;
    height: 150px;
}
.item-logos .logo{
    width: 150px;
    height: 150px;
}
</style>
<template>
    <div class="logos-wrapper">
        <h2 class="title-header">Find Best Logo</h2>
        <div class="item-logos">
            <img class="logos" alt="Adidas logo" src="../assets/adidas-logo.png">
        </div>
        <div class="item-logos">
            <img class="logos" alt="Nike logo" src="../assets/nike-logo.png">
        </div>
        <div class="item-logos">
            <img class="logos" alt="Puma logo" src="../assets/puma-logo.png">
        </div>
        <div class="item-logos">
            <img class="logos" alt="Adidas logo" src="../assets/adidas-logo.png">
        </div>
        <div class="item-logos">
            <img class="logos" alt="Nike logo" src="../assets/nike-logo.png">
        </div>
        <div class="item-logos">
            <img class="logos" alt="Puma logo" src="../assets/puma-logo.png">
        </div>
    </div>
</template>

<script>
export default {
    name: 'Logo'
}
</script>

<style scoped>
.title-header {
    margin-bottom: 80px;
    text-align: left;
}
.logos-wrapper {
    width: 62%;
    overflow: hidden;
    margin: auto;
}
.item-logos {
    float: left;
    margin-right: 70px;
    margin-bottom: 70px;
    width: 150px;
    height: 150px;
}
.item-logos .logos {
    width: 150px;
    height: 150px;
}
</style>
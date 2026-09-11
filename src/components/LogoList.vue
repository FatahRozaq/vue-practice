<template>
    <div class="logos-wrapper">
        <h2>Find Best Logos</h2>
        <div class="item-logos">
            <img src="" alt="">
        </div>
        <div class="item-logos">
            <img src="" alt="">
        </div>
        <div class="item-logos">
            <img src="" alt="">
        </div>
        <div class="item-logos">
            <img src="" alt="">
        </div>
        <div class="item-logos">
            <img src="" alt="">
        </div>
    </div>
</template>

<script>
export default {
    name: 'LogoList'
}
</script>

<style scoped>
.logos-wrapper {
    width: 70%;
    overflow: hidden;
    margin: auto;
}

.item-logos {
    width: 150px;
    height: 150px;
    float: left;
    background: red;
    margin-right: 20px;
    margin-bottom: 20px;
}

</style>
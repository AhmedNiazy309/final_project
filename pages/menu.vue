<template>
<div>
<div class="bigmenu m-auto text-center d-block">
    <NuxtLink class="menu" to="/yuga">Yoga</NuxtLink>
    <NuxtLink class="menu" to="/car">Cardio</NuxtLink>
    <NuxtLink class="menu" to="/gym">Gymnastics</NuxtLink>
</div>
</div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.bigmenu{
    padding-top: 8%;
}
    .menu{
    background-color: #91B3D9;
    display: block;
    margin-top: 2%;
    padding: 2%;
    color: #fff;
    font-size: 30px;
    font-weight: 900;
    text-decoration: none;
    margin-left: 10%;
    margin-right: 10%;
        }
</style>
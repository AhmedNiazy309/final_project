<template>
    <div class="contaoner">
    <div class="home m-auto">
        <h1 class="text-center">FITFLEX</h1>
        <NuxtLink to="/des" class="next">Yoga</NuxtLink>
        <NuxtLink to="/des" class="next">Cardio</NuxtLink>
        <NuxtLink to="/des" class="next">Gymnastatic</NuxtLink>

    </div>
    </div>
</template>
<script>
export default {
}
</script>
<style scoped>
.home h1{
    font-weight: 900;
    font-size: 50px;
    margin-top: 7%;
    margin-bottom: 4%;
}
.next{
      text-align: center;
    background-color: #5767A3;
    padding: 2%;
    color: #fff;
    font-size: 20px;
    font-weight: 900;
    text-decoration: none;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 0 35% 2%;
}

</style>>
<template>
    <div>
        <div class="container text-center">
            <div class="food">
                <h1>Diet Plan</h1>
                <div class="row">
                    <div class="col-sm-6">
                        <div class="row">
                            <div class="col-sm-6">
                                <img src="@/assets/img/breakfast1.svg" alt="">
                            </div>
                            <div class="col-sm-6">
                                <div class="text">
                                    <NuxtLink to="/breakfastOne">
                                        <h3 class="h2">Breakfast</h3>
                                    </NuxtLink>
                                    <p>Oat Milk Bowls</p>
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <img src="@/assets/img/lunch1.svg" alt="">
                            </div>
                            <div class="col-sm-6">
                                <div class="text">
                                    <NuxtLink to="/lunchOne">
                                        <h3 class="h2">Lunch</h3>
                                    </NuxtLink>
                                    <p>peanut tofu wrap</p>
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <img src="@/assets/img/dinner1.svg" alt="">
                            </div>
                            <div class="col-sm-6">
                                <div class="text">
                                    <NuxtLink to="/dinnerOne">
                                        <h3 class="h2">Dinner</h3>
                                    </NuxtLink>
                                    <p>taco lettuce wrap</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-sm-6">
                        <div class="row">
                            <div class="col-sm-6">
                                <img src="@/assets/img/breakfast2.svg" alt="">
                            </div>
                            <div class="col-sm-6">
                                <div class="text">
                                    <NuxtLink to="/breakfastTwo">
                                        <h3 class="h2">Breakfast</h3>
                                    </NuxtLink>
                                    <p>Oat Milk Bowls</p>
                                </div>
                            </div>
                            <div class="col-sm-6">
                                    <img src="@/assets/img/lunch2.svg" alt="">
                            </div>
                            <div class="col-sm-6">
                                <div class="text">
                                    <NuxtLink to="/lunchtwo">
                                        <h3 class="h2">Lunch</h3>
                                    </NuxtLink>
                                    <p>peanut tofu wrap</p>
                                </div>
                            </div>
                            <div class="col-sm-6">
                                <img src="@/assets/img/dinner2.svg" alt="">
                            </div>
                            <div class="col-sm-6">
                                <div class="text">
                                    <NuxtLink to="/dinner2">
                                        <h3 class="h2">Dinner</h3>
                                    </NuxtLink>
                                    <p>taco lettuce wrap</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<style scoped>
.food{
    padding-top: 5%;
}
    h1{
        font-weight: 900;
        color: #5766A3;
        margin-bottom: 5%;
    }
    .food .text h3{
        color: #5767A3;
        font-family: "Arial-BoldMT";
        font-weight: 700;
    }
        .food .text a:hover{
            text-decoration: none;
            color: #5766A3;
        }
    .food .text p{
        color: #868995;
        font-family: "Corbel-Bold";
        font-size: 18px;
        font-weight: 700;
    }
</style>
<script>
export default {
    
}
</script>
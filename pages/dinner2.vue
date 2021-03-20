<template>
    <div class="main">
        <div class="container">
            <div class="breakone text-center">
                <img src="@/assets/img/dinnerpage2.svg" class="img-fluid text-center" alt="">
                <h1>Taco Lettuce Wrap</h1>
                <div class="row">
                    <div class="col-sm-6">
                        <i class="far fa-clock fo"></i>
                        <p class="d-inline">20 minutes</p>
                    </div>
                    <div class="col-sm-6">
                        <i class="fas fa-fire-alt fo"></i>
                        <p class="d-inline">375 kcal</p>
                    </div>
                </div>
                <div class="row cirlce">
                    <div class="col-sm-4">
                        <div class="list">
                            <h3>CARBS</h3>
                            <p>49.7g</p>
                        </div>
                    </div>
                    <div class="col-sm-4">
                        <div class="list">
                            <h3>FATS</h3>
                            <p>18.1g</p>
                        </div>
                    </div>
                    <div class="col-sm-4">
                        <div class="list">
                            <h3>PROTIEN</h3>
                            <p>9.6g</p>
                        </div>
                    </div>
                </div>
                <div class="des text-left">
                    <h2>Ingredients</h2>
                    <p > 1 tablespoon store-bought Thai 
                            peanut sauce
                            <br>
                            - 1 8-inch whole-wheat flour tortilla
                            <br>
                            - 2 ounces thinly sliced seasoned baked tofu
                            <br>
                            - ¼ cup sliced red bell pepper
                            <br>
                            - 8 thinly sliced snow peas
                    </p>
                    <br>
                    <h2>Instructions</h2>
                    <p>- Spread peanut sauce on the tortilla. 
                    <br>
                        - Place tofu, peppers and snow peas in the 
                        center.
                        <br>
                        - Fold the sides over the filling and roll up.
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.main{
    background-color: #E7E7DB;
    height: 100%;
}
.breakone{
    padding-top: 3%;
}
h1,h2{
    color: #393939;
}
h1{
    margin-bottom: 5%;
}
.breakone .col-sm-6{
    font-size: 20px;
    font-weight: 700;
}
.breakone .col-sm-6 .fo{
    margin-right: 3%;
}
.breakone .cirlce{
    margin-top: 3%;
    margin-left: 10%;
}
.breakone .cirlce .list{
background-color: #fff;
    border-radius: 50%;
    width: 165px;
    padding: 7%;
    text-align: center;
    }
.breakone .cirlce h3{
        color: #5767A3;
        font-family: "Corbel-Bold";
        font-size: 25px;
        font-weight: 600;
}
.breakone .cirlce p{
    color: #393939;
    font-family: "BookmanOldStyle-Bold";
    font-size: 22px;
    font-weight: 600;
}
.des{
        display: grid;
    justify-content: center;
    align-items: center;
    margin-top: 5%;
    background-color: #fff;
    padding: 5% 0 2%;
}
</style>
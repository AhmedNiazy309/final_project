<template>
    <div class="main">
        <div class="container">
            <div class="breakone text-center">
                <img src="@/assets/img/lunchPageOne.svg" class="img-fluid text-center" alt="">
                <h1>Egg Omelet With Vegetables</h1>
                <div class="row">
                    <div class="col-sm-6">
                        <i class="far fa-clock fo"></i>
                        <p class="d-inline">20 minutes</p>
                    </div>
                    <div class="col-sm-6">
                        <i class="fas fa-fire-alt fo"></i>
                        <p class="d-inline">375 kacl</p>
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
                <div class="des text-center">
                    <h2>Ingredients</h2>
                    <p > 
                    - 2 eggs
                    <br>
                    - 2 Tbsp. vegetable or canola oil
                    <br>
                    - 2 Tbsp. water or milk
                    <br>
                    - salt and pepper to taste
                    <br>
                    - 1/2 Tbsp. butter
                    <br>
                    - 2 Tbsp. onion chopped
                    <br>
                    - 1/4 c. mushrooms chopped
                    <br>
                    - 1/2 c. fresh spinach
                    <br>
                    - 3 cherry tomatoes sliced in half
                    <br>
                    - shredded cheddar cheese to taste
                    </p>
                    <br>
                    <h2>Instructions</h2>
                    <p>
                        -- Crack and add the eggs to a bowl, beat them with a fork and season with salt and pepper.
                    <br>
                        - Once the butter is melted, add the beaten eggs, and spread over evenly, tilting the pan to ensure you get the same thickness.
                    <br>
                        - Leave to cook undisturbed until the 
                        edges start to cook, but there is still
                        raw eggs in the middle. Now you can 
                        add your toppings, then carefully flip 
                        the omelet over with a spatula, and
                        leave to cook on the other side.                  
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
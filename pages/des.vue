<template>
    <div>
    <div class="container">
    <div class="des text-center m-auto">
    <h2>CHOOSE YOUR
    <br>
FITNESS LEVEL</h2>
<p>Let us know you better to provide more
<br>
targeted support for you.</p>
        <div class="row"> 
            <div class="col-sm-5">
            <p>
            Date of Birth
            </p>
            </div>
            <div class="col-sm-2"></div>
            <div class="col-sm-5">
            <p>
            1990-01-01
            </p>
            </div>


            <div class="col-sm-5">
            <p>
            Weight
            </p>
            </div>
            <div class="col-sm-2"></div>
            <div class="col-sm-5">
            <p>
            121.3
            </p>
            </div>


            <div class="col-sm-5">
            <p>
            Height
            </p>
            </div>
            <div class="col-sm-2"></div>
            <div class="col-sm-5">
            <p>
            Height
            </p>
            </div>
        </div>
    <NuxtLink to="/des" class="next">NEXT</NuxtLink>

    </div>
    </div>
    </div>
</template>
<style scoped>
.des h2{
    font-size: 30px;
    font-weight: 900;
    margin-bottom: 4%;
}
.des p{
    font-size: 17px;
    font-weight: 500;
    margin-bottom: 8%;
}
.des .col-sm-5 p{
    line-height: 2;
    font-weight: 800;
    font-size: 19px;
}
.next{
      text-align: center;
    background-color: #5767A3;
    padding: 2%;
    color: #fff;
    font-size: 20px;
    border-radius: 57px;
    font-weight: 900;
    text-decoration: none;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 3% 35% 2%;
}

</style>

<template>
<div>
<div class="container">
<div class="profile m-auto text-center">
    <h3 class="text-center">My Profile</h3>
    <img src="@/assets/img/person.svg" class="img-fluid text-center" alt="">
    <h2 class="h1">Asmaa Harb</h2>
    <div class="fontawesome">
    <div class="row">
    <div class="col-sm-4">
    <i class="fas fa-star font"></i>
    </div>
    <div class="col-sm-4">
        <i class="fas fa-arrow-up font"></i>
    </div>
    <div class="col-sm-4">
    <i class="far fa-clock font"></i>
    </div>
    </div>
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
.profile{
    padding-top: 5%;
}
h3{
    font-weight: 600;
    font-size: 28px;
}
.profile img.text-center.img-fluid{
    margin-top: 1%;
    background: url(@/assets/img/circle.svg);
    padding: 1%;
    background-repeat: no-repeat;
    text-align: center;
    background-size: cover;
}
.profile h2{
    font-weight: 900;
    margin-top: 2.5%;
}
.fontawesome{
    margin-top: 5%;
}
.fontawesome .font{
    background-color: #5766A3;
    font-size: 40px;
    padding: 5%;
    color: #fff;
    border-radius: 50%;
    margin-bottom: 3%;
}
</style>
<template>
  <div>
    <div class="container">
      <div class="menu text-center">
        <h1>FITFLEX</h1>
        <p class="h3">Yoga</p>
        <div class="row">
          <div class="col-md-5 text-left">
            <h1>Side Bar</h1>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Aliquid
              sunt illum nisi modi perspiciatis quisquam atque aperiam,
              recusandae quo et magni maiores suscipit facere aspernatur
              delectus saepe asperiores doloremque nam?
            </p>
          </div>
          <div class="col-md-1">
          
          </div>
          <div class="col-md-6">
            <div class="row text-left">
              <div class="col-md-6">
                <NuxtLink to="/child" class="list">Child’s Pose</NuxtLink>
              </div>
              <div class="col-md-6">
                <img src="@/assets/img/1.svg" class="img-fluid" alt="" />
              </div>
              <div class="col-md-6">
                <NuxtLink class="list" to="/wind">Wind-Relieving Pose</NuxtLink>
              </div>
              <div class="col-md-6">
                <img src="@/assets/img/2.svg" class="img-fluid" alt="" />
              </div>
              <div class="col-md-6">
                <NuxtLink to="/spinal" class="list">Spinal Twist Pose </NuxtLink>
              </div>
              <div class="col-md-6">
                <img src="@/assets/img/3.svg" alt="" class="img-fluid" />
              </div>
              <div class="col-md-6">
                <NuxtLink to="/stand" class="list">Standing Forward
 Bend Pose</NuxtLink>
              </div>
              <div class="col-md-6">
                <img src="@/assets/img/4.svg" alt="" class="img-fluid" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {}
</script>
<style scoped>
.menu{
    padding-top: 10%;
}
h1 {
  font-weight: 900;
  font-size: 30px;
}
p.h3 {
  font-size: 22px;
  font-weight: 700;
  margin: 2% 0 5%;
}
.list{
color:#000;
text-decoration: none;
font-weight: 900;
font-size: 18px;
text-align: left;
}
.list:hover{
    color: inherit;
}
</style>
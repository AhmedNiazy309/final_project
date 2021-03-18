<template>
      <section class="main box">
      <div class="container">
              <img src="@/assets/img/FITFLEX.svg" class="text-center" alt="">
              <img src="@/assets/img/yoga.svg" class="text-center d-block mt-35" alt="">
              <NuxtLink to="/signup" class="d-block sign mb-4 mt-5">Sign Up</NuxtLink>
              <NuxtLink to="/SignIn" class="d-block sign">Sign In</NuxtLink>
      </div>
      </section>
</template>

<script>
export default {}
</script>

<style>
.box{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%,-50%);
  text-align: center;
}
.mt-35{
  margin-top: 25%;
}
.sign {
      background-color: #5767A3;
    padding: 5%;
/*    margin-top: 25%;*/
    color: #fff;
    font-size: 20px;
    border-radius: 25px;
    font-weight: 900;
    text-decoration: none;
}
.sign:hover{
  color: #fff;
  text-decoration: none;
}
</style>

<template>
  <div class="signin">
    <div class="container">
      <h2 class="signinword text-left">Sign in</h2>
      <p class="lead text-left">please sign in to continue</p>
      <form action="">
        <div class="textbox">
          <i class="fas fa-user"></i>
          <input type="text" placeholder="Username" class="form-control" />
        </div>
        <div class="textbox">
          <i class="fas fa-lock"></i>
          <input type="password" placeholder="Password" class="form-control" />
        </div>
        <NuxtLink to="/chooce" class=" sign">Sign In</NuxtLink>
        <NuxtLink to="" class="d-block fo mb-3">Forget Password?</NuxtLink>
        <NuxtLink to="/signup" class="d-block fo">Sign Up</NuxtLink>

      </form>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.signin {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 100%;
  text-align: center;
}
.signinword {
  color: #3a3a3a;
  font-family: Arial-BoldMT;
  font-size: 30px;
  font-weight: 700;
}
.signin p {
  color: #3a3a3a;
  font-size: 15px;
    font-weight: 800;
}
.textbox {
  width: 100%;
  overflow: hidden;
  font-size: 20px;
  padding: 8px 0;
}
.textbox i {
  position: absolute;
    padding: 1% 5% 0% 4%;
  color: #fff;
  left: 7%;
  font-size: 2rem;
}
.textbox input {
  font-size: 18px;
  width: 100%;
  float: left;
  background-color: #91b3d9;
  border-radius: 20px;
  border: none;
  padding: 3% 0% 3% 7%;
  color: #fff;
  margin-bottom: 2rem;
}
.form-control:focus {
  background-color: #91b3d9;
}
.sign {
      background-color: #5767A3;
    padding: 2%;
/*    margin-top: 25%;*/
    color: #fff;
    font-size: 20px;
    border-radius: 50px;
    font-weight: 900;
    text-decoration: none;
        width: 40rem;
    display: flex;
    text-align: center;
    justify-content: center;
    margin: 2% 20%;
}
.sign:hover{
  color: #fff;
  text-decoration: none;
}
.fo{
    color: #000;
    text-align: center;
    text-decoration: none;
    font-weight: 800;
}
.fo:hover{
    text-decoration: none;
    color: #000 ;
}
</style>
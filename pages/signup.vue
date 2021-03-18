<template>
  <div class="signin">
    <div class="container">
      <h2 class="signinword text-left">Create Account</h2>
      <p class="lead text-left">please fill the input bellow here</p>
      <form action="">
        <div class="textbox">
          <i class="fas fa-user"></i>
          <input type="text" placeholder="Username" class="form-control" />
        </div>
        <div class="textbox">
          <i class="far fa-envelope"></i>
          <input type="email" placeholder="Email" class="form-control" />
        </div>
        <div class="textbox">
          <i class="fas fa-lock"></i>
          <input type="password" placeholder="Password" class="form-control" />
        </div>
        <div class="textbox">
          <i class="fas fa-lock"></i>
          <input type="password" placeholder="Password" class="form-control" />
        </div>
        <div class="male-female-question">
          <div class="answer-element">
            <input type="radio" name="gender" value="male" id="male" />
            <label for="male">Male</label>
          </div>
          <div class="answer-element">
            <input type="radio" name="gender" value="female" id="female" />
            <label for="female">Female</label>
          </div>
        </div>

        <NuxtLink to="/chooce" class="d-block sign">Sign Up</NuxtLink>
        <h3>
          Already have an account? <NuxtLink to="/SignIn">Sign In</NuxtLink>
        </h3>
      </form>
    </div>
  </div>
</template>

<script>
$('body').on('click', '.answer-element input', function () {
  var selectedAnswer = $(this).parent()
  var allAnswers = $(this).parent().parent().children()
  allAnswers.removeClass('selected-answer')
  selectedAnswer.addClass('selected-answer')
  // console.log(selected-answer);
})

export default {}
</script>

<style scoped>
.signin {
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
  padding: 2% 0% 3% 7%;
  color: #fff;
  margin-bottom: 0rem;
}
.form-control:focus {
  background-color: #91b3d9;
}
.sign {
  background-color: #5767a3;
  padding: 2%;
  color: #fff;
  font-size: 20px;
  border-radius: 50px;
  font-weight: 900;
  text-decoration: none;
  width: 40rem;
  display: flex;
  text-align: center;
  justify-content: center;
  margin: 0% 20% 1%;
}
a:hover {
  color: #000;
  text-decoration: none;
}
.fo {
  color: #000;
  text-align: center;
  text-decoration: none;
  font-weight: 800;
}
.fo:hover {
  text-decoration: none;
  color: #000;
}
.male-female-question {
  display: inline-block;
  width: 100%;
  height: 100%;
  cursor: pointer;
}
.answer-element label {
  display: inline-block;
  width: 100%;
  height: 100%;
  padding: 1rem;
  cursor: pointer;
}
input[type='radio']:checked > .answer-element {
  background-color: #eb5757;
}
.answer-element {
  border: 1px solid #242424;
  margin: 1rem 0;
  text-align: center;
  background-color: #f7f6f4;
  cursor: pointer;
}
.answer-element input[type='radio'] {
  display: none;
}
.answer-element {
  border: 1px solid #242424;
  margin: 1rem 0;
  text-align: center;
  background-color: rgba(145, 179, 217, 0.4) !important;
  cursor: pointer;
}
.selected-answer {
  background-color: rgba(145, 179, 217, 1) !important;
  border: 1px solid rgba(145, 179, 217, 1) !important;
}
</style>
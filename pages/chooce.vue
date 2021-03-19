<template>
  <div class="choose">
    <div class="container">
      <h2>
        CHOOSE YOUR
        <br />
        FITNESS LEVEL
      </h2>
      <p>
        Choose the description that fits you the most. We will
        <br />
        design a program with a suitable difficulty level for you.
      </p>
      <!--<div class="chartchoose">
        <div class="row">
          <div class="col-md-4"></div>
          <div class="col-md-4">
     <div class="row">
              <div class="col-md-2" style="position: relative">
                <div class="answer-element" style="position: absolute; height: 30px;bottom: -145px;">
                  <input type="radio" name="gender" value="A" id="A" />
                  <label for="A"></label>
                </div>
              </div>
              <div class="col-md-2" style="position: relative">
                <div class="answer-element" style="position: absolute; height: 50px;bottom: -145px;">
                  <input type="radio" name="gender" value="B" id="B" />
                  <label for="B"></label>
                </div>
              </div>
              <div class="col-md-2" style="position: relative">
                <div class="answer-element" style="position: absolute; height: 70px;bottom: -145px;">
                  <input type="radio" name="gender" value="C" id="C" />
                  <label for="C"></label>
                </div>
              </div>
              <div class="col-md-2" style="position: relative">
                <div class="answer-element" style="position: absolute; height: 90px;bottom: -145px;">
                  <input type="radio" name="gender" value="D" id="D" />
                  <label for="D"></label>
                </div>
              </div>
              <div class="col-md-2" style="position: relative">
                <div class="answer-element" style="position: absolute; height: 110px;bottom: -145px;">
                  <input type="radio" name="gender" value="E" id="E" />
                  <label for="E"></label>
                </div>
              </div>
              <div class="col-md-2" style="position: relative">
                <div class="answer-element" style="position: absolute; height: 130px;bottom: -145px;">
                  <input type="radio" name="gender" value="F" id="F" />
                  <label for="F"></label>
                </div>
              </div>
            </div>
          </div>

          <div class="col-md-4"></div>
        </div>
      </div>-->
      <div class="chartchoose">
      <div class="row">
        <div class="answer-element col A" style=" transform: scale(.2 , -1.5); position: relative;top: 182px;">
                  <input type="radio" name="gender" value="A" id="A" />
                  <label for="A"></label>
                </div>
                
        <div class="answer-element col B" style="transform: scale(.2 , -2.2);position: relative;top: 164px;">
                  <input type="radio" name="gender" value="B" id="B" />
                  <label for="B"></label>
                </div>
                                
        <div class="answer-element col C" style="transform: scale(.2 , -2.9);position: relative;top: 147px;">
                  <input type="radio" name="gender" value="C" id="C" />
                  <label for="C"></label>
                </div>
                                
        <div class="answer-element col D" style="transform: scale(.2 , -3.6);position: relative;top: 129px;">
                  <input type="radio" name="gender" value="D" id="D" />
                  <label for="D"></label>
                </div>
                                
        <div class="answer-element col E" style="transform: scale(.2 , -4.1);position: relative;top: 116px;">
                  <input type="radio" name="gender" value="E" id="E" />
                  <label for="E"></label>
                </div>
                                
        <div class="answer-element col F" style="transform: scale(.2 , -4.8);position: relative;top: 99px;">
                  <input type="radio" name="gender" value="F" id="F" />
                  <label for="F"></label>
                </div>
                                
      </div>
      <p id="demo"></p>
      <NuxtLink to="/des" class="next">NEXT</NuxtLink>
      </div>
    </div>
  </div>
</template>
<script>
$('body').on('click', '.answer-element input', function () {
  var selectedAnswer = $(this).parent();
  var allAnswers = $(this).parent().parent().children();
//   console.log(allAnswers); 
   console.log(allAnswers);
  allAnswers.removeClass('selected-answer')
  selectedAnswer.addClass('selected-answer')
});
$('body').on('click', '.A', function () {
    var show = document.getElementById("demo");
    show.innerHTML = "I easily get out of breath while walking up the stairs.";
});
$('body').on('click', '.B', function () {
    var show = document.getElementById("demo");
    show.innerHTML = "My heartbeat really races after doing several jumping jacks.";
});
$('body').on('click', '.C', function () {
    var show = document.getElementById("demo");
    show.innerHTML = "Sometimes I do quick workouts to get my body moving.";
});
$('body').on('click', '.D', function () {
    var show = document.getElementById("demo");
    show.innerHTML = "I exercise regularly, at least 1-2 times a week.  ";
});
$('body').on('click', '.E', function () {
    var show = document.getElementById("demo");
    show.innerHTML = "Fitness is an essential part of my life.";
});
$('body').on('click', '.F', function () {
    var show = document.getElementById("demo");
    show.innerHTML = "Fitness is an essential part of my life.";
});

export default {}
</script>
<style scoped>
.choose h2 {
  text-align: center;
  margin-top: 5%;
  font-weight: 800;
}
.choose p {
  text-align: center;
  margin-top: 2%;
  font-weight: 500;
}
.chartchoose {
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
  text-align: center;
  background-color: #404e5c !important;
  cursor: pointer;
  max-width: 50%;
  min-height: 0%;
          -webkit-transform: rotate(360deg);
        -moz-transform: rotate(360deg);
        -o-transform: rotate(360deg);
        -ms-transform: rotate(360deg);
        transform: rotate(360deg);
}
.selected-answer {
  background-color: rgba(145, 179, 217, 1) !important;
  border: 1px solid rgba(145, 179, 217, 1) !important;
}
.offset-1 {
    margin-left: 1.333333% !important;
}
#demo{
      position: relative;
    margin-top: 20%;
    font-size: 20px;
    font-weight: 500;
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
    margin: 0 35% 2%;
}
</style>
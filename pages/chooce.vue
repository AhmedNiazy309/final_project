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
      <div class="chartchoose">
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
            </div>-->
          </div>

          <div class="col-md-4"></div>
        </div>
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
})

export default {}
</script>
<style scoped>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.choose h2 {
  text-align: center;
  margin-top: 8%;
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
  position: absolute;
  border: 1px solid #242424;
  text-align: center;
  background-color: #404e5c !important;
  cursor: pointer;
  max-width: 50%;
  min-height: 0%;
}
.selected-answer {
  background-color: rgba(145, 179, 217, 1) !important;
  border: 1px solid rgba(145, 179, 217, 1) !important;
}
</style>
<!DOCTYPE html>
<html>

<head>
    <title>Master MadLib</title>
    <meta charset="UTF-8">
    <style>
        div {
            border: 1px solid blue;
            background-color: rgb(224, 19, 107);
        }
        .displayNone {
            display: none;
        }
        .displayBlock {
            display: block;
        }
        #warning { background-color: red;}
        .bgPink {background-color: pink;}
    </style>
</head>

<body>
    <div id="inputPanel">
        <h3>A few questions for you</h3>
        <p>Your first name:
            <input id="firstName" type="text" placeholder="first name">
        </p>
        <p>Your favorite color:
            <input id="favColor" type="text" placeholder="favorite color">
        </p>
        <p>Your place of birth:
            <input id="place" type="text" placeholder="place of birth">
        </p>
        <button id="submit">Submit your answers</button>
        <p id="warning">Please answer all questions.</p>

    </div>
    <div id="outputPanel">
        <p>Your story....</p>
        <p id="theStory">Junk</p>
        <button id="again">Again?</button>
    </div>
    <script>
      const inputPanel = document.querySelector("#inputPanel");
      const outputPanel = document.querySelector("#outputPanel");
      const warning = document.querySelector("#warning");
      const submit = document.querySelector("#submit");

      submit.addEventListener("click", writeStory, false);
      submit.style.cursor = "pointer"

      const again = document.querySelector("#again");
      again.addEventListener("click", resetPage, false);
      again.style.cursor = "pointer"
      document.querySelector('#firstName').focus();

      const firstName = document.querySelector('#firstName');
      const favColor = document.querySelector("#favColor");
      const place = document.querySelector('#place');
      const theStory = document.querySelector("#theStory");

      window.addEventListener("keydown", keydownHandler, false);
      inputPanel.className = "displayBlock"
      outputPanel.className = "displayNone"
      warning.className = "displayNone"

      firstName.focus()
      function keydownHandler(event) {
        if (event.keyCode === 13) {

          console.log("Enter key pressed");
          writeStory()
        }
      }
      function checkComplete() {

        removePinkBG()
        if (firstName.value == "") {
          firstName.className = "bgPink"
        }
        if (favColor.value == ""){
          favColor.className = "bgPink"
        }
        if (place.value == ""){
          place.className = "bgPink"
        }
        if (firstName.value == "" || favColor.value == "" || place.value == ""){
          warning.className = "displayBlock"
          return false
        } else {
          return true
        }
      }
      function writeStory() {

        if (checkComplete()==false){
          return
        }
        let finishedStory = ""
        finishedStory += "You are known as " + firstName.value + ". "
        finishedStory += ", you like to wear " + favColor.value + " cloths"
        finishedStory += ", and were born in " + place.value + "."
        theStory.innerHTML = finishedStory


        inputPanel.className = "displayNone"
        outputPanel.className = "displayBlock"
        warning.className = "displayNone"
      }

      function resetPage() {

        inputPanel.className = "displayBlock"
        outputPanel.className = "displayNone"
        warning.className = "displayNone"

        firstName.value = ""
        favColor.value = ""
        place.value = ""

        firstName.classList.remove('bgPink')
        favColor.classList.remove('bgPink')
        place.classList.remove('bgPink')

        removePinkBG()
        theStory.innerHTML = ""
        firstName.focus()
      }
      function removePinkBG(){
        firstName.classList.remove('bgPink')
        favColor.classList.remove('bgPink')
        place.classList.remove('bgPink')
      }
    </script>
  </body>

  </html>

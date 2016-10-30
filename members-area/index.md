---
layout: page
title: Band Members' Area
permalink: /members-area/
---
Please enter your pin:
<input type="password" id="myPin">

<button onclick="checkPin()">Submit pin</button>

<p>Please note: Your note boxes will not work in iOS or Chrome and you can only access them on the same browser.</p>
<script>
function checkPin() {
  var pin = document.getElementById("myPin").value;
  if (pin == 1678) {
    window.open("https://livethebeatband.github.io/members-area/daniel", "_self");
  } else if (pin == 3682) {
    window.open("https://livethebeatband.github.io/members-area/william", "_self");
  } else if (pin == 4830) {
    window.open("https://livethebeatband.github.io/members-area/astrid", "_self");
  } else if (pin == 8902) {
    window.open("https://livethebeatband.github.io/members-area/helen", "_self");
  } else if (pin == 5267) {
    window.open("https://livethebeatband.github.io/members-area/rohan", "_self");
  } else if (pin == 2567) {
    window.open("https://livethebeatband.github.io/members-area/joseph", "_self");
  } else if (pin == 4382) {
    window.open("https://livethebeatband.github.io/members-area/michael", "_self");
  } else if (pin == 6518) {
    window.open("https://livethebeatband.github.io/members-area/admin", "_self");
  } else {
    alert("That is not a valid pin. Access denied! Try again!");
  }
}
</script>

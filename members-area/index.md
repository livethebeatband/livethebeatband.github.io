---
layout: page
title: Band Members' Area
permalink: /members-area/
---
Please enter your pin:
<input type="password" id="myPin">

<button onclick="checkPin()">Submit pin</button>

<script>
function checkPin() {
  var pin = document.getElementById("myPin").value;
  if (pin == 1678) {
    window.open("https://livethebeatband.github.io/members-area/daniel", "_self");
  } else if (pin == 3682) {
    window.open("https://livethebeatband.github.io/members-area/william");
  } else if (pin == 4830) {
    window.open("https://livethebeatband.github.io/members-area/astrid");
  } else if (pin == 8902) {
    window.open("https://livethebeatband.github.io/members-area/helen");
  } else if (pin == 5267) {
    window.open("https://livethebeatband.github.io/members-area/rohan");
  } else if (pin == 2567) {
    window.open("https://livethebeatband.github.io/members-area/joseph");
  } else if (pin == 4382) {
    window.open("https://livethebeatband.github.io/members-area/michael");
  } else if (pin == 6518) {
    window.open("https://livethebeatband.github.io/members-area/admin");
  } else {
    alert("That is not a valid pin. Access denied! Try again!");
  }
}
</script>

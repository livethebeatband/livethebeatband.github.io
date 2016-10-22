---
layout: page
title: Band Member's Area
permalink: /members-area/
---
Please enter your pin:
<input type="password" id="myPin">

<button onclick="checkPin)">Submit pin</button>

<script>
function checkPin() {
    var pin = document.getElementById("myPin").value;
    if (pin = 1678) {
      window.open("https://livethebeatband.github.io/members-area/daniel");
    } else {
      alert("That is not a valid pin. Access denied! Try again!");
    }
}
</script>

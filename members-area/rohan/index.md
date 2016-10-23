---
layout: page
permalink: /members-area/rohan/
---
<body onbeforeunload="unload()" onpageshow="load()">
<h1> Rohan </h1>

Any important information will appear here:

No information available

<a href="/members-area/rohan/sheet-music/">My Sheet Music</a>

<h4>Make any notes you need, here:</h4>
<textarea id="Rohan's notes" rows="4" cols="50">
</textarea>

<script>
  function load() {
    document.getElementById("Rohan's notes").innerHTML = localStorage.getItem("Rohan's text-box"); 
  }
  function unload() {
    localStorage.setItem("Rohan's text-box", document.getElementById("Rohan's notes").innerHTML);
  }
  </script>

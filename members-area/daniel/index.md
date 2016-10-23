---
layout: page
permalink: /members-area/daniel/
---
<body onbeforeunload="unload()" onpageshow="load()">
<h1> Daniel </h1>

Any important information will appear here:

No information available

<h4>Make any notes you need, here:</h4>
<textarea id="notes" rows="4" cols="50">
</textarea>

<script>
  function load() {
    document.getElementById("notes").innerHTML = localStorage.getItem("text-box"); 
  function unload() {
    localStorage.setItem("text-box", document.getElementById("notes").innerHTML);
  }
  </script>

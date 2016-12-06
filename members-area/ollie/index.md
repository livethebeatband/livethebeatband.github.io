---
layout: page
permalink: /members-area/ollie/
---
<body onbeforeunload="unload()" onpageshow="load()">
<h1> Ollie </h1>

Any important information will appear here:

No information available
<br/>
<a href="/members-area/ollie/sheet-music/">My Sheet Music</a>

<h4>Make any notes you need, here:</h4>
<textarea id="Ollie's notes" rows="4" cols="50">
</textarea>

<script>
  function load() {
    document.getElementById("Ollie's notes").innerHTML = localStorage.getItem("Ollie's text-box"); 
  }
  function unload() {
    localStorage.setItem("Ollie's text-box", document.getElementById("Ollie's notes").innerHTML);
  }
  </script>

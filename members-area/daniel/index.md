---
layout: page
permalink: /members-area/daniel/
---
<body onbeforeunload="unload()" onpageshow="load()">
<h1> Daniel </h1>

Any important information will appear here:

No information available
<br/>
<a href="/members-area/daniel/sheet-music/">My Sheet Music</a>

<h4>Make any notes you need, here:</h4>
<textarea id="Daniel's notes" rows="4" cols="50">
</textarea>

<script>
  function load() {
    document.getElementById("Daniel's notes").innerHTML = localStorage.getItem("Daniel's text-box"); 
  }
  function unload() {
    localStorage.setItem("Daniel's text-box", document.getElementById("Daniel's notes").innerHTML);
  }
  </script>

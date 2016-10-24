---
layout: page
permalink: /members-area/michael/
---
<body onbeforeunload="unload()" onpageshow="load()">
<h1> Michael </h1>

Any important information will appear here:

No information available
<br/>
<a href="/members-area/michael/sheet-music/">My Sheet Music</a>

<h4>Make any notes you need, here:</h4>
<textarea id="Michael's notes" rows="4" cols="50">
</textarea>

<script>
  function load() {
    document.getElementById("Michael's notes").innerHTML = localStorage.getItem("Michael's text-box"); 
  }
  function unload() {
    localStorage.setItem("Michael's text-box", document.getElementById("Michael's notes").innerHTML);
  }
  </script>

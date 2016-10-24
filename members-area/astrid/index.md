---
layout: page
permalink: /members-area/astrid/
---
<body onbeforeunload="unload()" onpageshow="load()">
<h1> Astrid </h1>

Any important information will appear here:

No information available
<br/>
<a href="/members-area/astrid/sheet-music/">My Sheet Music</a>

<h4>Make any notes you need, here:</h4>
<textarea id="Astrid's notes" rows="4" cols="50">
</textarea>

<script>
  function load() {
    document.getElementById("Astrid's notes").innerHTML = localStorage.getItem("Astrid's text-box"); 
  }
  function unload() {
    localStorage.setItem("Astrid's text-box", document.getElementById("Astrid's notes").innerHTML);
  }
  </script>

---
layout: page
permalink: /members-area/william/
---
<body onbeforeunload="unload()" onpageshow="load()">
<h1> William </h1>

Any important information will appear here:

No information available

<a href="/members-area/william/sheet-music/">My Sheet Music</a>

<h4>Make any notes you need, here:</h4>
<textarea id="William's notes" rows="4" cols="50">
</textarea>

<script>
  function load() {
    document.getElementById("William's notes").innerHTML = localStorage.getItem("William's text-box"); 
  }
  function unload() {
    localStorage.setItem("William's text-box", document.getElementById("William's notes").innerHTML);
  }
  </script>

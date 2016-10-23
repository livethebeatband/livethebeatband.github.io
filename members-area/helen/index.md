---
layout: page
permalink: /members-area/helen/
---
<body onbeforeunload="unload()" onpageshow="load()">
<h1> Helen </h1>

Any important information will appear here:

No information available

<a href="/members-area/helen/sheet-music/">My Sheet Music</a>

<h4>Make any notes you need, here:</h4>
<textarea id="Helen's notes" rows="4" cols="50">
</textarea>

<script>
  function load() {
    document.getElementById("Helen's notes").innerHTML = localStorage.getItem("Helen's text-box"); 
  }
  function unload() {
    localStorage.setItem("Helen's text-box", document.getElementById("Helen's notes").innerHTML);
  }
  </script>

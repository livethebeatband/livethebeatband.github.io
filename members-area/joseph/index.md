---
layout: page
permalink: /members-area/joseph/
---
<body onbeforeunload="unload()" onpageshow="load()">
<h1> Joseph </h1>

Any important information will appear here:

No information available

<a href="/members-area/joseph/sheet-music/">My Sheet Music</a>

<h4>Make any notes you need, here:</h4>
<textarea id="Joseph's notes" rows="4" cols="50">
</textarea>

<script>
  function load() {
    document.getElementById("Joseph's notes").innerHTML = localStorage.getItem("Joseph's text-box"); 
  }
  function unload() {
    localStorage.setItem("Joseph's text-box", document.getElementById("Joseph's notes").innerHTML);
  }
  </script>

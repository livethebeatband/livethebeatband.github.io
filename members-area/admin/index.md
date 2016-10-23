---
layout: page
permalink: /members-area/admin/
---
<body onpageshow="load()">
<h1> Admin </h1>

Any important information will appear here:

No information available

Daniel's notes:

<textarea id="Daniel's notes" rows="4" cols="50">
</textarea>

William's notes:

<textarea id="William's notes" rows="4" cols="50">
</textarea>

Astrid's notes:

<textarea id="Astrid's notes" rows="4" cols="50">
</textarea>

Helen's notes:

<textarea id="Helen's notes" rows="4" cols="50">
</textarea>

Rohan's notes:

<textarea id="Rohan's notes" rows="4" cols="50">
</textarea>

Joseph's notes:

<textarea id="Joseph's notes" rows="4" cols="50">
</textarea>

Michael's notes:

<textarea id="Michael's notes" rows="4" cols="50">
</textarea>

<script>
  function load() {
    document.getElementById("Daniel's notes").innerHTML = localStorage.getItem("Daniel's text-box"); 
    document.getElementById("William's notes").innerHTML = localStorage.getItem("William's text-box"); 
    document.getElementById("Astrid's notes").innerHTML = localStorage.getItem("Astrid's text-box"); 
    document.getElementById("Helen's notes").innerHTML = localStorage.getItem("Helen's text-box"); 
    document.getElementById("Rohan's notes").innerHTML = localStorage.getItem("Rohan's text-box"); 
    document.getElementById("Joseph's notes").innerHTML = localStorage.getItem("Joseph's text-box"); 
    document.getElementById("Michael's notes").innerHTML = localStorage.getItem("Michael's text-box"); 
  }
  </script>

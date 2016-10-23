---
layout: page
permalink: /members-area/admin/
---
<body onpageshow="load()">
<h1> Admin </h1>

Any important information will appear here:

No information available
<br/>
Daniel's notes:
<br/>
<textarea id="Daniel's notes" rows="4" cols="50">
</textarea>
<br/>
William's notes:
<br/>
<textarea id="William's notes" rows="4" cols="50">
</textarea>
<br/>
Astrid's notes:
<br/>
<textarea id="Astrid's notes" rows="4" cols="50">
</textarea>
<br/>
Helen's notes:
<br/>
<textarea id="Helen's notes" rows="4" cols="50">
</textarea>
<br/>
Rohan's notes:
<br/>
<textarea id="Rohan's notes" rows="4" cols="50">
</textarea>
<br/>
Joseph's notes:
<br/>
<textarea id="Joseph's notes" rows="4" cols="50">
</textarea>
<br/>
Michael's notes:
<br/>
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

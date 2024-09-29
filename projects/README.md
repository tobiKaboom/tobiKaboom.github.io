 <style>
body {
  background-color: #242424;
}
</style> 

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.collapsible {
  background-color: #202020;
  color: #4E5283;
  cursor: pointer;
  margin-left: 10px;
  padding: 6px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 25px;
}

.active, .collapsible:hover {
  font-size: 27px;
  color: #7871AA;
}

.content {
  padding: 0 0px;
  display: none;
  overflow: hidden;
  background-color: #202020;
} 
 
body {
  font-family: "Lato", sans-serif;
}

.sidenav {
  height: 100%;
  width: 180px;
  position: fixed;
  z-index: 1;
  top: 0;
  left: 0;
  background-color: #202020;
  overflow-x: hidden;
  padding-top: 20px;
}

.sidenav a {
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 25px;
  color: #4E5283;
  display: block;
}

.sidenav a:hover {
  font-size: 27px;
  color: #7871AA;
}

.main {
  margin-left: 160px; /* Same as the width of the sidenav */
  font-size: 28px; /* Increased text to enable scrolling */
  padding: 0px 10px;
}

@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}
</style>
</head>
<body>

<div class="sidenav">
  <a href="/">home</a>
  <a style="color: #7871AA; font-size: 26px">projects </a>
  <a href="/projects">deimos </a>
  <a href="/b">random</a>
  <a href="/cookies">cookies! 🍪</a>
</div>

<div class="main">
  <p style="color: #4E5283; font-size: 28px">all ma projects </p>
  <p style="color: #7871AA; font-size: 22px">stroke </p>
  <p style="color: #4E5283; font-size: 18px">status: stagnant progress. </p>
  <p style="color: #4E5283; font-size: 18px">to do: order and test pcb, complete firmware </p>
  <p style="color: #4E5283; font-size: 18px; href=https://www.github.com.tobikaboom/stroke">link: https://www.github.com/tobiKaboom/stroke (currently private) </p>
  <p style="color: #7871AA; font-size: 22px">deimos </p>
  <p style="color: #4E5283; font-size: 18px">status: completed, tested and working. </p>
  <p style="color: #4E5283; font-size: 18px; href=https://www.github.com.tobikaboom/deimos">link: https://www.github.com/tobiKaboom/deimos </p>
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  });
}
</script>
   
</body>
</html> 

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
  background-color: #777;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
}

.active, .collapsible:hover {
  background-color: #555;
}

.content {
  padding: 0 10px;
  display: none;
  overflow: hidden;
  background-color: #111;
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
  <a style="font-size: 26px;color: #7871AA;" 
     href="/">home</a>
   <button type="button" class="collapsible">projects</button>
<div class="content">
  <a href="/projects">deimos</a>
</div> 
  <a href="/b">random</a>
  <a href="/cookies">cookies! 🍪</a>
</div>

<div class="main">
  <p style="color: #4E5283">welcome to the jankiest website ever made</p>
</div>
   
</body>
</html> 

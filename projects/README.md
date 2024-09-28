 <style>
body {
  background-color: #242424;
}
</style> 

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
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
  <a style="font-size: 26px;color: #7871AA; 
   "href="/projects">projects</a>
  <a href="/b">random</a>
  <a href="/cookies">cookies! 🍪</a>
</div>

<div class="main">
  <p style="color: #4E5283">this is the projects page! </p>
  <p style="color: #4E5283">here i talk about the projects i am working on, update anyone interested on how far i am from completion and serves as a kind of journal. </p>
</div>
   
</body>
</html> 

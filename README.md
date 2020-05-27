<html>

<head>
<style>
$blue: #a3d5d3;

body {
  background-color: $blue;
  padding: 40px;
  text-align: center;
}

.header{
  height: 100vh;
  background-color: white;
  padding: 30px;
  text-align: center;
}

.project-tile {
  background-color: black;
  color: white;
  padding: 30px;
}
.navbar {
  overflow: hidden;
  background-color: #333;
  position: fixed; /* Set the navbar to fixed position */
  top: 0; /* Position the navbar at the top of the page */
  width: 100%; /* Full width */
}

/* Links inside the navbar */
.navbar a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change background on mouse-over */
.navbar a:hover {
  background: #ddd;
  color: black;
}

/* Main content */
.main {
  margin-top: 30px; /* Add a top margin to avoid content overlay */
}

@media only screen and (max-width: 1300px) {
  .project-tile {
    background-color: green;
    color: orange; 
  }
}

</style>
</head>

<body>

<div class="navbar">
  <a href="#welcome-section">Home</a>
  <a href="#projects">Projects</a>
  <a href="#contact">Contact</a>
  <a href="https://github.com/harald1803" target="_blank">Github</a>
</div>
<div class="header">
   <section id="welcome-section">
<h1>Harald sin portfolio</h1>

  <h2>welcome</h2>
    </section>
    </div>

<div class="project-tile" > 
  <section id="projects">
  <h2>python</h2>
    
  </section>
</div>
  


<script>
document.getElementsByTagName("h1")[0].style.fontSize = "60px";
</script>

</body>
</html>

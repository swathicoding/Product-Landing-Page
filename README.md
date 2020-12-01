<html>
<style>
* {
  margin: 0;
  padding: 0;
}
/* box-sizing and font sizing */
*,
*::before,
*::after {
  box-sizing: inherit;
}
html {
  box-sizing: border-box;
}
ul {
  list-style: none;
  }
.navbar {
  background-color: #be3144;
  display: flex;
  justify-content: flex-end;
align-items: center;
  position: fixed;
  top: 0;
  left: 0;
height: 80px;
  width: 100%;
  }
.barlist {
  display: flex;
  padding: 15px;
  margin: 0 3px;
}
.barlist a {
  text-decoration: none;
  color: white;
  padding: 15px;
}
.barlist a:hover {
  background-color: #45567d;
}
.welcome-section {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  width: 100%;
  height: 100vh;
  background-color: #303841;
  color: white;
  }
.welcome-section > p {
  font-weight: 200;
  font-style: italic;
  color: red;
  font-size: 2rem;
}
.projects {
  text-align: center;
  width: 100%;
  background-color: #45567d;
}
.pheader {
  width: 600px;
  margin: 0 auto 40px auto;
  padding: 15px;
  color: white;
  border-bottom: 3px solid white;
 }
.projects-grid {
  display: grid;
    grid-template-columns: auto auto auto;
  grid-gap: 10px;
  padding: 30px;
}
.project-image {
  height: 400px;;
  width: 100%;
  margin: 0;
}
.project-title {
  background-color: grey;
  padding: 15px;
  margin: 0;
}
figcaption {
text-decoration: none;
color:white;
}
.contact {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  width: 100%;
  margin: 0 auto;
height: 50vh;
  padding: 15px;
  background-color: #303841;
  border-bottom: 2px solid #be3144;
}
.contact-header {
 text-align: center;
color: white;
margin: 0 auto;
}
.contactlinks {
  display: flex;
  justify-content: center;
  padding: 20px;
  width: 100%;
  margin: 10px;
}
.contactlinks > a {
  text-decoration: none;
font-style:italic;
  color: white;
  padding: 15px;
  justify-content: space-evenly;
}
footer {
  display: flex;
  justify-content: space-evenly;
  flex-direction: row;
  background-color: #303841;
height: 10vh;  
padding: 10px;
}
.footer > p {
    color: white;
}
</style>
<body>

<header>
     <nav id="top" class="navbar">
      <ul class="barlist">
        <li><a href="#welcome-section"> About </a></li>
        <li><a href="#projects"> Work </a></li>
        <li><a href="#contact"> Contact</a></li>
    </nav><br>
  <section id="welcome-section" class="welcome-section">
    <h1>Hey i am Mimic</h1>
    <p> a web developer</p>
  </section>




  <section id="projects" class="projects">

    <h2 class="pheader"> These are some of my projects</h2>
      
	<div class="projects-grid">

    <figure>
    <a href="https://codepen.io/freeCodeCamp/full/qRZeGZ" target="_blank"
      class="project project-tile">
      <img class="project-image"
src="https://raw.githubusercontent.com/freeCodeCamp/cdn/master/build/testable-projects-fcc/images/random-quote-machine.png" alt="project"/>
      <figcaption class="project-title">Random Quote Machine</figcaption>
</a>
</figure>

<figure>
    <a href="https://codepen.io/freeCodeCamp/full/zNqgVx" target="_blank"
      class="project project-tile">
      <img class="project-image"
src="https://raw.githubusercontent.com/freeCodeCamp/cdn/master/build/testable-projects-fcc/images/tribute.jpg" alt="project"/>
      <figcaption class="project-title">Tribute Page</figcaption>
</a>
</figure>

    <figure>
    <a href="https://codepen.io/freeCodeCamp/full/wgGVVX" target="_blank">
    <img class="project-image"     src="https://raw.githubusercontent.com/freeCodeCamp/cdn/master/build/testable-projects-fcc/images/calc.png" alt="project"/>
      <figcaption class="project-title">Javascript Calculator</figcaption>
</a>
</figure>

<figure>
    <a href="https://codepen.io/freeCodeCamp/full/mVEJag" target="_blank">
      <img class="project-image" src="https://raw.githubusercontent.com/freeCodeCamp/cdn/master/build/testable-projects-fcc/images/map.jpg"
        alt="project" />
      <figcaption class="project-title">Wikipedia Viewer</figcaption>
</a>
</figure>

<figure>
    <a href="https://codepen.io/freeCodeCamp/full/wGqEga" target="_blank">
      <img class="project-image"
        src="https://raw.githubusercontent.com/freeCodeCamp/cdn/master/build/testable-projects-fcc/images/wiki.png"
        alt="project" />
      <figcaption class="project-title">Random Quote Machine</figcaption>
</a>
</figure>

<figure>
   <a href="https://codepen.io/freeCodeCamp/full/KzXQgy" target="_blank">
      <img class="project-image" src="https://raw.githubusercontent.com/freeCodeCamp/cdn/master/build/testable-projects-fcc/images/tic-tac-toe.png" alt=s"project"/>
      <figcaption class="project-title">Tic Tac Toe Game</figcaption>
</figure>

</div>

     </section>



  <section class="contact">
    <div class="contact-header">
    <h2>Let's work together....</h2>
    <p>How do you take your coffee?</p>
    </div>
    <div class="contactlinks">
    <i class="fab fa-facebook-square">Facebook</i>
      <a href="https://facebook.com/freecodecamp" alt="Facebook"><i class="fab fa-github"></i> Github</a>
      <a href="https://facebook.com/freecodecamp" alt="Facebook"><i class="fab fa-twitter"></i> Twitter</a>
      <a id="profilellink" href="https://facebook.com/freecodecamp" target="_blank" alt="Facebook"><i class="fas fa-mobile-alt"></i> callme</a>
    </div>
       </section>
 <footer>
   <div class="footer">
     <p>
    **This is just a fake portfolio. All the projects and contact details given are not real.
  </p>
  <p>
    &copy; Created for
    <a href="https://www.freecodecamp.com/" target="_blank"
      >freeCodeCamp <i class="fab fa-free-code-camp"></i></a>
  </p>
       </div>
       </footer>
</body>
</html>
      

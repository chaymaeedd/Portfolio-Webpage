# Portfolio-Webpage
<nav id="navbar">
  <a href="#welcome-section">About</a>
  <a href="#projects">Projects</a>
  <a href="#social">Social</a>
</nav>

<header id="welcome-section">
  <h1>Hello!</h1>
  <p>My name is Chaymae Eddouks</p>
  <p>and I am a Web Developer</p>
</header>

<section id="projects">
<h2>Projects</h2>
 <div class="projects-container">
  <a href="https://codepen.io/your-work" target="_blank" class="project-tile"><img src="https://codepen.io/Chaymaeedd/pen/vYKRMRq/image/large.png" alt="Survey form">
    <p>Survey Form</p>
    
  </a>
  <a href="https://codepen.io/your-work" target="_blank" class="project-tile"><img src="https://codepen.io/Chaymaeedd/pen/yLJvzyQ/image/large.png" alt="tribute page">
    <p>Tribute Page</p>
    
  </a>
  <a href="https://codepen.io/your-work" target="_blank" class="project-tile"><img src="https://codepen.io/Chaymaeedd/pen/ZEORLWZ/image/large.png" alt="Technical docummentation">
    <p>Technical Documentation Page</p>
    
  </a>
  <a href="https://codepen.io/your-work" target="_blank" class="project-tile"><img src="https://codepen.io/Chaymaeedd/pen/mdELRmX/image/large.png" alt="Product landing page">
    <p>Product Landing Page</p>
    
  </a>
 
</section>
<section id="social" class="bg-pink">
<h2>Social Media</h2>
<p>You can find me on</p>
   <ul class="social-ul">
     <li><a href="https://twitter.com/c_eddouks" target="_blank"><i class="fab fa-twitter"></i></a></li>
     <li><a href="https://www.instagram.com/chaymaeedd/" target="_blank"><i class="fab fa-instagram"></i></a></li>
     <li><a href="https://www.facebook.com/people/Chaymae-Eddouks/100011037726265" target="_blank"><i class="fab fa-facebook"></i></a></li>
     <li><a href="https://www.linkedin.com/in/chaymae-eddouks-a48aa01b7/" target="_blank"><i class="fab fa-linkedin"></i></a></li>
     <li><a id="profile-link"
       href="https://github.com/chaymaeedd" target="_blank"><i class="fab fa-github"></i></a></li>
   </ul>
</section>

<footer>Made with <i class="fas fa-heart"></i> by Chaymae Eddouks </footer>

@import url('https://fonts.googleapis.com/css2?family=Lato:wght@700&display=swap');
* {
  box-sizing: border-box;
}
body {
  background-color: #FBCF0CC;
  font-family: 'lato', sans-serif;
  margin: 0;
}
nav {
  background-color: #A64253;
  color: #fff;
  display: flex;
  justify-content: flex-end;
  padding: 15px;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 100;
}
nav a {
  color: #fff;
  margin-left: 20px;
  text-decoration: none;
}
nav a:hover {
  text-decoration: underline;
}
section {
  padding: 30px;
  text-align: center;
}
section h2 {
  margin: 0;
}
.projects-container {
  display: flex;
  flex-wrap: wrap; 
  align-items: center;
  justify-content: center; 
  max-width: 810px;
  margin: 20px auto 0;
}
.project-tile {
  color: #000;
  margin: 10px;
  max-width: 250px;
  text-decoration: none;
  transition: transform 0.3s ease;
}
.project-tile:hover {
  transform: scale(1.05);
}
.project-tile img {
  max-width: 100%;
}
.project-tile p {
  font-size: 20px;
  margin-top: 10px;
}

.bg-pink {
  background-color: #A64253;
  color: #fff;
}
.social-ul {
  list-style-type: none;
  display: flex;
  flex-wrap: wrap;
  padding: 0;
  margin: 0;
  justify-content: center;
}
.social-ul a {
  color: #fff;
  font-size: 20px;
  margin: 0 10px;
  
}
header {
  background-image: url('https://images.unsplash.com/photo-1534972195531-d756b9bfa9f2?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80');
  color: #fff;
  background-position: center center;
  background-size: cover;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  position: relative;
  height: 100vh;
}
header::after {
  content: '';
  background-color: #000;
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  opacity: 0.4;
 }
header * {
  position: relative;
  z-index: 1;
}
header h1 {
  font-size: 50px;
 
}
header p {
  font-size: 30px;
  margin: 0;
}

footer {
  background-color: #E5958E;
  color: #fff;
  padding: 10px;
  text-align: center;
}

footer .fa-heart {
  color: red;
}
@media (max-width:440px) {
  section{
    padding: 20px;
  }
}

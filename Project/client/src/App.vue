<template>
  <div id="app">
        <div class="navbar navbar-inverse navbar-static-top">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle" data-toggle="collapse" data-target=".navbar-collapse">
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="index.html">Mim</a>
        </div>
        <div class="navbar-collapse collapse">
          <ul class="nav navbar-nav navbar-right">
            <li><a href="#about">About</a></li>
            <li><a href="#BLOG">Write Anything</a></li>
            <li><a href="#work">Work</a></li>

          </ul>
        </div><!--nav end -->
      </div>
    </div>

  <!--Welcome Section -->
  <div id="ww">
      <div class="container">
      <div class="row">
        <div class="col-lg-8 col-lg-offset-2 centered">
          <img class='profile' src="./assets/img/me.jpg" alt="mim">
          <h1>Hi, I am Jhuma Kabir Mim</h1>
<p>Hello everybody. I'm Jhuma Kabir Mim; I'm doing a course in fulstack development design. This is the project I have done.</p>
<p>Here, first, I have set up the file structure, added a GitHub repository, and watched all the lectures. I have used the previous frontend template that I created for the frontend development course. Now here I have converted that HTML template inside the VUE app and added a small section for writing anything. Basically, anyone can write anything here, and it will post to the MongoDB server. It looks simple; however, I have made an API and perform Get, Delete and Post requests.</p>
        
        </div><!-- /col-lg-8 -->
      </div><!-- /row -->
      </div> <!-- /container -->
  </div>


    <!-- about section-->

    <div id="about" class="parallax">

      <div class="container pt"  >
            <div class="row mt centered"> 
              <div class="col-lg-3">
                <span class="glyphicon glyphicon-book"></span>
                <p>I love to read books.</p>
              </div>
              
              <div class="col-lg-3">
                <span class="glyphicon glyphicon-user"></span>
                <p>I love to make new friends.</p>
              </div>

              <div class="col-lg-3">
                <span class="glyphicon glyphicon-fire"></span>
                <p>Nothing can stop me InShaAllah.</p>
              </div>

              <div class="col-lg-3">
                <span class="glyphicon glyphicon-globe"></span>
                <p>I want to travel the whole world.</p>
              </div>
            </div><!-- /row -->
            
            <div class="row">
              <div class="col-lg-6">
                <h4>THE Parallax Example</h4>
                <p>In this section, I have made a small parallax example. I have used a background image and set it as a fixed position.</p>
              </div><!-- /colg-lg-6 -->
              
              <div class="col-lg-6">
                <h4>My SKILLS</h4>
                Machine learning
                <div class="progress">
                  <div class="progress-bar progress-bar-theme" role="progressbar" aria-valuenow="60" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
                    <span class="sr-only">60% Complete</span>
                  </div>
                </div>

                Python
                <div class="progress">
                  <div class="progress-bar progress-bar-theme" role="progressbar" aria-valuenow="80" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
                    <span class="sr-only">80% Complete</span>
                  </div>
                </div>
                
                HTML + CSS + Javascript
                <div class="progress">
                  <div class="progress-bar progress-bar-theme" role="progressbar" aria-valuenow="95" aria-valuemin="0" aria-valuemax="100" style="width: 60%;">
                    <span class="sr-only">95% Complete</span>
                  </div>
                </div>

              </div><!-- /col-lg-6 -->
            </div><!-- /row -->
       </div><!-- /container -->

    </div>

    <a class="weatherwidget-io" href="https://forecast7.com/en/61d0528d19/lappeenranta/" data-label_1="LAPPENRANTA" data-theme="original" >LAPPENRANTA</a>

  


     <!-- portfolio section -->
  
  <div id="BLOG">
    <post-component msg="Welcome to Your Vue.js App"/>

  </div><!-- /container -->



  <!-- portfolio section -->
  
  <div id="work" class="container pt">
    <div class="row mt centered"> 
      <center><h1>What I do? Grid Layout Example</h1></center>
      
      <div class="col-xs-6 col-sm-6 col-md-6 col-lg-4">
        <a class="zoom green" href="#"><img class="img-responsive" src="./assets/images/1.jpg" alt="" /></a>
        <p>Researcher</p>
      </div>
      <div class="col-xs-6 col-sm-6 col-md-6 col-lg-4">
        <a class="zoom green" href="#"><img class="img-responsive" src="./assets/images/2.jpg" alt="" /></a>
        <p>Traveler</p>
      </div>
      <div class="col-xs-6 col-sm-6 col-md-6 col-lg-4">
        <a class="zoom green" href="#"><img class="img-responsive" src="./assets/images/3.png" alt="" /></a>
        <p>Hicking</p>
      </div>


    </div><!-- /row -->

  </div><!-- /container -->

 

      <!-- footer section-->
  
  <div id="footer">
    <div class="container">
      <div class="row">
        <div class="col-lg-4">
          <h4>My Address</h4>
          <p>
            Korpraalinkuja 3, 110 ,<br/>
            +3580449353419, <br/>
          LUT University.
          </p>
        </div><!-- /col-lg-4 -->
        
        <div class="col-lg-4">
          <h4>My Links</h4>
          <p>

            <a href="https://scholar.google.com/citations?user=dALoMeAAAAAJ&hl=en&authuser=1&oi=ao">Google Scholar</a><br/>
            <a href="https://github.com/Meem007">GitHub</a>
          </p>
        </div><!-- /col-lg-4 -->
        
        <div class="col-lg-4">
          <h4>About </h4>
          <p>Im creating this front-end layout for my personal development.</p>
        </div><!-- /col-lg-4 -->
      
      </div>
    
    </div>
  </div>

  </div>
</template>

<script>
import PostComponent from "./components/PostComponent.vue";

export default {
  name: "app",
  components: {
    PostComponent
  }
};

!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src='https://weatherwidget.io/js/widget.min.js';fjs.parentNode.insertBefore(js,fjs);}}(document,'script','weatherwidget-io-js');
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0px;
}


@import url(http://fonts.googleapis.com/css?family=Montserrat:400,700);

img.profile {
    width: 100px;
    border-radius: 50px;
}

body {
    background-color: #ffffff;
    font-family: 'Montserrat', sans-serif;
    font-weight: 400;
    font-size: 14px;
    color: #555;

    -webkit-font-smoothing: antialiased;
    -webkit-overflow-scrolling: touch;
}

/* Titles */
h1, h2, h3, h4, h5, h6 {
  font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    color: #333;
}

h1 {
  font-size: 35px;
  margin-top: 30px;
  margin-bottom: 30px;


}


/* footer section css */

#ww {
    padding-top: 70px;
    padding-bottom: 70px;
    background-color: #f2f2f2;
}


#footer {
    background-color: #2f2f2f;
    padding-top: 50px;
    padding-bottom: 50px; 
}

#footer p {
    color: white;
}

#footer h4 {
    color: white;
    text-transform: uppercase;
    padding-bottom: 20px;
}

/* Padding Margin*/

.mt {
    margin-top: 40px;
    margin-bottom: 40px;
}

.pt {
    padding-top: 50px;
    padding-bottom: 50px;
}


/* Portfolio*/


a.zoom.green img {
    max-height: 500px;
}

/* navigations and Links */
a {
    color: #1abc9c;
    word-wrap: break-word;

    -webkit-transition: color 0.1s ease-in, background 0.1s ease-in;
    -moz-transition: color 0.1s ease-in, background 0.1s ease-in;
    -ms-transition: color 0.1s ease-in, background 0.1s ease-in;
    -o-transition: color 0.1s ease-in, background 0.1s ease-in;
    transition: color 0.1s ease-in, background 0.1s ease-in;
}

a:hover,
a:focus {
    color: #7b7b7b;
    text-decoration: none;
    outline: 0;
}

a:before,
a:after {
    -webkit-transition: color 0.1s ease-in, background 0.1s ease-in;
    -moz-transition: color 0.1s ease-in, background 0.1s ease-in;
    -ms-transition: color 0.1s ease-in, background 0.1s ease-in;
    -o-transition: color 0.1s ease-in, background 0.1s ease-in;
    transition: color 0.1s ease-in, background 0.1s ease-in;
}

 hr {
    display: block;
    height: 1px;
    border: 0;
    border-top: 1px solid #ccc;
    margin: 1em 0;
    padding: 0;
}


.navbar {
    text-transform: uppercase;
    margin-bottom: 0px;
}

.navbar-inverse {
    padding-bottom: 20px;
    padding-top: 20px;
}

.navbar-inverse {
    background-color: #1abc9c;
    border-color: #16a085;
}

.navbar-inverse .navbar-nav > li > a {
    color: white;
}

.navbar-inverse .navbar-nav > li > a:hover {
    color: #222222;
}

.navbar-brand {
    font-weight: 700;
    font-size: 20px;
    letter-spacing: 2px;
}

.navbar-inverse .navbar-brand {
    color: white;
}

.navbar-inverse .navbar-toggle {
    border-color: transparent;
}

.progress-bar-theme {
  background-color: #1abc9c;
}

  /* Create the parallax scrolling effect */
.parallax {
  /* The image used */
  background-image: url('./assets/paralax.webp');

  /* Full height */
  height: 100%; 


  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}


/* icon Configuration */

.glyphicon {
    font-size: 40px;
    color: #1abc9c;
}

/* slide show */
* {box-sizing:border-box}

/* Slideshow container */
.slideshow-container {
  
  position: relative;
  margin: auto;
}

/* Hide the images by default */
.mySlides {
  display: none;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 3s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 3s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  animation-name: fade;
  animation-duration: 3s;
}
div#BLOG {
    BACKGROUND: #93c4a6;
    padding-top: 35px;
    padding-bottom: 57px;
}

@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}
</style>

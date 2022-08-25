<template>
<div class="body">
  </div>
     <b-navbar toggleable="lg" type="dark" variant="danger"> </b-navbar>
  <b-container>
  <b-navbar toggleable="lg" type="dark" variant="danger">
     <b-navbar-toggle target="nav-collapse"></b-navbar-toggle></b-navbar>
     </b-container>
<div class="container-center">
  <div class="card">
      <theme-button />
<div class="I" >
<br><br><img alt="Vue logo" class="perfil" src="../assets/logo.png">
<div>
</div>
<br><br> <h1>Hello, I´m Juanfe</h1>
<p>
I am a junior front-end developer. It seems to me that the world of technolog
It is interesting and extensive because the
job opportunities it offers are good and growing
professionally day by day helps us to collaborate in
this collaborative environment.</p>
</div>
<div class="A" id="about">
<br><br> <h1>About me</h1>
<p>Since I was little I have found computer systems interesting, so I decided to study
a computer systems technician in my city (Pensilvania-Caldas)
and take different web development courses to expand
my knowledge, to be able to contribute to society, collaborate to build it in a better way.</p>
</div>
<div class="P" id="proyects" >
<br><br> <h1>Proyects</h1>
<div class="view">
<div class="i"> <h2> Demo day: </h2> <br> <img class="po"
src="../assets/food.gif" alt="demo day"> <br>
<a href="https://github.com/juanfetm/Demo-Day" target="_blank">
    <button class="go">go</button>
  </a> </div>
<div class="o"><br><br>  <h2>CV:</h2> <br> <img class="po" src="../assets/cv.gif" alt="cv"> <br>
<a href="https://github.com/juanfetm/CV" target="_blank">
    <button class="go">go</button>
  </a></div>
<div class="u"> <h2>Proyects:</h2> <br> <img class="po" src="../assets/portafolio.gif"
alt="portafolio"> <br>  <a href="https://github.com/juanfetm/portafolio" target="_blank">
    <button class="go">go</button>
  </a> </div>
</div>
</div> <br>
  <div class="E" id="studies" >
<br><br>   <h1>Studies</h1>
<p>I am a professional computer systems technician,
Front End Developer with knowledge in HTML, CSS, JS, VUE,
GRID, FLEX. intermediate excel.</p>
<div class="Studies">
<br><br>   <img class="stu" src="../assets/prosper.png" alt="prosper">
<img  class="stu" src="../assets/ies.png" alt="ies">
<img  class="stu" src="../assets/platzi.png" alt="platzi">
<img  class="camcop" src="../assets/camcop.png" alt="camcop">
</div>
</div>
  <div class="T" id="testimonials">
<br><br> <h1>Testimonials</h1>
<p>I am part of the prospercity community and I demonstrated
 it when I participated in "100 Pensilvania opportunities
 for the world", held in Pensilvania caldas colombia,
 where I shared my testimony with hundreds of people
 so that they would be motivated to study web
development, to have a better life quality.<br><br> <br><br> </p>

<!-- slider -->
<div class="container">
  <ul class="slider">
    <li id="slide1">
     <img src="../assets/sli1.jpg" alt="photo">
    </li>
    <li id="slide2">
      <img src="../assets/sli2.jpg" alt="photo">
    </li>
    <li id="slide3">
    <img src="../assets/sli3.jpg" alt="photo">
    </li>
    <li id="slide4">
    <img src="../assets/sli4.jpg" alt="photo">
    </li>
  </ul>
  <ul class="menu">
    <li>
      <a href="#slide1">1</a>
    </li>
    <li>
      <a href="#slide2">2</a>
    </li>
     <li>
      <a href="#slide3">3</a>
    </li>
         <li>
      <a href="#slide4">4</a>
    </li>
  </ul>
</div>
</div>
  <div class="W" id="working">
<br><br> <h1>Interesting in working together</h1>
  <p>I am looking to have a great professional experience
 as a Developer, willing and open to continue
 learning new technologies, and strengthen
current knowledge<br><br> <br><br> </p>
</div>
</div>
</div>
</template>

<script lang="ts">
export default ({
  name: 'ContentComponent',
});
</script>

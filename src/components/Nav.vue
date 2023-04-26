<template>
  <nav class="navbar navbar-expand-lg bg-black sticky-top ">
  <div class="container-fluid">
     <img class="brandon-swinton-1" src="https://i.postimg.cc/ryC8s1gC/BRANDON-SWINTON.png" />
    <a class="navbar-brand text-white" href="#">Mr.Swinton</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a  class="nav-link"  aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#aboutpage">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#testimonials">Testimonials</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#skills">Skills</a>
        </li>
         <li class="nav-item">
          <a class="nav-link" aria-current="page" href="#resume">Resume</a>
        </li>
          <li class="nav-item">
          <a class="nav-link"  aria-current="page" href="#projects">Projects</a>
        </li>
          <li class="nav-item">
          <a class="nav-link ">Contact Me</a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
export default {

}
</script>

<style>
.nav-link , .navbar-brand{
  font-family: 'Rubik', sans-serif;

}


.nav-item * {
  box-sizing: border-box;
  transition: all .35s ease;
}


.nav-item a {
  padding: .5em .8em;
  color: white;
  position: relative;
  text-decoration: none;
}

.nav-item a::before,
.nav-item a::after {
  content: '';
  height: 14px;
  width: 14px;
  position: absolute;
  transition: all .35s ease;
  opacity: 0;
}

.nav-item a::before {
  content: '';
  right: 0;
  top: 0;
  border-top: 3px solid #ff0000;
  border-right: 3px solid #ff0000;
  transform: translate(-100%, 50%);
}

.nav-item a:after {
  content: '';
  left: 0;
  bottom: 0;
  border-bottom: 3px solid #ff0000;
  border-left: 3px solid #ff0000;
  transform: translate(100%, -50%)
}

.nav-item a:hover:before,
.nav-item a:hover:after{
  transform: translate(0,0);
  opacity: 1;
}

.nav-item a:hover {
  color: #ff0000;
}
.brandon-swinton-1{
  width: 5rem;
}
</style>
<template>
<section id="home">
<div class="container-fluid">
    <div class="row">
  <div class="col-4">
    
   <img class="brandon-swinton-1" src="https://i.postimg.cc/7hHcW3NX/BRANDON.png"/>

  <div class="hello2">Hello !</div>
    <div class="Subtext">MY NAME IS </div>
      <div class="Subtext2">BRANDON SWINTON </div>
      <div class="Subtext3">Full-Stack Developer</div>


      
    </div>
    <div class="col-4">
      
        <svg
    class="rectangle-10"
    width="582"
    height="565"
    viewBox="0 0 582 565"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path
      d="M0 92C0 41.1898 41.1898 0 92 0H299.5C455.52 0 582 126.48 582 282.5V508C582 539.48 556.48 565 525 565H248C111.033 565 0 453.967 0 317V92Z"
      fill="url(#paint0_linear_22_73)"
    />
    <defs>
      <linearGradient
        id="paint0_linear_22_73"
        x1="-837.5"
        y1="110.449"
        x2="-837.5"
        y2="675.449"
        gradientUnits="userSpaceOnUse"
      >
        <stop stop-color="#A60000" stop-opacity="0" />
        <stop offset="1" stop-color="#A60000" />
      </linearGradient>
    </defs>
  </svg>
    </div>
  </div>
</div>
</section>
</template>

<script>
export default {
  name: 'home',
 
}
</script>


<style scoped>
#home{
  background-color: black;
  height: 100vh;
}
.hello,
.hello * {
  box-sizing: border-box;
}
.hello {
  position: absolute;
  inset: 0;
}
.brandon-swinton-1 {
  width: 200px;
  position: absolute;
  left: 180px;
  top: 200px;
}
.hello2 {
  color: #ffffff;
  text-align: center;
  font: 900 96px "Poppins", sans-serif;
  position: absolute;
  left: 360px;
  top: 250px;
  display: flex;
  align-items: center;
  justify-content: center;
}

.Subtext{
    color: #ffffff;
  text-align: center;
  font:  30px 'Bebas Neue', cursive;
  font-weight: 600;
  position: absolute;
  left: 250px;
  top: 358px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.Subtext2{
  color: #ff0000;
  text-align: center;
  font: 800 34px 'Bebas Neue', cursive;
  position: absolute;
  left: 360px;
  top: 355px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.Subtext3{
      color: #ffffff;
  text-align: center;
  font:  20px 'Bebas Neue', cursivef;
  font-weight: 600;
  position: absolute;
  left: 360px;
  top: 395px;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>

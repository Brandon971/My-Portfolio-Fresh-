<template>

 <section id="skills">
    <div><h1 class="skillsTitle">SKILLS</h1></div>
<div class="container ">
  <div class="card">
      <img src="https://i.postimg.cc/CK5KyQWG/pngwing-com.png" alt="">
    <div class="circle">
      <svg version="1.1" xmlns="http://www.w3.org/2000/svg">
      <circle class="stroke" cx="60" cy="60" r="50"/>
    </svg>
    </div>
  </div>
  <div class="card">
    <img src="https://i.postimg.cc/8cY8qTrW/pngwing-com-1.png" alt="">
    <div class="circle">
      <svg version="1.1" xmlns="http://www.w3.org/2000/svg">
      <circle class="stroke" cx="60" cy="60" r="50"/>
    </svg>
    </div>
  </div>
  <div class="card">
    <img src="https://i.postimg.cc/wj4pNcBF/pngwing-com-2.png" alt="">
    <div class="circle">
      <svg version="1.1" xmlns="http://www.w3.org/2000/svg">
      <circle class="stroke" cx="60" cy="60" r="50"/>
    </svg>
    </div>
  </div>
  <div class="card">
    <h3 class="title mx-5 text-black">VUE</h3>
    <img class="pt-5" src="https://i.postimg.cc/L8drd9sk/pngwing-com-4.png" alt="">
    
    <div class="circle">
      <svg version="1.1" xmlns="http://www.w3.org/2000/svg">
      <circle class="stroke" cx="60" cy="60" r="50"/>
    </svg>
    </div>
  </div>
   <div class="card">
    <img src="https://i.postimg.cc/9FzbVfXR/pngwing-com-1.png" alt="">
    <div class="circle">
      <svg version="1.1" xmlns="http://www.w3.org/2000/svg">
      <circle class="stroke" cx="60" cy="60" r="50"/>
    </svg>
    </div>
  </div>
    <div class="card">
    <h3 class="title">BOOTSTRAP</h3>
    <img class="pt-5" src="https://i.postimg.cc/sDv11csf/pngwing-com-6.png" alt="">
    <div class="circle">
      <svg version="1.1" xmlns="http://www.w3.org/2000/svg">
      <circle class="stroke" cx="60" cy="60" r="50"/>
    </svg>
    </div>
  </div>
    <div class="card">
    <img src="https://i.postimg.cc/qRH4BsQR/pngwing-com-7.png" alt="">
    <div class="circle">
      <svg version="1.1" xmlns="http://www.w3.org/2000/svg">
      <circle class="stroke" cx="60" cy="60" r="50"/>
    </svg>
    </div>
  </div>
    <div class="card">
    <img src="https://i.postimg.cc/zBhMB43Z/pngwing-com-8.png" alt="">
    <div class="circle">
      <svg version="1.1" xmlns="http://www.w3.org/2000/svg">
      <circle class="stroke" cx="60" cy="60" r="50"/>
    </svg>
    </div>
  </div>
 
 
</div>
</section>


</template>

<script>
export default {

}
</script>

<style scoped>

#skills{
    min-height: 100vh;
    background-color:rgb(0, 0, 0);

}


.container {
  position: absolute;
  height: 300px;
  width: auto;
  display: flex;
  padding-top: 3%;
  margin-left: 7%;
}

.card {
  display: flex;
  height: 280px;
  width: 300px;
  background-color: #313131;
  border-radius: 10px;
  box-shadow: -1rem 0 3rem #161616;
/*   margin-left: -50px; */
  transition: 0.4s ease-out;
  position: relative;
  left: 0px;
}

.card:not(:first-child) {
    margin-left: -50px;
}

.card:hover {
  transform: translateY(-20px);
  transition: 0.4s ease-out;
}

.card:hover ~ .card {
  position: relative;
  left: 50px;
  transition: 0.4s ease-out;
}

.title {
  color: rgb(0, 0, 0);
  font-weight: 800;
  position: absolute;
  left: 20px;
  top: 15px;
}

.bar {
  position: absolute;
  top: 100px;
  left: 20px;
  height: 5px;
  width: 150px;
}

.emptybar {
  background-color: #2e3033;
  width: 100%;
  height: 100%;
}

.filledbar {
  position: absolute;
  top: 0px;
  z-index: 3;
  width: 0px;
  height: 100%;
  background: rgb(255, 0, 0);
  background: linear-gradient(90deg, rgb(0, 0, 0) 0%, rgb(255, 0, 0) 65%, rgb(7, 0, 0) 100%);
  transition: 0.6s ease-out;
}

.card:hover .filledbar {
  width: 120px;
  transition: 0.4s ease-out;
}

.circle {
  position: absolute;
  top: 150px;
  left: calc(50% - 60px);
}

.stroke {
  stroke: rgb(255, 0, 0);
  stroke-dasharray: 360;
  stroke-dashoffset: 360;
  transition: 0.6s ease-out;
}

svg {
  fill: #2b2b2b;
  stroke-width: 2px;
}

.card:hover .stroke {
  stroke-dashoffset: 100;
  transition: 0.6s ease-out;
}

.skillsTitle{
    padding-top: 10%;
    color: #2e3033;
    font:800 150px "Poppins", sans-serif;
}
</style>
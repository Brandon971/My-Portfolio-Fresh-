<template>
  <section id='projects'>
    <div class="projectTitle">PROJECTS</div>
    <div class="container mx-auto col-9 ">
    <hr>
    <div class="profile-card-4 text-center " v-for="project in Projects" :key="project.id">
      <img :src="project.image" class="img img-responsive w-75">
        <div class="profile-content">
            <div class="profile-name">{{ project.name }}

            </div>
            <div class="row">
                <div class="col-xs-4">
                    <div class="profile-overview">
                      <p>WEB</p>
                        <a :href="project.web" target="_blank"><button class="name noselect">WEB</button></a></div>
                </div>
                <div class="col-xs-4">
                    <div class="profile-overview">
                        <p>GITHUB</p>
                        <a :href="project.github" target="_blank"><button class="name noselect">GITHUB</button></a></div>
                </div>
            </div>
        </div>
    </div>
</div>
  
  </section>
</template>

<script>
export default {

  data(){
        return{
            Projects : [
                {
                    id: 1,
                    name:'ELEMENT',
                    image:'https://i.postimg.cc/vmq5Zc7x/Screenshot-1.png',
                    web:'https://brandons-pos.netlify.app',
                    github:'https://github.com/Brandon971/End-of-module--JS'
                },
                {
                  id: 2,
                  name:'First Portfolio',
                  image:'https://i.postimg.cc/MH4sM9yR/Screenshot-2.png',
                  web:'https://brandons-vue-portfolio.netlify.app',
                  github:'https://github.com/Brandon971/Vue-Portfolio'
                },
                {
                  id: 3,
                  name:'Wanted',
                  image:'https://i.postimg.cc/xT35SjZM/Screenshot-3.png',
                  web:'https://wanted-capstone.netlify.app',
                  github:'https://github.com/Brandon971/Wanted---Capstone'
                },
                {
                  id: 4,
                  name:'Basic Calculator',
                  image:'https://i.postimg.cc/NMQGS421/Screenshot-4.png',
                  web:'https://brandons-basic-calculator.netlify.app',
                  github:'https://github.com/Brandon971/Calculator'
                },
                {
                  id: 5,
                  name:'BMW Motors',
                  image:'https://i.postimg.cc/X7jHqydQ/Screenshot-5.png',
                  web:'https://gleaming-axolotl-f3a6e8.netlify.app',
                  github:'https://github.com/Brandon971/Vue-ecommerce'
                },
                {
                  id: 6,
                  name:'First Eccomerce',
                  image:'https://i.postimg.cc/k5gRtqfr/Screenshot-6.png',
                  web:'https://symphonious-strudel-5a3cbd.netlify.app',
                  github:'https://github.com/Brandon971/Ecommerce'
                }
              ]
              }
}
}
</script>

<style scoped>
#projects{
    min-height: 100vh;
    background-color: black;
}
.profile-card-4 {
    max-width: 300px;
    background-color: #FFF;
    border-radius: 5px;
    box-shadow: 0px 0px 25px rgba(0, 0, 0, 0.1);
    overflow: hidden;
    position: relative;
    margin: 10px auto;
    cursor: pointer;
}
.container{
  display: flex;
  flex-wrap: wrap;
  align-items : center;
  justify-content : center;
  flex-direction: row;
  position: relative;
}
.profile-card-4 img {
    transition: all 0.25s linear;
}

.profile-card-4 .profile-content {
    position: relative;
    padding: 15px;
    background-color:  #ffffff;
}

.profile-name {
    font-weight: bold;
    position: absolute;
    left: 0px;
    right: 0px;
    top: -70px;
    color:  rgb(255, 255, 255);
    background-color: black;
    font-size: 17px;
}

.profile-card-4 .profile-name p {
    font-weight: 600;
    font-size: 13px;
    letter-spacing: 1.5px;
}

.profile-card-4 .profile-description {
    color: #777;
    font-size: 12px;
    padding: 10px;
}

.profile-card-4 .profile-overview {
    padding: 15px 0px;
}

.profile-card-4 .profile-overview p {
    font-size: 10px;
    font-weight: 600;
    color: #777;
}

.profile-card-4 .profile-overview h4 {
    color: #273751;
    font-weight: bold;
}

.profile-card-4 .profile-content::before {
    content: "";
    position: absolute;
    height: 20px;
    top: -10px;
    left: 0px;
    right: 0px;
    background-color: #FFF;
    z-index: 0;
    transform: skewY(3deg);
}

.profile-card-4:hover img {
    transform: rotate(5deg) scale(1.1, 1.1);
    filter: brightness(110%);
}

.noselect {
  -webkit-touch-callout: none;
    -webkit-user-select: none;
     -khtml-user-select: none;
       -moz-user-select: none;
        -ms-user-select: none;
            user-select: none;
		-webkit-tap-highlight-color: transparent;
}

button {
	width: 150px;
	height: 40px;
	cursor: pointer;
   font-family: 'Rubik', sans-serif;
	font-size: 15px;
	font-weight: bold;
	color: rgb(255, 255, 255);
	background: #000000;
	border: 2px solid rgb(0, 0, 0);
	box-shadow: 5px 5px 0 rgb(255, 0, 0),
		-5px -5px 0 black,
		-5px 5px 0 black,
		5px -5px 0 black;
	transition: 500ms ease-in-out;
}

button:hover {
	box-shadow: 20px 5px 0 black, -20px -5px 0 rgb(255, 0, 0);
}

button:focus {
	outline: none;
}

.projectTitle{
  padding-top:5%;
  padding-bottom: 0;
  color: #2e2e2e;
  font: 800 150px 'Poppins' ,sans-serif
}
</style>
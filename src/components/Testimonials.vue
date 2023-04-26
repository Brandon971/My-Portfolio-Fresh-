<template>
  <section id="testimonials">
  <div class="testimonials2">TESTIMONIALS</div>

  <div class="container mx-auto g-5">
    <div v-for="comments in Testimonials" :key="comments.id" class ="card ">

      <div class= "image">
          <img :src="comments.image" alt="...">
      </div>
      <div class = "content">
        <h3>{{ comments.name }} <span class="surname">{{comments.surname}}</span></h3>
        <p class="reference" >{{ comments.reference}}</p>
      </div>
    </div>    
  </div>


  
</section>

</template>

<script>
export default {
     name: 'nice',
    data(){
        return{
            Testimonials : [
                {
                    id: 1,
                    name:'Timothy ',
                    surname:'Jennike',
                    image:'https://i.postimg.cc/FsJGLZym/C11-1.jpg',
                    title:'Developer',
                    reference:'Brandon is hard working guy who completes every project and reaches every goal that he sets for himself.He is friendly and respectful which makes him perfect for the work-environment.'
                },
                {
                    id: 2,
                    name:'Maxwill ', 
                    surname:'Isaacs',
                    image:'https://i.postimg.cc/rwfT9Qj2/Me-Profile-1.jpg',
                    title:'Developer',
                    reference:'Brandon is a very dependable and passion driven person .He is very confident,consistent and gives his all and not afraid to listen to advice from peers .'
                },
                {
                    id: 3,
                    name:'Lindokuhle', 
                    surname:'Mgoqi',
                    image:'https://i.postimg.cc/d3mwvZtZ/DSC-3517.jpg',
                    title:'Developer',
                    reference:'Brandon is dedicated to his craft and always looking for ways to improve it.He is always showing love to those around him'
                },
                {
                    id: 4,
                     name:'Deno', 
                    surname:'Rautenbach',
                    image:'https://i.postimg.cc/3JbvW54P/DSC-3597.jpg',
                    title:'Developer',
                    reference:' A wonderful colleague to work beside. Always there to lend a helping hand when called upon or even offers to help when he can see that a certain task is a handful.'
                },
                {
                  id: 5,
                   name:'Joel ', 
                    surname:'Mukanya',
                  image:'https://i.postimg.cc/R0LyQRBx/1-1.jpg',
                  title:'Lecturer',
                  reference:'Brandon is a very creative, go-getter, and well-behaved student.He has gained knowledge of web development, including Bootstrap 5. I will be very delighted to see him get hired.'
                },
                {
                  id: 6,
                   name:'Candice', 
                    surname:'Amon',
                  image:'https://i.postimg.cc/9MxgMX7y/candice-2022.jpg',
                  title:'Facilitator',
                  reference:'Very disciplined and only focus on the task at hand. His presence demands attention without having to say a word. He is very selective with who he surrounds himself with and loves having meaningful conversations.'
                }
              ]
            }
          }
}

</script>

<style scoped>
#testimonials,
#testimonials * {
  box-sizing: border-box;
}
#testimonials {
  background: #000000;
  min-height: 100vh;
  position: relative;
  overflow: hidden;
}
.testimonials2 {
  color: #2e2e2e;
  text-align: center;
  font: 800 150px "Poppins", sans-serif;
  position: absolute;
  left: 0px;
  top: 0px;
  padding-bottom:6% ;
  height: 391px;
  display: flex;
  align-items: center;
  justify-content: center;
}

* { 
  margin : 0;
  padding: 0;
  box-sizing : border-box;
  font-family : "Poppins", sans-serif;
}


.container {
  position : relative;
  margin-top: 9%;
  width : 1100px;
  display : flex;
  align-items : center;
  justify-content : center;
  flex-wrap : wrap;
  padding : 30px;  
}

.container .card {
  position: relative;
  max-width : 300px;
  height : 215px;  
  background-color : #313131;
  margin : 30px 10px;
  padding : 20px 15px;
  
  display : flex;
  flex-direction : column;
  box-shadow : 0 5px 20px rgba(0,0,0,0.5);
  transition : 0.3s ease-in-out;
  border-radius : 15px;
}
.container .card:hover {
  height : 320px;    
}


.container .card .image {
  position : relative;
  width : 260px;
  height : 260px;
  
  top : -40%;
  left: 8px;
  box-shadow : 0 5px 20px rgba(0,0,0,0.2);
  z-index : 1;
}

.container .card .image img {
  max-width : 100%;
  border-radius : 15px;
}

.container .card .content {
  position : relative;
  top : -140px;
  padding : 10px 15px;
  color : #111;
  text-align : center;
  
  visibility : hidden;
  opacity : 0;
  transition : 0.3s ease-in-out;
    
}

.container .card:hover .content {
   margin-top : 30px;
   visibility : visible;
   opacity : 1;
   transition-delay: 0.2s;
  
}

h3{
  color: white;
  font-family: 'Rubik'
}

.surname{
  color: red;
  font-family: 'Rubik'
}

.reference{
  color: white;
    font-family: 'Rubik'
}
    

</style>
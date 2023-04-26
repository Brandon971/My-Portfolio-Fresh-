<template>
<section id="aboutpage">
    <div class="container-fluid">
        <div class="row">
<div class="about-me">
  <div class="rectangle-2"></div>

  <svg
    class="rectangle-3"
    width="450"
    height="362"
    viewBox="0 0 502 362"
    fill="none"
    xmlns="http://www.w3.org/2000/svg"
  >
    <path d="M0.5 0H501.5V362H0.5V0Z" fill="#111111" />
  </svg>

  <img
    class="img-20210822-wa-0192-1-removebg-preview-1"
    src="https://i.postimg.cc/J4wPQR01/IMG-20210822-WA0192-1-removebg-p.png"
  />

  <div
    class="info"
  >
    Hi My name is Brandon Swinton ,I am an aspiring developer .I was born in
    Cape Town ,South Africa ,I was raised in Mitchells Plain and this is where
    Im currently located in .I am a bachelor pass Matriculant from Portland high
    school.I am a very disciplined young man.I believe in hard work and
    commitment to be successful in anything .I love solving problems and i love
    using my creativity in my work.I can work alone and i can corporate well
    within a team.I believe i can push any company to success with my talents
  </div>
  <div class="subtitle">Get to know </div>
   <div class="subtitle2">Me </div>

  <div class="about">About</div>
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
.about-me,
.about-me * {
  box-sizing: border-box;
}
.about-me {
  background: #000000;
  width: 1980px;
  height: 1080px;
  position: relative;
  overflow: hidden;
}
.rectangle-2 {
  border-width: 50px;
  border-style: solid;
  border-image: linear-gradient(
    180deg,
    rgba(254, 0, 0, 1) 0%,
    rgba(254, 0, 0, 0.89) 8.33333358168602%,
    rgba(123, 52, 52, 0) 99.98999834060669%,
    rgba(254, 0, 0, 0) 100%
  );
  border-image-slice: 1;
  width: 500px;
  height: 400px;
  position: absolute;
  left: 69px;
  top: 135px;
}
.rectangle-3 {
  position: absolute;
  left: 745px;
  top: 180px;
  overflow: visible;
}
.img-20210822-wa-0192-1-removebg-preview-1 {
  width: 500px;
  /* height: 1223.3px; */
  position: absolute;
  left: 1px;
  top: 60px;
}
.info {
  color: #ffffff;
  text-align: center;
  font-family: 'Rubik', sans-serif;
  position: absolute;
  left: 750px;
  top: 90px;
  width: 550px;
  height: 544px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.about {
  color: #ffffff;
  text-align: center;
  font: 800 96px "Poppins", sans-serif;
  position: absolute;
  left: 540px;
  top: 100px;
  width: 638px;
  height: 165px;
  display: flex;
  align-items: center;
  justify-content: center;
}

#aboutpage{
    height: 100vh;
}
.subtitle{
      color: #ffffff;
  font: 800 36px "Poppins", sans-serif;
  position: absolute;
  left: 334px;
  top: 50px;
  width: 550px;
  height: 544px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
}
.subtitle2{
      color: #ff0000;
  font: 800 40px "Poppins", sans-serif;
  position: absolute;
  left: 580px;
  top: 50px;
  width: 550px;
  height: 544px;
  display: flex;
  align-items: center;
  justify-content: flex-start;

}

</style>
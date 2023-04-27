<template>
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.6.3/css/all.css" integrity="sha384-UHRtZLI+pbxtHCWp1t77Bi1L4ZtiqrqD80Kn4Z8NTSRyMA2Fd33n5dQ8lWUE00s/" crossorigin="anonymous">
    <!-- Site footer -->
    <footer class="site-footer">
      <div class="container">
        <div class="row">
          <div class="col-sm-12 col-md-6">
            <h6>About</h6>
            <p class="text-justify">I'm a highly skilled and a passionate Full Stack Developer with a strong background in building robust and beautiful web applictaions. With a focus on delivering high-quality code and exceptional user experiences,I strive to create innovative solutions that meet and exceed the needs of my clients.In summary, I bring a comprehensive skill set, a passion for innovation, and commitment to excellance as a Developer.</p>
          </div>

          <div class="col-xs-6 col-md-3">
            <h6>Skills</h6>
            <ul class="footer-links">
              <li><a href="https://www.hostinger.com/tutorials/what-is-javascript" target="_blank">Javascript</a></li>
              <li><a href="https://www.interaction-design.org/literature/topics/ui-design" target="_blank">UI Design</a></li>
              <li><a href="https://www.hostinger.com/tutorials/what-is-node-js" target="_blank">Node.js</a></li>
              <li><a href="https://vuejs.org/guide/introduction.html" target="_blank">VUE</a></li>
              <li><a href="https://www.w3schools.com/css/css_intro.asp" target="_blank">CSS</a></li>
              <li><a href="https://www.hostinger.com/tutorials/what-is-mysql" target="_blank">MYSQL</a></li>
            </ul>
          </div>

          <div class="col-xs-6 col-md-3">
            <h6>Quick Nav</h6>
            <ul class="footer-links">
              <li><a href="#aboutpage">About Me</a></li>
              <li><a href="#contact">Contact Me</a></li>
              <li><a href="#resume">Education/Work</a></li>
              <li><a href="#projects">Projects</a></li>
              <li><a href="#skills">My Skills</a></li>
            </ul>
          </div>
        </div>
        <hr>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-md-8 col-sm-6 col-xs-12">
            <p class="copyright-text">Copyright &copy; 2023 All Rights Reserved by 
         <a href="https://www.linkedin.com/in/brandon-swinton-a14088235/" target="_blank">Brandon Swinton</a>.
            </p>
          </div>

          <div class="col-md-4 col-sm-6 col-xs-12">
            <ul class="social-icons">
  <li>
    <a href="https://www.instagram.com/_brandonswinton_/" target="_blank" class="instagram"><i class="fab fa-instagram icon"></i></a>
  </li>
  <li>
    <a href="https://www.linkedin.com/in/brandon-swinton-a14088235/"  target="_blank" class="linkedin"><i class="fab fa-linkedin-in icon"></i></a></li>
  <li>
    <a href="https://github.com/Brandon971"  target="_blank" class="github"><i class="fab fa-github icon"></i></a></li>
            </ul>
          </div>
        </div>
      </div>
</footer>
</template>

<script>
export default {

}
</script>

<style scoped>
.site-footer
{
  background-color:#26272b;
  padding:45px 0 20px;
  font-size:15px;
  line-height:24px;
  color:#737373;
}
.site-footer hr
{
  border-top-color:#bbb;
  opacity:0.5
}
.site-footer hr.small
{
  margin:20px 0
}
.site-footer h6
{
  color:#fff;
  font-size:16px;
  text-transform:uppercase;
  margin-top:5px;
  letter-spacing:2px
}
.site-footer a
{
  color:#737373;
}
.site-footer a:hover
{
  color:#3366cc;
  text-decoration:none;
}
.footer-links
{
  padding-left:0;
  list-style:none
}
.footer-links li
{
  display:block
}
.footer-links a
{
  color:#737373
}
.footer-links a:active,.footer-links a:focus,.footer-links a:hover
{
  color:#3366cc;
  text-decoration:none;
}
.footer-links.inline li
{
  display:inline-block
}
.site-footer .social-icons
{
  text-align:right
}
.site-footer .social-icons a
{
  width:40px;
  height:40px;
  line-height:40px;
  margin-left:6px;
  margin-right:0;
  border-radius:100%;
  background-color:#33353d
}
.copyright-text
{
  margin:0
}
@media (max-width:991px)
{
  .site-footer [class^=col-]
  {
    margin-bottom:30px
  }
}
@media (max-width:767px)
{
  .site-footer
  {
    padding-bottom:0
  }
  .site-footer .copyright-text,.site-footer .social-icons
  {
    text-align:center
  }
}
.social-icons
{
  padding-left:0;
  margin-bottom:0;
  list-style:none
}
.social-icons li
{
  display:inline-block;
  margin-bottom:4px
}
.social-icons li.title
{
  margin-right:15px;
  text-transform:uppercase;
  color:#96a2b2;
  font-weight:700;
  font-size:13px
}
.social-icons a{
  background-color:#eceeef;
  color:#818a91;
  font-size:16px;
  display:inline-block;
  line-height:44px;
  width:44px;
  height:44px;
  text-align:center;
  margin-right:8px;
  border-radius:100%;
  -webkit-transition:all .2s linear;
  -o-transition:all .2s linear;
  transition:all .2s linear
}
.social-icons a:active,.social-icons a:focus,.social-icons a:hover
{
  color:#fff;
  background-color:#29aafe
}
.social-icons.size-sm a
{
  line-height:34px;
  height:34px;
  width:34px;
  font-size:14px
}

.social-icons a.instagram:hover
{
  background-color:#ea4c89
}
.social-icons a.linkedin:hover
{
  background-color:#007bb6
}
.social-icons a.github:hover
{
  background-color:#5aeb47
}



@media (max-width:767px)
{
  .social-icons li.title
  {
    display:block;
    margin-right:0;
    font-weight:600
  }
}
</style>
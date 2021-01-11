<template>
  <div id="app">

    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
      <div class="container">
        <a class="navbar-brand js-scroll-trigger" href="#page-top">Matias Davidson</a>
        <button class="navbar-toggler navbar-toggler-right" type="button" data-toggle="collapse" data-target="#navbarResponsive" aria-controls="navbarResponsive" aria-expanded="false" aria-label="Toggle navigation">
          Menu
          <i class="fas fa-bars"></i>
        </button>
        <div class="collapse navbar-collapse" id="navbarResponsive">
          <ul class="navbar-nav text-uppercase ml-auto">
            <li class="nav-item" >
              <a @click="collapseMenu" class="nav-link js-scroll-trigger" href="#about" >About me</a>
            </li>
            <li class="nav-item">
              <a @click="collapseMenu" class="nav-link js-scroll-trigger" href="#portfolio">Portfolio</a>
            </li>
            <li class="nav-item">
              <a @click="collapseMenu" class="nav-link js-scroll-trigger" href="#experience">Experience</a>
            </li>
            <li class="nav-item">
              <a @click="collapseMenu" class="nav-link js-scroll-trigger" href="#education">education</a>
            </li>
            <li class="nav-item">
              <a @click="collapseMenu" class="nav-link js-scroll-trigger" href="#skills">skills</a>
            </li>
            <a style="align-self:center" target="_blank" href="https://github.com/matiasdavidson"><img class="header-icon" src="../public/img/GitHub-Mark-Light-120px-plus.png" alt=""></a>
            <a style="align-self:center" target="_blank" href="https://www.linkedin.com/in/matias-davidson/"><img class="header-icon" src="../public/img/linkedin-4-512.png" alt=""></a>
            <a target="_blank" style="align-self:center" href="https://drive.google.com/file/d/1I68KR6Qh1yPieUZXuiH-xGCB3g67H2eA/view?usp=sharing"><img class="header-icon" src="../public/img/cv-icon.png" alt=""></a>
          </ul>
        </div>
      </div>
    </nav>

    <!-- Header -->
    <header class="masthead">
      <div class="container">
        <div class="intro-text">
          <div class="intro-lead-in">Hi! I'm Matias Davidson</div>
          <div class="intro-heading">Front End Developer</div>
          <img src="./assets/img/scroll.png" alt="scroll" class="scroll-icon">
        </div>
      </div>
    </header>

    <!-- About Me -->
    <section id="about">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
           <img class="cv-img rounded-circle" src="../public/img/cv-black.png">
            <h3 class="section-subheading text-muted about-text"><br>Jr Front End Developer<br><br>Marketing Graduate<br><br>Amateur snowboarder, travel enthusiast and animal rights activist
            </h3>
          </div>
          <div class="languages col-lg-12 text-center">
            <img class="language-flag" src="../public/img/espana.png" alt="Spanish" title="Spanish (native)">
            <img class="language-flag" src="../public/img/reino-unido.png" alt="English" title="English (advanced)">
            <img class="language-flag" src="../public/img/israel.png" alt="Hebrew" title="Hebrew (basic to intermediate)">
            <img class="language-flag" src="../public/img/brasil.png" alt="Portuguese" title="Portuguese (basic)">
          </div>
        </div>
        </div>
      </section>

 <!-- Recent Experience -->
    <section id="experience" class="bg-light">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">Recent Experience</h2>
            <h3 class="section-subheading text-muted">Recent IT experience and others</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-sm-4">
            <div class="job">
              <a target="_blank" href="https://www.globant.com"><img class="mx-auto rounded-circle" src="https://uxmyjob.com/wp-content/uploads/2019/11/logo-globant-uxmyjob.png" alt=""></a>
              <h4>Globant</h4>
              <p class="text-muted"><strong>Front End Developer (Dec 2020 - Now)</strong> <br>Vue.js Front End Developer.</p>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="job">
              <a target="_blank" href="https://kahloagencia.com/"><img class="mx-auto rounded-circle" src="https://media.licdn.com/dms/image/C4E0BAQFrF6OAHc7gBA/company-logo_200_200/0?e=2159024400&v=beta&t=xIOGFIxDqiWV3zzNJgW_WQTHm3rY8WqUk5_M2j14JvQ" alt=""></a>
              <h4>Kahlo Digital Agency</h4>
              <p class="text-muted"><strong>Freelance Front End Developer (2020)</strong><br>Web development using HTML, SCSS, CSS, JS and PHP for an agency working with US based clients.</p>
             
            </div>
          </div>
          <div class="col-sm-4">
            <div class="job">
              <a target="_blank" href="https://reserv.com.ar/"><img class="mx-auto rounded-circle" src="https://media-exp1.licdn.com/dms/image/C4E03AQEYnHx0Pr9Chg/profile-displayphoto-shrink_200_200/0/1583768929956?e=1614211200&v=beta&t=wA290NSx9eVVMnSPkAlzhvBqHVRQv0vTPsixizppVww" alt="" style="border: solid lightgray 1px"></a>
              <h4>Reserv IT Solutions</h4>
              <p class="text-muted"><strong>Full Stack Developer (2019 - 2020)</strong><br>Working with Angular, JS and PHP. Also helping with test automation for websites.</p>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="job">
              <a target="_blank" href="https://lamroth.org/inicio/"><img class="mx-auto rounded-circle" src="../public/img/lamroth.jpg" alt="" style="border: solid lightgray 1px"></a>
              <h4>Lamroth Hakol</h4>
              <p class="text-muted"><strong>Head of Security (2016-2019)</strong><br>In charge of the security team (55 people) and procedures.</p>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="job">
              <a target="_blank" href="https://www.fravega.com/"><img class="mx-auto rounded-circle" src="https://www.gointegro.com/wp-content/uploads/2018/10/fravega.jpg" alt="" style="border: solid lightgray 1px"></a>
              <h4>Fravega</h4>
              <p class="text-muted"><strong>Sr Ecommerce Analyst (2016)</strong><br>Working with Fravega´s app and web page.</p>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="job">
              <a target="_blank" href="https://www.groupon.com/"><img class="mx-auto rounded-circle" src="https://play-lh.googleusercontent.com/ZEv9s5qAuSug0FPBDgsTLru5gRULx01C7XiUuVC9eu_-3zbVj14648EeHY52wWMFTkc" alt="" style="border: solid lightgray 1px"></a>
              <h4>Groupon</h4>
              <p class="text-muted"><strong>Sales executive (2015-2016)</strong><br>Finding and developing new business opportunities.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Portfolio Grid -->
    <Portfolio></Portfolio>

    <!-- Education -->
    <section id="education" class="bg-light">
      <div class="container">
        <div class="row">
          <div class="col-lg-12 text-center">
            <h2 class="section-heading text-uppercase">education</h2>
            <h3 class="section-subheading text-muted"></h3>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-12">
            <ul class="timeline">
              <li>
                <a target="_blank" href="https://www.coderhouse.com/"><div class="timeline-image timeline-image1">
                  <img class="rounded-circle img-fluid" src="" alt="">
                </div></a>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>2020</h4>
                    <h4 class="subheading">Coderhouse</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">React JS and React Native</p>
                  </div>
                </div>
              </li>
              <li class="timeline-inverted">
                <a target="_blank" href="https://platzi.com/home">
                  <div class="timeline-image timeline-image2">
                  <img class="rounded-circle img-fluid" src="img/about/2.jpg" alt="">
                </div> </a>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>2020</h4>
                    <h4 class="subheading">Platzi</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Vue.js, Javascript (professional  and asyncronism)</p>
                  </div>
                </div>
              </li>
              <li>
                <a target="_blank" href="https://www.digitalhouse.com/">                
                <div class="timeline-image timeline-image3">
                  <img class="rounded-circle img-fluid" src="img/about/3.jpg" alt="">
                </div></a>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>2018</h4>
                    <h4 class="subheading">Digital House</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Full Stack Development</p>
                  </div>
                </div>
              </li>
              <li class="timeline-inverted">
                <a target="_blank" href="https://www.uade.edu.ar/">       
                <div class="timeline-image timeline-image4">
                  <img class="rounded-circle img-fluid" src="img/about/4.jpg" alt="">
                </div></a>
                <div class="timeline-panel">
                  <div class="timeline-heading">
                    <h4>2016</h4>
                    <h4 class="subheading">UADE University</h4>
                  </div>
                  <div class="timeline-body">
                    <p class="text-muted">Marketing graduate</p>
                  </div>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>

    <section id="skills">
      <div class="container">
        <h2 class="section-heading text-uppercase">Skills</h2>
          <div class="row text-center">
            <div class="col-md-3">
              <span class="fa-stack fa-4x">
                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                <i class="fas fa-shopping-cart fa-stack-1x fa-inverse"></i>
              </span>
              <h5 class="skill-heading">Vue.js (b)</h5>
            </div>
            <div class="col-md-3">
              <span class="fa-stack fa-4x">
                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                <i class="fas fa-laptop fa-stack-1x fa-inverse"></i>
              </span>
              <h5 class="skill-heading">React JS (bk)</h5>
            </div>
            <div class="col-md-3">
              <span class="fa-stack fa-4x">
                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
              </span>
              <h5 class="skill-heading">Angular (bk)</h5>
            </div>
            <div class="col-md-3">
              <span class="fa-stack fa-4x">
                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
              </span>
              <h5 class="skill-heading">Laravel (bk)</h5>
            </div>
            <div class="col-md-3">
              <span class="fa-stack fa-4x">
                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
              </span>
              <h5 class="skill-heading">React Native (bk)</h5>
            </div>
            <div class="col-md-3">
              <span class="fa-stack fa-4x">
                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
              </span>
              <h5 class="skill-heading">Javascript (i)</h5>
            </div>
            <div class="col-md-3">
              <span class="fa-stack fa-4x">
                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
              </span>
              <h5 class="skill-heading">PHP (b)</h5>
            </div>
            <div class="col-md-3">
              <span class="fa-stack fa-4x">
                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
              </span>
              <h5 class="skill-heading">SQL (b)</h5>
            </div>
            <div class="col-md-3">
              <span class="fa-stack fa-4x">
                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
              </span>
              <h5 class="skill-heading">HTML</h5>
            </div>
            <div class="col-md-3">
              <span class="fa-stack fa-4x">
                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
              </span>
              <h5 class="skill-heading">SASS</h5>
            </div>
            <div class="col-md-3">
              <span class="fa-stack fa-4x">
                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
              </span>
              <h5 class="skill-heading">CSS</h5>
            </div>
            <div class="col-md-3">
              <span class="fa-stack fa-4x">
                <i class="fas fa-circle fa-stack-2x text-primary"></i>
                <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
              </span>
              <h5 class="skill-heading">Scrum</h5>
            </div>
          </div>
        </div>
      </section>

    <!-- Footer -->
    <footer style="background-color: black;">
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <span class="copyright">Developed by Matias Davidson</span>
          </div>
          <div class="col-md-4">
            <span class="copyright">matiasdavidson1@gmail.com</span>
          </div>
          <div class="col-md-4">
            <a style="align-self:center" target="_blank" href="https://github.com/matiasdavidson"><img class="header-icon footer-icon" src="../public/img/GitHub-Mark-Light-120px-plus.png" alt=""></a>
            <a style="align-self:center" target="_blank" href="https://www.linkedin.com/in/matias-davidson/"><img class="header-icon footer-icon" src="../public/img/linkedin-4-512.png" alt=""></a>
            <a target="_blank" style="align-self:center" href="https://drive.google.com/file/d/1I68KR6Qh1yPieUZXuiH-xGCB3g67H2eA/view?usp=sharing" ><img class="header-icon footer-icon" src="../public/img/cv-icon.png" alt=""></a>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script>

import Portfolio from './components/Portfolio'

export default {
  name: 'app',
  methods: {
    collapseMenu: function(){
      document.getElementById("navbarResponsive").classList.remove("show");
    }
  },
  components: {
    Portfolio
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

body {
  background: black;
}
</style>

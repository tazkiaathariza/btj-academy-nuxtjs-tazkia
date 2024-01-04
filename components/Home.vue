<template>
<div class="background">
   <div class="container my-5 mx-5 p-0 main">
        <!-- Nav Bar -->
        <nav class="navbar navbarHome navbar-expand-lg">
          <div class="container-fluid p-3 mx-md-3">
            <div class="navbar-brand">
              <img id="logo" src="../assets/images/flower-pic.svg" alt="Logo" width="40" height="40" 
              class="d-inline-block align-top">
              Home
            </div>

            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" 
              data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" 
              aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
        
            <div class="collapse navbar-collapse justify-content-end" id="navbarNav">
              <ul class="navbar-nav">
              
                <li class="nav-item">
                  <button class="btn btn-primary" @click="toLogin">Log In</button>
                </li>
              </ul>
            </div>
          </div>
        </nav>


        <!-- Intro -->
        <section class="row p-2 mx-md-4 justify-content-center align-items-center" id="introduction">

            <div class="col-md-6 pt-3 pb-3 text-center intro1">
                <figure class="ml-md-5">
                    <img id="myphoto" src="../assets/images/myphoto.jpg" class="rounded-circle img-fluid">
                </figure>
            </div>

            <div class="col-md-6 pt-2 pb-4 intro2">
                <div id="judul" class="text-center">
                    <p>Hi! It's me, </p>
                    <h3 class="judul_subsection">Tazkia Athariza Dhivara</h3>
                 </div>
                  <hr width="90%"/>
                  <div class="p-3 profile">
                    <h5 class="judul_subsection">Who am I?</h5>
                    <p>
                      I'm an enthusiast junior <mark>frontend developer</mark> based on Surabaya. I used to 
                      study biology in college, but I also put more work in research, UI/UX 
                      design, and website development. My spare time is mostly used for reading 
                      various genre of book, watching film, and listening to music. 
                    </p>
                    <span>
                      <button class="btn btn-primary m-2"><a href="https://github.com/tazkiaathariza">
                        GitHub</a></button>
                      <button class="btn btn-primary"><a href="https://www.linkedin.com/in/tazkiaathariza">
                        LinkedIn</a></button>
                    </span>
                  </div>
                 
            </div>
        </section>


        <!-- Motto -->
        <section class="row" id="motto">
            <div class="col-md-12 text-center">
                <p>My life motto is...</p>
                <h4 id="mottoText">
                    <i><b style="color:#AB3C41">Always strive to make a useful impact 
                    <br/> no matter how small</b></i>
                </h4>
            </div>
        </section>


        <!-- Education -->
        <section class="container p-md-5 p-sm-5 bg-red" id="education">

            <div class="row py-3">
                <div class="my-3" style="color: white">
                    <h3>Where did I go to study?</h3>
                    <p style="color: white">I finished all of my study in my home town, Surabaya</p>
                </div>

            <div class="row mb-2 mt-2">
                <div class="col-md-4 col-sm-12 mb-sm-5 mb-3">
                    <div class="card px-2 py-3 cardEdu" style="width: 100%; height: 100%;">
                        <div class="card-body">
                          <img src="../assets/images/icon3.svg" class="icon"/>
                          <h6 class="card-subtitle my-2 text-body-secondary">2018-2022 </h6>
                          <h5 class="card-title">Universitas Airlangga</h5>
                          <p class="card-text">Major : Biologi | IPK : 3.76</p>
                          <button href="#" class="btn btn-primary" data-bs-toggle="modal" 
                          data-bs-target="#modal1">More</button>
                        </div>
                      </div>
                </div>
                <div class="col-md-4 col-sm-12 mb-sm-5 mb-3">
                    <div class="card px-2 py-3 cardEdu" style="width: 100%; height: 100%;">
                        <div class="card-body">
                          <img src="../assets/images/icon2.svg" class="icon"/>
                          <h6 class="card-subtitle my-2 text-body-secondary">2015-2018</h6>
                          <h5 class="card-title">SMAN 20 Surabaya</h5>
                          <p class="card-text">Major : IPA</p>
                          <button href="#" class="btn btn-primary" data-bs-toggle="modal" 
                          data-bs-target="#modal2">More</button>
                        </div>
                      </div>
                </div>
                <div class="col-md-4 col-sm-12 mb-sm-5 mb-3">
                    <div class="card px-2 py-3 cardEdu" style="width: 100%; height: 100%;">
                        <div class="card-body">
                          <img src="../assets/images/icon1.svg" class="icon"/>
                          <h6 class="card-subtitle my-2 text-body-secondary">2012-2015</h6>
                          <h5 class="card-title">SMPI Al-Azhar 13</h5>
                          <p class="card-text">Major : -</p>
                          <button href="#" class="btn btn-primary" data-bs-toggle="modal" 
                          data-bs-target="#modal3">More</button>
                        </div>
                      </div>
                </div>

            </div>
        </div>
        </section>

        <!-- Modal -->
        <div class="modal fade" id="modal1" tabindex="-1" aria-labelledby="modal1" aria-hidden="true">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h1 class="modal-title fs-5" id="exampleModalLabel">More Info</h1>
                <button type="button" class="btn-close" data-bs-dismiss="modal" 
                  aria-label="Close"></button>
              </div>
              <div class="modal-body">
                Title of my thesis is "The Effect of the Combination of Sargassum 
                  duplicatum Alginate with Abelmoschus esculentus and Garcinia mangostana
                  Peel Extract on Blood Glucose Levels and Diameter of the Islet of Langerhans 
                  in Diabetic Mice (Mus musculus)"
              </div>
              <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
              </div>
            </div>
          </div>
        </div>

        <div class="modal fade" id="modal2" tabindex="-1" aria-labelledby="modal2" aria-hidden="true">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h1 class="modal-title fs-5" id="exampleModalLabel">More Info</h1>
                <button type="button" class="btn-close" data-bs-dismiss="modal" 
                  aria-label="Close"></button>
              </div>
              <div class="modal-body">
                During senior high school, I used to active in extracurricular 'Karya Ilmiah Remaja' and 'Sie Kerohanian Islam' 
              </div>
              <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
              </div>
            </div>
          </div>
        </div>

        <div class="modal fade" id="modal3" tabindex="-1" aria-labelledby="modal3" aria-hidden="true">
          <div class="modal-dialog">
            <div class="modal-content">
              <div class="modal-header">
                <h1 class="modal-title fs-5" id="exampleModalLabel">More Info</h1>
                <button type="button" class="btn-close" data-bs-dismiss="modal" 
                  aria-label="Close"></button>
              </div>
              <div class="modal-body">
                During junior high school, I used to active in extracurricular 'Karya Ilmiah Remaja'.
              </div>
              <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
              </div>
            </div>
          </div>
        </div>

        <!-- Work -->
        <section class="container p-md-5 p-sm-5 mt-2 mb-4" id="work">
            <div class="row my-3">
                <h4 class="judul_subsection">Here's my intern and part-time experience..</h4>
                <p>My experience is quite varied</p>
            </div>

            <div class="row">
                <div class="col-md-12 text-center">
                    <table class="table table-striped table-striped-costum">
                        <thead>
                          <tr>
                            <th>Position</th>
                            <th>Institution</th>
                            <th>Year</th>
                          </tr>
                        </thead>
                        <tbody>
                          <tr>
                            <td>UI/UX Designer Intern</td>
                            <td>Skilvul</td>
                            <td>2021</td>
                          </tr>
                          <tr>
                            <td>Graphic Designer Intern</td>
                            <td>Tokobay</td>
                            <td>2021</td>
                          </tr>
                          <tr>
                            <td>Researcher Intern</td>
                            <td>Perum Perhutani</td>
                            <td>2021</td>
                          </tr>
                          <tr>
                            <td>Lecturer's Assistant</td>
                            <td>Universitas Airlangga</td>
                            <td>2020</td>
                          </tr>
                          <tr>
                            <td>Pengelola Kelas (Part-Time)</td>
                            <td>BAKTI Kominfo</td>
                            <td>2022</td>
                          </tr>
                          <tr>
                            <td>Researcher's Assistant</td>
                            <td>Universitas Airlangga</td>
                            <td>2022</td>
                          </tr>
                        </tbody>
                      </table>
                </div>
            </div>
        </section>

        <!-- Organization  -->
        <section class="container p-md-5 p-sm-5 bg-red" id="organization">
          <div class="row my-3">

            <div class="col-md-4" style="color:white">
              <h4>Organization experiences</h4>
              <p style="color:white">I used to active in organization during my time 
                as undergraduate student</p>
            </div>

            <div class="col-md-8 pt-2 pb-4">
              <div class="accordion" id="accordionPanelsStayOpenExample">
                <div class="accordion-item">
                  <h2 class="accordion-header">
                    <button class="accordion-button" type="button" data-bs-toggle="collapse" 
                      data-bs-target="#panelsStayOpen-collapseOne" aria-expanded="true" 
                      aria-controls="panelsStayOpen-collapseOne">
                      SCOLAH Unair Mengajar
                    </button>
                  </h2>
                  <div id="panelsStayOpen-collapseOne" class="accordion-collapse collapse show">
                    <div class="accordion-body">
                      Worked in this department, there were two main of job desk, those are connecting Unair Mengajar (UM) 
                      to external party and developing creative media. I was the coordinator of the biggest UM external event. 
                      I conceptualized the event and executed it perfectly until it was exceeding the target.
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" 
                      data-bs-target="#panelsStayOpen-collapseTwo" aria-expanded="false" aria-controls="panelsStayOpen-collapseTwo">
                      Bursa Eksakta
                    </button>
                  </h2>
                  <div id="panelsStayOpen-collapseTwo" class="accordion-collapse collapse">
                    <div class="accordion-body">
                      My department was responsible for educating the members about business and investment. 
                      I became the vice chairman of one of its biggest event; Beta Business Model Canvas Competition and 
                      successfully exceeding the target.
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" 
                      data-bs-target="#panelsStayOpen-collapseThree" aria-expanded="false" aria-controls="panelsStayOpen-collapseThree">
                      Biology English Club
                    </button>
                  </h2>
                  <div id="panelsStayOpen-collapseThree" class="accordion-collapse collapse">
                    <div class="accordion-body">
                      As a secretary, I was in charge of managing the secretariat, organizing the files, 
                      and planning work programs.
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <h2 class="accordion-header">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" 
                      data-bs-target="#panelsStayOpen-collapseFour" aria-expanded="false" aria-controls="panelsStayOpen-collapseThree">
                      UKM Penalaran
                    </button>
                  </h2>
                  <div id="panelsStayOpen-collapseFour" class="accordion-collapse collapse">
                    <div class="accordion-body">
                      My department was responsible for establishing a partnership with external parties. I was the 
                      coordinator of collaboration research event and the treasurer of open recruitment event 2020.
                    </div>
                  </div>
                </div>
              </div>
                
            </div>

        </div>
      </section>

      <!-- Project -->
      <section class="container p-md-5 p-sm-5 mt-2 mb-4" id="project">
        <div class="row my-3">
            <h4 class="judul_subsection">Project I've made before</h4>
            <p>It's from internship and bootcamp. Click right to see the others</p>
        </div>

        <div class="row">
            <div class="col-md-12 text-center">
              <div id="carouselExampleCaptions" class="carousel slide carousel-dark">
                <div class="carousel-indicators">
                  <button type="button" data-bs-target="#carouselExampleCaptions" 
                    data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1">
                  </button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" 
                    data-bs-slide-to="1" aria-label="Slide 2">
                  </button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" 
                    data-bs-slide-to="2" aria-label="Slide 3">
                  </button>
                </div>
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img src="../assets/images/carrental.svg" class="d-block w-100" alt="...">
                    <div class="carousel-caption d-none d-md-block">
                      <a href="https://tazkiaathariza-carrental-project.vercel.app/">
                        <h5> Website : Car Rental</h5>
                      </a>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="../assets/images/kitabisa.svg" class="d-block w-100" alt="...">
                    <div class="carousel-caption d-none d-md-block"> 
                      <a href="https://medium.com/@tazkia.athariza.dhivara-2018/ux-case-study-kitabisa-7042a0150d1f">
                        <h5>UI/UX Case : KitaBisa</h5>
                      </a>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="../assets/images/talentadigital.svg" class="d-block w-100" alt="...">
                    <div class="carousel-caption d-none d-md-block">
                      <a href="https://medium.com/@tazkia.athariza.dhivara-2018/ux-case-study-talentadigital-867146a4796a">
                        <h5>UI/UX Case : TalentaDigital</h5>
                      </a>
                    </div>
                  </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Next</span>
                </button>
              </div>
            </div>
        </div>
      </section>

      <!-- Footer -->
      <footer class="row">
        <p style="color:#AB3C41">&copy; 2023 BTJ Academy</p>
      </footer>

    </div>
</div>
</template>

<script>
export default {
    methods: {
        toLogin(){
            alert("Redirect ke halaman login")
            navigateTo('/login')
        }
    }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;0,500;0,700;1,300;1,500;1,700&display=swap');

:root {
    --primary-color:  #73101E;
    --secondary-color: #AB3C41;
    --tertiary-color: #ef5b62;
    --pink: #fcf5f3;
    --main-text-color: #2B2B2B;
}

* {
    font-family: 'Poppins', Arial, sans-serif;
    color:var(--main-text-color);
}

/* costumize navbar */

.navbarHome {
    background-color: white;
    border-radius: 15px;
}

.navbar-brand,
.nav-link{
    color:var(--secondary-color) !important;
}

.nav-link:hover {
    color: var(--main-text-color) !important;
    transition: color 0.5s ease;
}

#logo {
    cursor: pointer;
    transition: transform 1s ease-in-out;
}

.navbar-toggler{
    border: 0px;
}

.nav-link.active  {
    color: var(--main-text-color) !important;
} 


/* background color */

body {
  background-color:#73101E;
}

.main {
    background-color: white;
    border-radius: 15px 15px 15px 15px;
}

/* costumize button */

.btn-primary {
    background-color: var(--secondary-color) !important;
    border-color: var(--secondary-color) !important;
}

.btn-primary:hover {
    background-color: var(--tertiary-color) !important;
    border-color: var(--tertiary-color) !important;
    color: white;
    transition: background-color 0.5s ease;
}

.btnsubmit {
    width: 100%;
}


/* costumize form section */

.card {
    box-shadow: 0 0 4px rgba(0, 0, 0, 0.3);
    border-radius: 15px;
}

.form-control:focus{
    box-shadow: none;
    border: 3px solid var(--secondary-color)
}


#flower {
    width: 55%;
    height: 55%;
}

.pesanError {
    font-size: 14px;
    font-weight: 385;
    margin-top: 0px;
    position: relative;
    top: 2px;
    margin-bottom: 0px;
    width: 90%;
}

.userInput {
    margin: 0px;
}

/* To show password in a readable text */

.showPassword {
    position: relative;
    right: 45px;
    transform: translateY(-50%);
    cursor: pointer;
}

/* Animation */
@keyframes fadeIn {
    0% {
      opacity: 0;
    }
    100% {
      opacity: 1;
    }
  }
  
@keyframes scaleUp {
    0% {
      transform: scale(0);
    }
    100% {
      transform: scale(1);
    }
}

.welcome {
    animation: fadeIn 2s ease-in-out; 
}

.quote {
    animation: scaleUp 1.5s ease-in-out; 
}

/* ABOUT ME PAGE*/

.judul_subsection{
    color: var(--secondary-color);
}

mark {
    background-color: var(--tertiary-color);
    color: white;
    border-radius: 2px;
    padding: 2px;
}

#myphoto {
    width: 70%;
    box-shadow: 0 0 12px var(--secondary-color);
    cursor: pointer;
    transition: opacity 1s;
}

#myphoto:hover {
    transform: scale(1.02);
}


.btn.btn-primary a,
.btn.btn-primary a:hover,
.btn.btn-primary a:active,
.btn.btn-primary a:focus {
  color: inherit; 
  text-decoration: none; 
}

/* Motto */

#motto {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 600px; 
    background-image: url('../assets/images/background-flower.svg');
    background-size: cover; 
    margin: 0px;
}

#mottoText:hover {
    transform: scale(1.02);
    transition: transform 0.5s ease;
}

/* Edu */

.bg-red {
    background: linear-gradient(to bottom right, #ef5b62, var(--secondary-color), #ef5b62);
}

.icon {
    width: 30%;
}

.cardEdu:hover {
    box-shadow: 0 0 8px rgba(77, 0, 0, 0.7);
    transform: scale(1.02);
    transition: transform 0.5s ease;
}

/* Work */
 
th {
    background-color: var(--secondary-color) !important; 
    color: white!important; 
}


.table-striped {
    --bs-table-striped-bg: var(--pink);
}

/* Organization */

.accordion {
    --bs-accordion-active-bg: var(--tertiary-color);
    --bs-accordion-active-color: white;
    --bs-accordion-btn-focus-box-shadow: none;
    --bs-accordion-btn-color: var(--secondary-color);
    --bs-accordion-color: var(--main-text-color);
    --bs-accordion-border-color: var(--tertiary-color);
}
  
  
/* Project */

.carousel-caption {
    background-color: rgb(223, 223, 223) !important;
    padding: 5px !important;
    border-radius: 15px !important;
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.5);
} 

.carousel-caption a {
    text-decoration: none;
    color: var(--main-text-color);
}

/* Animation */

@keyframes slideLeft {
    0% {
        transform: translateX(-100%);
      }
      100% {
        transform: translateX(0);
      }
}

@keyframes slideRight {
    0% {
        transform: translateX(100%);
      }
      100% {
        transform: translateX(0);
      }
}

.intro1 {
    animation: slideLeft 1.5s ease-in-out; 
}

.intro2 {
    animation: slideRight 1.5s ease-in-out; 
}

/* Footer */
footer {
    padding: 5px;
    text-align: center;
    color: var(--secondary-color);
    margin: 0;
}

@media (max-width: 768px) {

    .profile {
        text-align: center;
    }

    #motto {
        height: 150px; 
        background-color: white;
        background-image: none;
        margin-bottom: 20px;
    }
}

@media screen and (min-width : 768px) and (max-width : 1024px) {
    #myphoto{
        width: 90%;
    }

    #motto {
        height: 150px; 
        background-color: white;
        background-image: none;
        margin-bottom: 20px;
    }
    
}
</style>
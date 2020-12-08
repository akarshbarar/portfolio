<template>
  <div class="container">
   <p>Hi, I am</p>
   <span>Akarsh Barar</span><br/>
   <div class="part__first">

        <div class="designation">Full Stack Software Developer</div>
        <div class="description">
          I am Full Stack Softare Developer based in Faridabad,India. I am interested in building mobile apps and websites. I am also interested in open source contribution and teaching thats why I have a youtube channel were I teach how to make applications using Flutter. 
        </div>
        <button class="btn btn-outline movie-card__button">Get In touch</button>
   </div>
   

    <!-- <div class="scroll-downs">
      <div class="mousey">
        <div class="scroller"></div>
      </div>
    </div> -->
    <div class="aboutme" id="aboutme">
      <h1><span>01.</span> About Me </h1>
      <div class="aboutme__data">
            <div class="aboutme__innerdata">
              <p>
              Hi, I am Akarsh Barar, a Full Stack Software Developer in Faridabad India. I enjoy working on Mobile App developent alng with keen intrest in website developmet. I love to learn new technologies and platform. I love to work on <b>Open Source Projects</b>
              .<br/>
              I have done B.Tech in Computer Science. I also love teaching therefor I have a Youtube channel where I teach some random tech stuff like how to create mobile applications using Flutter and also some other programming stuffs. 

              <h3>Here are some technologies I have been working recently:</h3>
              <ul>
                  <li>NodeJs</li>
                  <li>VueJs</li>
                  <li>ReactJs</li>
                  <li>JavaScript</li>
                  <li>Flutter</li>
                  <li>Android App Developement</li>

              </ul>
            </p>
            </div>
          <img src="../assets/image/myimage.jpg"/>
      </div>   
   </div>


     <div class="education" id="aboutme">
      <h1><span>02.</span> Where I have worked </h1>
      <div class="education__data">
            <div class="work_tab_div">
              <div class="work_tabs_menu">
                <ul class="work_tabs">
                  <li id="work_tab1"> NovelVox </li>
                  <!-- <li id="work_tab2"> Intermediate</li>
                  <li id="work_tab3"> High School </li> -->
                </ul>
                <!--     closing tabs menu div -->
              </div>
              <div class="work_tab_content">
                <div id="work_tab1_content">
                  <h3> Full Stack Software Developer 
                    <h3>
                      <a href="https://www.novelvox.com/" target="_blank">@NovelVox</a>
                     </h3>
                  </h3>
                  <div class="work_tab1_content_timestamp">June 2019 to Present</div>
                  <ul>
                    <li>Worked on Integrating whatsapp to a web applicaion to redirect the message from any user to a particular number.</li>
                    <li>Worked on integrating facebook to a web applicaion.</li>
                    <li>Worked on Cisco Finesse SSO part which will let user to logout from all the application by one logout.</li>
                    <li>Worked on Research and Developement part in applicaion.</li>
                    <li>Worked on writing documents.</li>
                  </ul>
                </div>
              </div>
              <!--     closing tab div -->
            </div>
      </div>   
   </div>

   <div class="work education">
      <h1><span>03.</span> Some Things I've built </h1>
  

<div id="movie-card-list">
  <div class="movie-card" data-movie="amazonclone">
    <div class="movie-card__overlay"></div>
    <!-- <div class="movie-card__share">
      <button class="movie-card__icon"><i class="material-icons">&#xe87d</i></button>
      <button class="movie-card__icon"><i class="material-icons">&#xe253</i></button>
      <button class="movie-card__icon"><i class="material-icons">&#xe80d</i></button>
    </div> -->
    <div class="movie-card__content">
      <div class="movie-card__header">
        <h1 class="movie-card__title">Amazon Clone</h1>
        <h4 class="movie-card__info">VueJs E-Commerce App</h4>
      </div>
      <p class="movie-card__desc">Amazon Clone is a full fleged VueJs applicaiton with payement gateway integration using Stripe.
        In order to test use <b>test@test.com and password </b> as login credential.
      </p>
      <div class="buttonflex">
            <a href="https://amzonclone.vercel.app/" target="_blank" class="btn btn-outline movie-card__button" type="button">Visit Site</a>

      <a href="https://github.com/akarshbarar/amzonclone" target="_blank" class="btn btn-outline movie-card__button" type="button">Github</a>
      </div>
    


    </div>
  </div>
  <div class="movie-card" data-movie="corona">
    <div class="movie-card__overlay"></div>
    
    <div class="movie-card__content">
      <div class="movie-card__header">
        <h1 class="movie-card__title">Corona Tracker App</h1>
        <h4 class="movie-card__info">ReactJs Applcaion</h4>
      </div>
      <p class="movie-card__desc">Corona tracker will give you a visual representation of coran virus spread all over the world with Total affected, total recovered and total active cases.</p>

      <div class="buttonflex">
           <a href="https://covid19tracker-a45a3.web.app/"  target="_blank" class="btn btn-outline movie-card__button" type="button">Visit Site</a>

       <a href="https://github.com/akarshbarar/Covid19Tracker_Reactjs" target="_blank" class="btn btn-outline movie-card__button" type="button">Github</a>
      </div>
     

    </div>
  </div>

    <div class="movie-card" data-movie="onelink">
    <div class="movie-card__overlay"></div>
    
    <div class="movie-card__content">
      <div class="movie-card__header">
        <h1 class="movie-card__title">OneLink</h1>
        <h4 class="movie-card__info">NuxtJs Application</h4>
      </div>
      <p class="movie-card__desc">Onlink is a applcation where people can put all there usefull links at one place and can get one link for all link.</p>
      <div class="buttonflex">
            <a href="https://onlink-ten.vercel.app/"  target="_blank" class="btn btn-outline movie-card__button" type="button">Visit Site</a>

       <a href="https://github.com/akarshbarar/OneLink" target="_blank" class="btn btn-outline movie-card__button" type="button">Github</a>
      </div>
    
    </div>
  </div>
  <div class="movie-card" data-movie="airbnb">
    <div class="movie-card__overlay"></div>
   
    <div class="movie-card__content">
      <div class="movie-card__header">
        <h1 class="movie-card__title">AirBnb Clone App</h1>
        <h4 class="movie-card__info">ReactJs Applicaion</h4>
      </div>
      <p class="movie-card__desc">
        Airbnb clone app is just the UI dummy of Airbnb site, build with reactjs.
      </p>

     <div class="buttonflex">

      <a href="https://airbnb-clone-react-2025.firebaseapp.com/"  target="_blank" class="btn btn-outline movie-card__button" type="button">Visit Site</a>
      
        <a href="https://github.com/akarshbarar/airbnb-clone-react-ui" target="_blank" class="btn btn-outline movie-card__button" type="button">Github</a>
      </div>

    </div>
  </div>

  <div class="movie-card" data-movie="hulu">
    <div class="movie-card__overlay"></div>
   
    <div class="movie-card__content">
      <div class="movie-card__header">
        <h1 class="movie-card__title">Hulu Clone</h1>
        <h4 class="movie-card__info">ReactJs Applicaion</h4>
      </div>
      <p class="movie-card__desc">
        Hulu is movie site just like Netflix so I have just copied the UI part of the Hulu app.
      </p>
      <div class="buttonflex">
      <a href="https://hulu-clone-react-2025.firebaseapp.com/" target="_blank" class="btn btn-outline movie-card__button" type="button">Visit Site</a>

      <a href="https://github.com/akarshbarar/hulu-clone-ui-react" target="_blank" class="btn btn-outline movie-card__button" type="button">Github</a>
      </div>
    </div>
  </div>
<span>Many more to come</span>

</div>


   </div>

  


  </div>
</template>

<script>
import $ from 'jquery';

export default {
  head: {
    title: "Akarsh Barar | Developer",
    link: [
      {
        // rel:"stylesheet",
        // href:"https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css",
        // integrity:"sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2",
        // crossorigin:"anonymous"
        //  href:"https://www.w3schools.com/w3css/4/w3.css"
      },
    ],
  },
  mounted(){

// WORK EXPEREINCE
        $("#work_tab1_content").hide();
        $("#work_tab2_content").hide();
        $("#work_tab3_content").hide();
        $("#work_tab4_content").hide();


$("#work_tab1").mouseover(function() {
          $("#work_tab1_content").show();
        });
$("#work_tab1").mouseleave(function() {
          $("#work_tab1_content").hide();
        });


        // $("#work_tab1").hover(function() {
        //   $("#work_tab1_content").show();
        //   $("#work_tab2_content").hide();
        //   $("#work_tab3_content").hide();
        //   $("#work_tab4_content").hide();
        // });

        // $("#work_tab2").click(function() {
        //   $("#work_tab2_content").show();
        //   $("#work_tab1_content").hide();
        //   $("#work_tab3_content").hide();
        //   $("#work_tab4_content").hide();
        // });

        // $("#work_tab3").click(function() {
        //   $("#work_tab3_content").show();
        //   $("#work_tab1_content").hide();
        //   $("#work_tab2_content").hide();
        //   $("#work_tab4_content").hide();
        // });

        // $("#work_tab4").click(function() {
        //   $("#work_tab4_content").show();
        //   $("#work_tab1_content").hide();
        //   $("#work_tab2_content").hide();
        //   $("#work_tab3_content").hide();
        // });




      
  }
};
// https://codepen.io/vikassingh1111/pen/xBPmbL
</script>

<style>


@import url("https://fonts.googleapis.com/css?family=Varela");
@import url("https://fonts.googleapis.com/css2?family=Roboto&display=swap");
html,
body {
  font-family: "Roboto", sans-serif;
  background-color: #161b33;
  color: #fff;
}
.container {
  height: 100vh;
  max-width: 80%;
  margin-left: 25%;
  margin-right: auto;
  margin-top: 10%;
}
.container > p {
  color: #5ef1cf;
  font-size: 2vw;
  font-weight: 500;
}
/* .part__first{
    height:80vh;
} */
.designation {
  line-height: 1.6;
  font-size: 2vw;
  font-weight: 500;
  white-space: nowrap;
  overflow: hidden;
  animation: typing 4s steps(22, end) forwards infinite, blink 1s infinite;
}
@keyframes typing {
  0% {
    width: 0%;
  }
  100% {
    width: 100%;
  }
}
@keyframes blink {
  0%,
  100% {
    border-right: 2px solid transparent;
  }
  50% {
    border-right: 2px solid #222;
  }
}
.container > span {
  font-size: 5vw;
  font-weight: 900;
}
.description {
  margin-top: 10px;
  width: 50%;
  color: rgb(236, 236, 229);
  font-size: clamp(15px, 1vw, 30px);
}







.scroll-downs {
  position: absolute;
  right: 50%;
  left: 50%;
  margin-top: 10%;
  width: 34px;
  height: 55px;
}
.mousey {
  width: 3px;
  padding: 10px 15px;
  height: 35px;
  border: 2px solid #fff;
  border-radius: 25px;
  opacity: 0.75;
  box-sizing: content-box;
}
.scroller {
  width: 3px;
  height: 10px;
  border-radius: 25%;
  background-color: #fff;
  animation-name: scroll;
  animation-duration: 2.2s;
  animation-timing-function: cubic-bezier(0.15, 0.41, 0.69, 0.94);
  animation-iteration-count: infinite;
}
@keyframes scroll {
  0% {
    opacity: 0;
  }
  10% {
    transform: translateY(0);
    opacity: 1;
  }
  100% {
    transform: translateY(15px);
    opacity: 0;
  }
}
.aboutme,.education {
  margin-top: 15%;
  width: 80%;
}
.aboutme__data,.education__data{
  display: flex;
  flex-direction: row;
  line-height: 1.6;
  margin-top: 10px;
}

.aboutme__innerdata {
  width: 150%;
}
.aboutme__innerdata > ul {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(19rem, 1fr));
}
.aboutme__data > img {
  width: 200px;
  height: 200px;
  object-fit: contain;
  margin-left: 15%;
  -webkit-filter: grayscale(100%); /* Safari 6.0 - 9.0 */
  filter: grayscale(100%);
}

.aboutme__data > img:hover {
  transform: scale(1.1);
  -webkit-filter: grayscale(0%); /* Safari 6.0 - 9.0 */
  filter: grayscale(0%);
}

.aboutme > h1 > span {
  color: #5ef1cf;
}
.education > h1 > span {
  color: #5ef1cf;
}
h1::after {
  display: inline-block;
  content: "";
  border-top: 0.1rem solid lightgray;
  width: 25%;
  transform: translateY(0rem);
}


/* work */
@media screen and (max-width: 400px) {
  .work_tab_div {
    display: none;
  }
}


.work_tab_div {
  width: 100%;
  transform: translateZ(0);
}

.work_tabs_menu {
  /*   background-color:blue; */
  padding-top: 1%;
  width: 20%;
  float: left;
}

ul.work_tabs {
  padding: 0;
}

#work_tab1,
#work_tab2,
#work_tab3,
#work_tab4 {
  padding-top: 10%;
  padding-bottom: 20%;
  padding-left: 5%;
  padding-right: 5%;
  width: 100%;
}

ul.work_tabs li {
  list-style-type: none;
  font-family: Quicksand;
  border-right: 2px solid white;
  font-size: 18px;
  color: white;
  /*   transition: background-color 0.2s ease; */
}


/* ul.tabs li:hover {
  border-right: 2px solid #e1386c;
  background-color: rgba( 255, 155, 180, .9);
  font-weight: bold;
} */

#work_tab1_content,
#work_tab2_content,
#work_tab3_content,
#work_tab4_content {
  /*   background-color:red; */
  float: right;
  width: 70%;
  height: auto;
  padding-top: 5%;
}

p {
  font-family: Quicksand;
  font-size: 16px;
  color: white;
}


/* hover effect */

ul.work_tabs li {
  display: inline-block;
  position: relative;
  padding: 1em;
  cursor: pointer;
  color: white;
  z-index: 0;
}
ul.work_tabs li :hover{
  color: #000;;
}
ul.work_tabs li:before {
  content: " ";
  position: absolute;
  z-index: -1;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: #5ef1cf;
  transform: scaleX(0);
  transform-origin: 0 50%;
  transition: transform .5s ease-out;
}

ul.work_tabs li:hover:before {
  transform: scaleX(1);
}


/* Work */
@import url("https://fonts.googleapis.com/css?family=Montserrat:300,400,700,800");




* {
  -webkit-transition: .4s;
  transition: .4s;
}

a {
  text-decoration: none;
}

button {
  font-family: inherit;
  border: 0;
  cursor: pointer;
}
button:focus {
  outline: 0;
}

.movie-card {
  padding: 2px;
  background-size: contain;
  background-repeat: no-repeat;
  filter: grayscale(100%);
  width: 100%;
  max-width: 800px;
  height: 100%;
  min-height: 300px;
  display: block;
  margin: 8vh auto;
  border-radius: 8px;
  box-shadow: 0px 8px 12px 0px rgba(0, 0, 0, 0.25);
  position: relative;
}
.movie-card:hover{
  filter: grayscale(0);
    transform: scale(1.1);

}
@media screen and (max-width: 800px) {
  .movie-card {
    width: 95%;
    max-width: 95%;
  }
}
@media screen and (max-width: 600px) {
  .movie-card {
    background-position: 50% 0%;
    background-size: cover;
    height: 400px;
  }
}
.movie-card[data-movie="amazonclone"] {
  background-image: url("../assets/image/amazonclone.png");
}
.movie-card[data-movie="corona"] {
  background-image: url("../assets/image/coronatracker.png");
}
.movie-card[data-movie="onelink"] {
  background-image: url("../assets/image/onelink.png");
}
.movie-card[data-movie="airbnb"] {
  background-image: url("../assets/image/airbnbclone.png");
}
.movie-card[data-movie="hulu"] {
  background-image: url("../assets/image/huluclone.png");
}
.movie-card__overlay {
  width: 100%;
  height: 100%;
  border-radius: 8px;
  background: -webkit-gradient(linear, left top, right top, from(rgba(42, 159, 255, 0.2)), color-stop(60%, #212120), to(#212120));
  background: linear-gradient(to right, rgba(42, 159, 255, 0.2) 0%, #212120 60%, #212120 100%);
  background-blend-mode: multiply;
  position: absolute;
  top: 0;
  bottom: 0;
  right: 0;
  left: 0;
}
@media screen and (max-width: 600px) {
  .movie-card__overlay {
    background: -webkit-gradient(linear, left top, left bottom, from(rgba(42, 159, 255, 0.2)), color-stop(60%, #212120), to(#212120));
    background: linear-gradient(to bottom, rgba(42, 159, 255, 0.2) 0%, #212120 60%, #212120 100%);
  }
}
.movie-card__share {
  padding: 1em;
  display: inline-block;
  width: 100%;
  max-width: 130px;
}
@media screen and (max-width: 600px) {
  .movie-card__share {
    display: block;
    width: 100%;
  }
}
.movie-card__icon {
  color: #ffffff;
  mix-blend-mode: lighten;
  opacity: .4;
  background: none;
  padding: 0;
}
.movie-card__icon:hover {
  opacity: 1;
  mix-blend-mode: lighten;
}
.movie-card__icon:not(:first-of-type) {
  margin-left: 5px;
}
.movie-card__icon i {
  font-size: 1.2em;
}
.movie-card__content {
  width: 100%;
  max-width: 370px;
  display: -webkit-box;
  display: flex;
  -webkit-box-align: start;
          align-items: flex-start;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
          flex-direction: column;
  position: relative;
  float: right;
  padding-right: 1.2em;
  padding-bottom: 1em;
}
@media screen and (max-width: 1000px) {
  .movie-card__content {
    width: 50%;
  }
}
@media screen and (max-width: 600px) {
  .movie-card__content {
    margin-top: 4.2em;
    width: 100%;
    float: inherit;
    max-width: 100%;
    padding: 0 1em 1em;
  }
}
.movie-card__header {
  margin-bottom: 2em;
}
.movie-card__title {
  color: #ffffff;
  margin-bottom: .25em;
  opacity: .75;
}
.movie-card__info {
  text-transform: uppercase;
  letter-spacing: 2px;
  font-size: .8em;
  color: #2a9fff;
  line-height: 1;
  margin: 0;
  font-weight: 700;
  opacity: .5;
}
.movie-card__desc {
  font-weight: 300;
  opacity: .84;
  margin-bottom: 2em;
  overflow: hidden;
display: -webkit-box;
-webkit-line-clamp: 3;
-webkit-box-orient: vertical;
}
.movie-card__desc:hover{
  display: block;
}

h1, h2, h3 {
  font-family: "Montserrat", helvetica, arial, sans-serif;
  text-transform: uppercase;
  letter-spacing: 2px;
  line-height: 1;
  font-weight: 400;
}

.btn {
    border-radius: 10px;

  padding: .5rem 2rem;
  background-color: rgba(255, 255, 255, 0.4);
  color: white;
}

.btn-outline {
  background-color: transparent;
  border: 3px solid #ffffff;
}

.btn::before {
  font-family: 'Material Icons';
  vertical-align: middle;
  font-size: 1.5em;
  padding-right: .5em;
}

.btn-outline:hover {
  border-color: #2a9fff;
  color: #2a9fff;
  box-shadow: 0px 1px 8px 0px rgba(245, 199, 0, 0.2);
}

</style>

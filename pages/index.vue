<template>
  <div class="container">
   <p>Hi, I am</p>
   <span>Akarsh Barar</span><br/>
   <div class="part__first">

        <div class="designation">Full Stack Software Developer</div>
        <div class="description">
          I am Full Stack Softare Developer based in Faridabad,India. I am interested in building mobile apps and websites. I am also interested in open source contribution and teaching thats why I have a youtube channel were I teach how to make applications using Flutter. 
        </div>
        <button class="btn btn-5">Get In touch</button>
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
                  <h3> Full Stack Software Developer <h2><a href="#">@NovelVox</a></h2> </h3>
                  <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eos, ullam, illum impedit earum minima maiores totam libero ratione tempora ea iusto facilis voluptate neque aspernatur atque soluta non doloremque porro?</p>
                </div>
                
                <!-- <div id="work_tab2_content">
                  <p> Passed Intermediate with 84% from ISC board. </p>
                </div>

                <div id="work_tab3_content">
                  <p> Passed High School with 82% from ICSE Board. </p>
                </div> -->

                

                <!--     closing tab content div -->
              </div>
              <!--     closing tab div -->
            </div>
      </div>   
   </div>

     <div class="education" id="aboutme">
      <h1><span>03.</span> Educational Background </h1>
      <div class="education__data">
            
            <div class="tab_div">
              <div class="tabs_menu">
                <ul class="tabs">
                  <li id="tab1"> Graduation </li>
                  <li id="tab2"> Intermediate</li>
                  <li id="tab3"> High School </li>
                </ul>
                <!--     closing tabs menu div -->
              </div>
              <div class="tab_content">
                <div id="tab1_content">
                  <p> B.Tech in Computer Science </p>
                  <!--       closes tab 1 content -->
                </div>
                
                <div id="tab2_content">
                  <p> Passed Intermediate with 84% from ISC board. </p>
                  <!--       closes tab 2 content -->
                </div>

                <div id="tab3_content">
                  <p> Passed High School with 82% from ICSE Board. </p>
                  <!--       closes tab 3 content -->
                </div>

                

                <!--     closing tab content div -->
              </div>
              <!--     closing tab div -->
            </div>
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

        $("#work_tab1").click(function() {
          $("#work_tab1_content").show();
          $("#work_tab2_content").hide();
          $("#work_tab3_content").hide();
          $("#work_tab4_content").hide();
        });

        $("#work_tab2").click(function() {
          $("#work_tab2_content").show();
          $("#work_tab1_content").hide();
          $("#work_tab3_content").hide();
          $("#work_tab4_content").hide();
        });

        $("#work_tab3").click(function() {
          $("#work_tab3_content").show();
          $("#work_tab1_content").hide();
          $("#work_tab2_content").hide();
          $("#work_tab4_content").hide();
        });

        $("#work_tab4").click(function() {
          $("#work_tab4_content").show();
          $("#work_tab1_content").hide();
          $("#work_tab2_content").hide();
          $("#work_tab3_content").hide();
        });
// Educational 

        $("#tab1_content").hide();
        $("#tab2_content").hide();
        $("#tab3_content").hide();
        $("#tab4_content").hide();

        $("#tab1").click(function() {
          $("#tab1_content").show();
          $("#tab2_content").hide();
          $("#tab3_content").hide();
          $("#tab4_content").hide();
        });

        $("#tab2").click(function() {
          $("#tab2_content").show();
          $("#tab1_content").hide();
          $("#tab3_content").hide();
          $("#tab4_content").hide();
        });

        $("#tab3").click(function() {
          $("#tab3_content").show();
          $("#tab1_content").hide();
          $("#tab2_content").hide();
          $("#tab4_content").hide();
        });

        $("#tab4").click(function() {
          $("#tab4_content").show();
          $("#tab1_content").hide();
          $("#tab2_content").hide();
          $("#tab3_content").hide();
        });



      
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

.btn-5 {
  border: 0 solid;
  outline-color: rgba(255, 255, 255, 0.5);
  outline-offset: 0px;
  text-shadow: none;
  -webkit-transition: all 1250ms cubic-bezier(0.19, 1, 0.22, 1);
  transition: all 1250ms cubic-bezier(0.19, 1, 0.22, 1);
}

.btn-5:hover {
  border: 1px solid;
  box-shadow: inset 0 0 20px rgba(255, 255, 255, 0.5),
    0 0 20px rgba(255, 255, 255, 0.2);
  outline-color: rgba(255, 255, 255, 0);
  outline-offset: 15px;
  text-shadow: 1px 1px 2px #427388;
}

.btn {
  margin-top: 10px;
  border: #5ef1cf;
  border-radius: 10px;
  cursor: pointer;
  font-size: 16px;
  font-weight: 400;
  line-height: 45px;
  max-width: 160px;
  position: relative;
  text-decoration: none;
  text-transform: uppercase;
  width: 100%;
}

.btn:hover {
  text-decoration: none;
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


@import 'https://fonts.googleapis.com/css?family=Quicksand';
@media screen and (max-width: 400px) {
  .tab_div {
    display: none;
  }
}


.education__data >.tab_div {
  width: 100%;
  transform: translateZ(0);
}

.tabs_menu {
  /*   background-color:blue; */
  padding-top: 1%;
  width: 20%;
  float: left;
}

ul.tabs {
  padding: 0;
}

#tab1,
#tab2,
#tab3,
#tab4 {
  padding-top: 10%;
  padding-bottom: 20%;
  padding-left: 5%;
  padding-right: 5%;
  width: 100%;
}

ul.tabs li {
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

#tab1_content,
#tab2_content,
#tab3_content,
#tab4_content {
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

ul.tabs li {
  display: inline-block;
  position: relative;
  padding: 1em;
  cursor: pointer;
  /* background: #17171e; */
  color: #fff;
  z-index: 0;
}
ul.tabs li:hover {

  color: #000;
}
ul.tabs li:before {
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

ul.tabs li:hover:before {
  transform: scaleX(1);
}


/* work */
@import 'https://fonts.googleapis.com/css?family=Quicksand';
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
</style>

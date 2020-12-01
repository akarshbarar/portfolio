<template>
  <div class="container">
   <p>Hi, I am</p>
   <span>Akarsh Barar</span><br/>
   <div class="designation">Full Stack Software Developer</div>
    <div class="description">
      I am Full Stack Softare Developer based in Faridabad,India. I am interested in building mobile apps and websites. I am also interested in open source contribution and teaching thats why I have a youtube channel were I teach how to make applications using Flutter. 
    </div>
    <button class="btn btn-5">Get In touch</button>

    <!-- <div class="scroll-downs">
      <div class="mousey">
        <div class="scroller"></div>
      </div>
    </div> -->
    <div class="aboutme" id="aboutme">
      <h1><span>01.</span> About Me </h1>
      <div class="aboutme__data">
      <p>
        Hi, I am Akarsh Barar, a Full Stack Software Developer in Faridabad India. I enjoy working on Mobile App developent alng with keen intrest in website developmet. I love to learn new technologies and platform. I love to work on <b>Open Spurce Projects</b>
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
 <img src="https://images.unsplash.com/photo-1544723795-3fb6469f5b39?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=635&q=80"/>
 </div>
   </div>
  </div>
</template>

<script>
export default {
    head: {
    title: 'Akarsh Barar | Developer',
     link: [
          { 
             rel:"stylesheet", 
            //  href:"https://www.w3schools.com/w3css/4/w3.css"
          }
        ]
  },
  
}

</script>

<style>

@import url('https://fonts.googleapis.com/css?family=Varela');
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
html, body {
  font-family: 'Roboto', sans-serif;
  background-color: #161B33;
  color:#fff;

}
.container{
  height: 100vh;
  max-width: 80%;
  margin-left: 25%;
  margin-right: auto;
  margin-top: 10%;
}
.container>p{
  color:#5EF1CF;
  font-size: 2vw;
  font-weight: 500;
}

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
.container>span{
  font-size: 5vw;
  font-weight: 900;
}
.description{
  margin-top: 10px;
  width: 50%;
  color:rgb(236, 236, 229);
  font-size:clamp(15px,1vw,30px);

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
  box-shadow: inset 0 0 20px rgba(255, 255, 255, 0.5), 0 0 20px rgba(255, 255, 255, 0.2);
  outline-color: rgba(255, 255, 255, 0);
  outline-offset: 15px;
  text-shadow: 1px 1px 2px #427388;
}

.btn {
  margin-top: 10px;
  border: #5EF1CF;
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
  width :34px;
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
  animation-timing-function: cubic-bezier(.15,.41,.69,.94);
  animation-iteration-count: infinite;
}
@keyframes scroll {
  0% { opacity: 0; }
  10% { transform: translateY(0); opacity: 1; }
  100% { transform: translateY(15px); opacity: 0;}
}
.aboutme{
  margin-top: 15%;
  width:50%;
}
.aboutme__data{
  display:flex;
  flex-direction:row;
}

.aboutme__data>img{
  width:400px;
  height:400px;
  object-fit:contain;
}
.aboutme >h1>span{
  color: #5EF1CF;
}
h1::after {
    display: inline-block;
    content: "";
    border-top: .1rem solid lightgray;
    width: 25%;
    transform: translateY(0rem);
}
</style>

<template>
  <div class="container">
   <p>Hi, I am</p>
   <span>Akarsh Barar</span><br/>
   <div class="designation">Full Stack Software Developer</div>
    <div class="description">
      I am Full Stack Softare Developer based in Faridabad,India. I am interested in building mobile apps and websites. I am also interested in open source contribution and teaching thats why I have a youtube channel were I teach how to make applications using Flutter. 
    </div>
    <button class="btn btn-5">Get In touch</button>
  </div>
</template>

<script>
export default {
    head: {
    title: 'Akarsh Barar | Developer',
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

</style>

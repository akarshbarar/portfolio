<template>
  <div class="container">
   <p>Hi I am</p>
   <span>Akarsh Barar</span>
   
 
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

}
.container{
  height: 100vh;
  max-width: 80%;
  margin-left: 25%;
  margin-right: auto;
}
.container>p{
  color:#5EF1CF;
  font-size: 2vw;
  font-weight: 500;
}

.container>span{
  color:#fff;
  font-size: 5vw;
  font-weight: 900;
}

</style>

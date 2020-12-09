<template>
  <div>
    <Navbar/>
    <div class="content">
      <LeftSidebar/>
      <Nuxt />
      <RightSidebar/>
    </div>
   

  </div>
</template>
<script>
import Navbar from "../components/Navbar"
import LeftSidebar from "../components/LeftSideBar"
import RightSidebar from "../components/RightSideBar"

export default {
  components:{
    Navbar,
    LeftSidebar,
    RightSidebar,
    
  }  
}
</script>
<style>
html {
  font-family:
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
.content{
  display: flex;
  flex-direction: row;
  height: 25vh;
}


</style>

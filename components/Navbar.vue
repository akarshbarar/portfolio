<template>
  <div class="navbar">
      <header>
          <nav>
              <nuxt-link to="/"><img src="../assets/image/logo2.png"/></nuxt-link>
              <ul>
                  <li><nuxt-link to="/blogs">Blogs</nuxt-link></li>
                  <li><nuxt-link to="#projects">Projects</nuxt-link></li>
                  <li><nuxt-link to="#contactme">Contact Me</nuxt-link></li>
                  <li> <a href="/resume.pdf" download> Resume</a></li>
                  
              </ul>
          </nav>
      </header>
  </div>
</template>

<script>
export default {

}
</script>

<style >


.navbar{
    position: sticky;
    top: 0;
    z-index: 100;
}

header{
    background-color: #161B33;
}
nuxt-link{
    color:#fff;
}
nav{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    text-decoration: none;
    color: white;
    align-items: center;
    /* margin: 0 10px; */
    font-size: larger;
}

nav > a{
    color: white;
            text-decoration: none;

}
nav > a >img{
    width: 80px;
    height: 80px;
    object-fit: contain;
}
nav > ul{
    display: flex;
   list-style-type: none;
}
nav>ul>li{
    margin: 10px;
    color: white;
}
nav>ul>li>a{
        text-decoration: none;

    color: #fff;
}
nav>ul>li>a:hover{
    text-decoration: none;
    color: #5EF1CF;
}


</style>
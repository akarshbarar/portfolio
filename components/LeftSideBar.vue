<template>
  <div class="sidebar__left">
        <a href="https://www.linkedin.com/in/akarsh-barar-50588b131/"><font-awesome-icon :icon="['fab', 'linkedin']" style="font-size: 30px"/></a>
        <a href="https://github.com/akarshbarar/"><font-awesome-icon :icon="['fab', 'github']"  style="font-size: 30px"/></a>
        <a href="https://www.facebook.com/akarsh.barar.7"><font-awesome-icon :icon="['fab', 'facebook']"  style="font-size: 30px"/></a>
        <a href="https://codepen.io/akarsh-barar/"><font-awesome-icon :icon="['fab', 'codepen']"  style="font-size: 30px"/></a>
        <a href="https://www.instagram.com/mycodecave/"><font-awesome-icon :icon="['fab', 'instagram']"  style="font-size: 30px"/></a>
        <a href="https://www.youtube.com/c/CodeCave"><font-awesome-icon :icon="['fab', 'youtube']"  style="font-size: 30px"/></a>
        <a href="https://twitter.com/CodeCave2"><font-awesome-icon :icon="['fab', 'twitter']"  style="font-size: 30px"/></a>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.sidebar__left{
    overflow-y: hidden;
    position: fixed;
    z-index: 90;
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    bottom: 0;
    margin-left: 2%;
    height: 90%;

}
svg{
    color: white;
    
}

 svg:hover{
    color:#5EF1CF;
}


</style>
<template>
  <div class="sidebar__left">
        <a href="#"><font-awesome-icon :icon="['fab', 'linkedin']" style="font-size: 30px"/></a>
        <a href="#"><font-awesome-icon :icon="['fab', 'github']"  style="font-size: 30px"/></a>
        <a href="#"><font-awesome-icon :icon="['fab', 'facebook']"  style="font-size: 30px"/></a>
        <a href="#"><font-awesome-icon :icon="['fab', 'codepen']"  style="font-size: 30px"/></a>
        <a href="#"><font-awesome-icon :icon="['fab', 'instagram']"  style="font-size: 30px"/></a>
        <a href="#"><font-awesome-icon :icon="['fab', 'youtube']"  style="font-size: 30px"/></a>
        <a href="#"><font-awesome-icon :icon="['fab', 'twitter']"  style="font-size: 30px"/></a>
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
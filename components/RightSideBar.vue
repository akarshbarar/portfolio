<template>
  <div class="sidebar__right">
      <a href="mailto:barar.akarsh8@gmail.com">barar.akarsh8@gmail.com
</a>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.sidebar__right{
    position: fixed;
    top:50%;
    right: 2%;
    z-index: 90;
     writing-mode: vertical-lr;
     text-orientation:sideways;
     margin-right: 10px;
     height: 100%;
     bottom: 0;
}
.sidebar__right > a {
    text-decoration: none;
    color: white;
}
.sidebar__right > a:hover{
    color: #5EF1CF;
}
@media screen and (max-width: 950px) {
  .sidebar__right{
    display: none;
    visibility: hidden;
  }
}
</style>
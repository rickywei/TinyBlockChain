<template>
  <div id="app" >
    <router-view></router-view>
    
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};



</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* height: 100%; */
  /* background: black;
  height:100% */
  /* margin-top: 60px; */
}
html,body{
    height:100%;
    width:100%;
    background-image: linear-gradient(120deg, #e0c3fc 0%, #8ec5fc 100%);
    
}
</style>

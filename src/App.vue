<template>
  <div id="app">
    
      <div >
        <img src="./assets/1.jpg" width="800px" />
        <ejCounter />
      </div> <br>

      <div >
        <img src="./assets/2.jpg" width="800px"/>
        <ejCounter />
      </div>  <br> 
    
      <div >
        <img src="./assets/3.jpg" width="800px" />
        <ejCounter />
      </div><br>

      <div >
        <img src="./assets/4.jpg"  width="800px"/>
        <ejCounter />
      </div><br>
   
    
      <div >
        <img src="./assets/5.jpg" width="800px" />
        <ejCounter />
      </div><br>

      <div >
        <img src="./assets/6.jpg" width="800px"/>
        <ejCounter />  
    </div><br>

  </div>
</template>

<script>
import ejCounter from "./components/ejCounter.vue";

export default {
  name: "App",
  components: {
    ejCounter,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgb(88, 0, 88);
  margin-top: 60px;
  background-color: rgb(255, 255, 255);
}
</style>

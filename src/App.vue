<template>
  
   <div>
        <NavBar></NavBar>
        <router-view/>
    </div>
</template>

<script>
// import { Tooltip, initTE } from "tw-elements";
import NavBar from './components/NavBar.vue'


export default {
  name: 'App',
  components: {
    
    NavBar
  },
  // onMounted: function() {
  //   console.log('mounted');
  //   initTE({ Tooltip });
  // }
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<template>
    <div class="hello">
      This is Navbar
      <div id="nav">
            <router-link to="/">Home </router-link> 
            <router-link to="/about">About</router-link>
            <router-link to="/contact">Contact</router-link>
        </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'NavBar',
    
  }
  </script>
  
  
<template>   

  

    <!-- Right-aligned Navbar -->
  <nav class="navbar">
    <div class="container flex items-center justify-between">
      <div class="logo">
        <img src="logo.jpg" alt="College Logo">
      </div>
      <div class="search-bar">
        <input type="text" placeholder="Search">
      </div>
      <div class="auth-buttons">
        <button>Login</button>
        <button @click="()=>{ modal=true ; openSignupModal() ;}" class="signup-button">Sign Up</button>
      </div>
    </div>
  </nav>



  <!-- Carousel -->
  <div class="carousel">
    <div class="carousel-images">
      <img src="clg.webp" alt="Image 1" class="carousel-image">
      <img src="clg2.webp" alt="Image 2" class="carousel-image">
      <img src="clg3.webp" alt="Image 3" class="carousel-image">
    </div>
    <div class="search-overlay">
      <h1>Find Your Perfect College</h1>
      <input type="text" placeholder="Search for courses, colleges, etc.">
    </div>
  </div>












</template>

<script >



document.addEventListener('DOMContentLoaded', function () {
  // Get all carousel images
  const carouselImages = document.querySelectorAll('.carousel-image');

  // Set initial index
  let currentIndex = 0;

  // Function to show the next image
  function showNextImage() {
    carouselImages[currentIndex].style.display = 'none';

    // Increment index
    currentIndex = (currentIndex + 1) % carouselImages.length;

    // Show the next image
    carouselImages[currentIndex].style.display = 'block';
  }

  // Set interval to change images every 3 seconds (adjust as needed)
  setInterval(showNextImage, 3000);
});



export default {
    name: 'Home-Page' ,
    data() {
        return {
        modal: false,
        };
    },
    methods: {
        openSignupModal() {
        this.modal = true;
        console.log('coming in modal')
        document.getElementById('signupModal').style.display = 'flex';
        },
        closeSignupModal() {
        this.modal = false;
        console.log('coming in close')
        document.getElementById('signupModal').style.display = 'none';
        },
        register() {
        // Handle form submission logic here
        console.log('coming in register')
        },
    },
};

</script>

<style>
body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
}

.container {
  width: 80%;
  margin: 0 auto;
}

body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
}

.container {
  width: 80%;
  margin: 0 auto;
}

/* Right-aligned Navbar Styles */
.navbar {
  background-color: #3498db;
  padding: 10px 0;
  color: #fff;
}

.logo img {
  height: 40px;
}

.flex {
  display: flex;
}

.items-center {
  align-items: center;
}

.justify-between {
  justify-content: space-between;
}

/* Search Bar Styles */
.search-bar {
  flex-grow: 1;
  margin: 0 20px;
}

.search-bar input {
  padding: 10px;
  font-size: 16px;
  border: none;
  border-radius: 5px;
  width: 100%;
  max-width: 400px;
}

/* Auth Buttons Styles */
.auth-buttons button {
  background-color: transparent;
  border: none;
  color: #fff;
  cursor: pointer;
  margin-left: 10px;
  font-size: 16px;
}

.signup-button {
  background-color: #fff;
  color: #3498db;
  padding: 8px 16px;
  border-radius: 5px;
}

/* Carousel Styles */
.carousel {
  position: relative;
}

.carousel-image {
  display: none;
  width: 100%;
  height: auto;
}

/* Initial state */
.carousel-image:first-child {
  display: block;
}

.search-overlay {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  color: #fff;
}

.search-overlay h1 {
  font-size: 36px;
  margin-bottom: 20px;
}

.search-overlay input {
  padding: 10px;
  font-size: 16px;
  border: none;
  border-radius: 5px;
  width: 300px;
  max-width: 80%;
}


/* Carousel start */ 

.carousel-image {
  display: none;
  width: 100%;
  height: auto;
}

/* Initial state */
.carousel-image:first-child {
  display: block;
}

.search-overlay {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  color: #fff;
}

.search-overlay h1 {
  font-size: 36px;
  margin-bottom: 20px;
}

.search-overlay input {
  padding: 10px;
  font-size: 16px;
  border: none;
  border-radius: 5px;
  width: 300px;
  max-width: 80%;
}



/* Add your existing styles here */

/* Modal Styles */
.modal {
  display: none;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.7);
  justify-content: center;
  align-items: center;
}

.modal-content {
  background-color: #fff;
  padding: 20px;
  max-width: 600px;
  margin: 0 auto;
  position: relative;
  border-radius: 10px;
  overflow: hidden;
  display: flex;
}

.close {
  position: absolute;
  top: 10px;
  right: 10px;
  font-size: 20px;
  cursor: pointer;
}

.modal-image img {
  max-width: 100%;
  height: auto;
}

.signup-form {
  flex-grow: 1;
  padding: 20px;
  text-align: center;
}

/* #signupModal{
    display : flex
} */
/* Add more styling as needed */



</style>


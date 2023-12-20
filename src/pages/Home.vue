<template>
  <!-- <section class="bg_img">
        <nav class="nav_menu">
          <ul>
            <li><a href="">BTech</a></li>
            <li><a href="">MTech</a></li>
            <li><a href="">BBA</a></li>
            <li><a href="">BCA</a></li>
            <li><a href="">Home</a></li>
            <li><a href="">Home</a></li>
            <li><a href="">Home</a></li>
            <li><a href="">Home</a></li>
            <li><a href="">Home</a></li>
            <li><a href="">Home</a></li>
            <li><a href="">Home</a></li>
            <li><a href="">Home</a></li>
          </ul>
        </nav>
        
    </section> -->

  <!-- Right-aligned Navbar -->
  <nav class="navbar">
    <div class="container flex items-center justify-between">



      <!-- <div class="logo">
        <img src="logo.jpg" alt="College Logo">
      </div>
      <div class="search-bar">
        <input type="text" placeholder="Search">
      </div>
      <div class="auth-buttons">
        <router-link   to="/login"><button  >Login</button></router-link>
        <router-link    to="/register"><button class="signup-button" >Register</button></router-link>
        <button v-if="!user" v-on:click="logout"   class="signup-button" >Logout</button>
      </div> -->





      <!-- TW Elements is free under AGPL, with commercial license required for specific uses. See more details: https://tw-elements.com/license/ and contact us for queries at tailwind@mdbootstrap.com -->
      <nav
        class="relative flex w-full flex-wrap items-center justify-between bg-[#FBFBFB]  text-neutral-500 shadow-lg hover:text-neutral-700 focus:text-neutral-700 dark:bg-neutral-600 lg:py-4">
        <div class="flex w-full flex-wrap items-center justify-between px-3">
          <!-- Left elements -->
          <div class="flex">
            <!-- Brand -->
            <a class="mx-2 my-1 flex items-center text-neutral-900 hover:text-neutral-900 focus:text-neutral-900 lg:mb-0 lg:mt-0"
              href="#">
              <img class="mr-2" src="../../public/logo.jpg" style="height: 20px" alt="TE Logo" loading="lazy" />
            </a>
            <form class="hidden md:flex">
              <input type="search"
                class="relative m-0 block w-[250px] min-w-0 flex-auto rounded border border-solid border-neutral-300 bg-transparent bg-clip-padding px-3 text-base font-normal leading-[1.6] text-neutral-700 outline-none transition duration-200 ease-in-out focus:z-[3] focus:border-primary focus:text-neutral-700 focus:shadow-[inset_0_0_0_1px_rgb(59,113,202)] focus:outline-none dark:border-neutral-500 dark:text-neutral-200 dark:placeholder:text-neutral-200 dark:focus:border-primary motion-reduce:transition-none"
                placeholder="Search" aria-label="Search" aria-describedby="button-addon2" />

              <!--Search icon-->
              <span
                class="input-group-text flex items-center whitespace-nowrap rounded px-3 text-center text-base font-normal text-neutral-700 dark:text-neutral-200"
                id="basic-addon2">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="h-5 w-5">
                  <path fill-rule="evenodd"
                    d="M9 3.5a5.5 5.5 0 100 11 5.5 5.5 0 000-11zM2 9a7 7 0 1112.452 4.391l3.328 3.329a.75.75 0 11-1.06 1.06l-3.329-3.328A7 7 0 012 9z"
                    clip-rule="evenodd" />
                </svg>
              </span>
            </form>
          </div>
          <!-- Left elements -->

          <!-- Center elements -->
          <ul class="list-style-none mx-auto hidden flex-row pl-0 md:flex" data-te-navbar-nav-ref>
            <li class="px-2" data-te-nav-item-ref>
              <a class="text-neutral-500 transition duration-200 hover:text-neutral-700 hover:ease-in-out focus:text-neutral-700 disabled:text-black/30 dark:text-neutral-200 dark:hover:text-neutral-300 dark:focus:text-neutral-300 [&.active]:text-black/90 dark:[&.active]:text-zinc-400 motion-reduce:transition-none "
                href="#" data-te-nav-link-ref><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"
                  fill="currentColor" class="h-7 w-7">
                  <path fill-rule="evenodd"
                    d="M9.293 2.293a1 1 0 011.414 0l7 7A1 1 0 0117 11h-1v6a1 1 0 01-1 1h-2a1 1 0 01-1-1v-3a1 1 0 00-1-1H9a1 1 0 00-1 1v3a1 1 0 01-1 1H5a1 1 0 01-1-1v-6H3a1 1 0 01-.707-1.707l7-7z"
                    clip-rule="evenodd" />
                </svg>
                <!-- Notification counter -->
                <span
                  class="absolute -mt-7 ml-4 rounded-full bg-danger px-[0.50em] py-[0.25em] text-[0.6rem] font-bold leading-none text-white">1</span>
              </a>
            </li>

            <li class="px-2" data-te-nav-item-ref>
              <a class="text-neutral-500 transition duration-200 hover:text-neutral-700 hover:ease-in-out focus:text-neutral-700 disabled:text-black/30 dark:text-neutral-200 dark:hover:text-neutral-300 dark:focus:text-neutral-300 [&.active]:text-black/90 dark:[&.active]:text-neutral-400 motion-reduce:transition-none"
                href="#" data-te-nav-link-ref><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"
                  fill="currentColor" class="h-7 w-7">
                  <path
                    d="M3.5 2.75a.75.75 0 00-1.5 0v14.5a.75.75 0 001.5 0v-4.392l1.657-.348a6.449 6.449 0 014.271.572 7.948 7.948 0 005.965.524l2.078-.64A.75.75 0 0018 12.25v-8.5a.75.75 0 00-.904-.734l-2.38.501a7.25 7.25 0 01-4.186-.363l-.502-.2a8.75 8.75 0 00-5.053-.439l-1.475.31V2.75z" />
                </svg>
              </a>
            </li>

            <li class="px-2" data-te-nav-item-ref>
              <a class="text-neutral-500 transition duration-200 hover:text-neutral-700 hover:ease-in-out focus:text-neutral-700 disabled:text-black/30 dark:text-neutral-200 dark:hover:text-neutral-300 dark:focus:text-neutral-300 [&.active]:text-black/90 dark:[&.active]:text-neutral-400 motion-reduce:transition-none"
                href="#" data-te-nav-link-ref><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"
                  fill="currentColor" class="h-7 w-7">
                  <path
                    d="M3.25 4A2.25 2.25 0 001 6.25v7.5A2.25 2.25 0 003.25 16h7.5A2.25 2.25 0 0013 13.75v-7.5A2.25 2.25 0 0010.75 4h-7.5zM19 4.75a.75.75 0 00-1.28-.53l-3 3a.75.75 0 00-.22.53v4.5c0 .199.079.39.22.53l3 3a.75.75 0 001.28-.53V4.75z" />
                </svg>
              </a>
            </li>

            <li class="px-2" data-te-nav-item-ref>
              <a class="text-neutral-500 transition duration-200 hover:text-neutral-700 hover:ease-in-out focus:text-neutral-700 disabled:text-black/30 dark:text-neutral-200 dark:hover:text-neutral-300 dark:focus:text-neutral-300 [&.active]:text-black/90 dark:[&.active]:text-neutral-400 motion-reduce:transition-none"
                href="#" data-te-nav-link-ref><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"
                  fill="currentColor" class="h-7 w-7">
                  <path fill-rule="evenodd"
                    d="M6 5v1H4.667a1.75 1.75 0 00-1.743 1.598l-.826 9.5A1.75 1.75 0 003.84 19H16.16a1.75 1.75 0 001.743-1.902l-.826-9.5A1.75 1.75 0 0015.333 6H14V5a4 4 0 00-8 0zm4-2.5A2.5 2.5 0 007.5 5v1h5V5A2.5 2.5 0 0010 2.5zM7.5 10a2.5 2.5 0 005 0V8.75a.75.75 0 011.5 0V10a4 4 0 01-8 0V8.75a.75.75 0 011.5 0V10z"
                    clip-rule="evenodd" />
                </svg>
              </a>
            </li>

            <li class="px-2" data-te-nav-item-ref>
              <a class="text-neutral-500 transition duration-200 hover:text-neutral-700 hover:ease-in-out focus:text-neutral-700 disabled:text-black/30 dark:text-neutral-200 dark:hover:text-neutral-300 dark:focus:text-neutral-300 [&.active]:text-black/90 dark:[&.active]:text-neutral-400 motion-reduce:transition-none"
                href="#" data-te-nav-link-ref><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"
                  fill="currentColor" class="h-7 w-7">
                  <path
                    d="M10 9a3 3 0 100-6 3 3 0 000 6zM6 8a2 2 0 11-4 0 2 2 0 014 0zM1.49 15.326a.78.78 0 01-.358-.442 3 3 0 014.308-3.516 6.484 6.484 0 00-1.905 3.959c-.023.222-.014.442.025.654a4.97 4.97 0 01-2.07-.655zM16.44 15.98a4.97 4.97 0 002.07-.654.78.78 0 00.357-.442 3 3 0 00-4.308-3.517 6.484 6.484 0 011.907 3.96 2.32 2.32 0 01-.026.654zM18 8a2 2 0 11-4 0 2 2 0 014 0zM5.304 16.19a.844.844 0 01-.277-.71 5 5 0 019.947 0 .843.843 0 01-.277.71A6.975 6.975 0 0110 18a6.974 6.974 0 01-4.696-1.81z" />
                </svg>
                <span
                  class="absolute -mt-7 ml-5 rounded-full bg-danger px-[0.50em] py-[0.25em] text-[0.6rem] font-bold leading-none text-white">2</span>
              </a>
            </li>
          </ul>
          <!-- Center elements -->

          <!-- Right elements -->
          <ul class="list-style-none ml-auto flex flex-row pl-0 md:pl-4" data-te-navbar-nav-ref>
            <li class="px-2" data-te-nav-item-ref>
              <a class="text-neutral-500 transition duration-200 hover:text-neutral-700 hover:ease-in-out focus:text-neutral-700 disabled:text-black/30 dark:text-neutral-200 dark:hover:text-neutral-300 dark:focus:text-neutral-300 sm:flex [&.active]:text-black/90 dark:[&.active]:text-zinc-400 motion-reduce:transition-none"
                href="#" data-te-nav-link-ref><img src="https://tecdn.b-cdn.net/img/new/avatars/1.jpg"
                  class="rounded-full" style="height: 25px; width: 25px" alt="TE Avatar" loading="lazy" />
                <strong class="ml-1 hidden sm:block">John</strong>
              </a>
            </li>

            <li class="px-2" data-te-nav-item-ref>
              <a class="text-neutral-500 transition duration-200 hover:text-neutral-700 hover:ease-in-out focus:text-neutral-700 disabled:text-black/30 dark:text-neutral-200 dark:hover:text-neutral-300 dark:focus:text-neutral-300 [&.active]:text-black/90 dark:[&.active]:text-neutral-400 motion-reduce:transition-none"
                href="#" data-te-nav-link-ref><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"
                  fill="currentColor" class="h-7 w-7">
                  <path fill-rule="evenodd"
                    d="M10 18a8 8 0 100-16 8 8 0 000 16zm.75-11.25a.75.75 0 00-1.5 0v2.5h-2.5a.75.75 0 000 1.5h2.5v2.5a.75.75 0 001.5 0v-2.5h2.5a.75.75 0 000-1.5h-2.5v-2.5z"
                    clip-rule="evenodd" />
                </svg>
              </a>
            </li>

            <li class="relative px-2" data-te-dropdown-ref>
              <!-- First dropdown trigger -->
              <a class="hidden-arrow flex items-center text-neutral-500 transition duration-200 hover:text-neutral-700 hover:ease-in-out focus:text-neutral-700 disabled:text-black/30 dark:text-neutral-200 dark:hover:text-neutral-300 dark:focus:text-neutral-300 [&.active]:text-black/90 dark:[&.active]:text-neutral-400 motion-reduce:transition-none"
                href="#" id="dropdownMenuButton1" role="button" data-te-dropdown-toggle-ref aria-expanded="false">
                <!-- Dropdown trigger icon -->
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="h-7 w-7">
                  <path
                    d="M3.505 2.365A41.369 41.369 0 019 2c1.863 0 3.697.124 5.495.365 1.247.167 2.18 1.108 2.435 2.268a4.45 4.45 0 00-.577-.069 43.141 43.141 0 00-4.706 0C9.229 4.696 7.5 6.727 7.5 8.998v2.24c0 1.413.67 2.735 1.76 3.562l-2.98 2.98A.75.75 0 015 17.25v-3.443c-.501-.048-1-.106-1.495-.172C2.033 13.438 1 12.162 1 10.72V5.28c0-1.441 1.033-2.717 2.505-2.914z" />
                  <path
                    d="M14 6c-.762 0-1.52.02-2.271.062C10.157 6.148 9 7.472 9 8.998v2.24c0 1.519 1.147 2.839 2.71 2.935.214.013.428.024.642.034.2.009.385.09.518.224l2.35 2.35a.75.75 0 001.28-.531v-2.07c1.453-.195 2.5-1.463 2.5-2.915V8.998c0-1.526-1.157-2.85-2.729-2.936A41.645 41.645 0 0014 6z" />
                </svg>
                <!-- Notification counter -->
                <span
                  class="absolute -mt-6 ml-5 rounded-full bg-danger px-[0.50em] py-[0.25em] text-[0.6rem] font-bold leading-none text-white">6</span>
              </a>
              <!-- Dropdown menu -->
              <ul
                class="absolute z-[1000] float-left hidden min-w-max list-none overflow-hidden rounded-lg border-none bg-white bg-clip-padding text-left text-base shadow-lg dark:bg-neutral-700 [&[data-te-dropdown-show]]:block"
                aria-labelledby="dropdownMenuButton1" data-te-dropdown-menu-ref>
                <!-- Dropdown menu items -->
                <li>
                  <a class="block w-full whitespace-nowrap bg-transparent px-4 py-2 text-sm font-normal text-neutral-700 hover:bg-neutral-100 active:text-neutral-800 active:no-underline disabled:pointer-events-none disabled:bg-transparent disabled:text-neutral-400 dark:text-neutral-200 dark:hover:bg-white/30"
                    href="#" data-te-dropdown-item-ref>Some news</a>
                </li>
                <li>
                  <a class="block w-full whitespace-nowrap bg-transparent px-4 py-2 text-sm font-normal text-neutral-700 hover:bg-neutral-100 active:text-neutral-800 active:no-underline disabled:pointer-events-none disabled:bg-transparent disabled:text-neutral-400 dark:text-neutral-200 dark:hover:bg-white/30"
                    href="#" data-te-dropdown-item-ref>Another news</a>
                </li>
                <li>
                  <a class="block w-full whitespace-nowrap bg-transparent px-4 py-2 text-sm font-normal text-neutral-700 hover:bg-neutral-100 active:text-neutral-800 active:no-underline disabled:pointer-events-none disabled:bg-transparent disabled:text-neutral-400 dark:text-neutral-200 dark:hover:bg-white/30"
                    href="#" data-te-dropdown-item-ref>Something else here</a>
                </li>
              </ul>
            </li>

            <li class="relative px-2" data-te-dropdown-ref data-te-dropdown-alignment="end">
              <!-- Second dropdown trigger -->
              <a class="hidden-arrow mr flex items-center text-neutral-500 transition duration-200 hover:text-neutral-700 hover:ease-in-out focus:text-neutral-700 disabled:text-black/30 dark:text-neutral-200 dark:hover:text-neutral-300 dark:focus:text-neutral-300 [&.active]:text-black/90 dark:[&.active]:text-neutral-400 motion-reduce:transition-none"
                href="#" id="dropdownMenuButton1" role="button" data-te-dropdown-toggle-ref aria-expanded="false">
                <!-- Dropdown trigger icon -->
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="h-7 w-7">
                  <path fill-rule="evenodd"
                    d="M5.25 9a6.75 6.75 0 0113.5 0v.75c0 2.123.8 4.057 2.118 5.52a.75.75 0 01-.297 1.206c-1.544.57-3.16.99-4.831 1.243a3.75 3.75 0 11-7.48 0 24.585 24.585 0 01-4.831-1.244.75.75 0 01-.298-1.205A8.217 8.217 0 005.25 9.75V9zm4.502 8.9a2.25 2.25 0 104.496 0 25.057 25.057 0 01-4.496 0z"
                    clip-rule="evenodd" />
                </svg>
                <!-- Notification counter -->
                <span
                  class="absolute -mt-6 ml-3 rounded-full bg-danger px-[0.50em] py-[0.25em] text-[0.6rem] font-bold leading-none text-white">12</span>
              </a>
              <!-- Dropdown menu -->
              <ul
                class="absolute z-[1000] float-left hidden min-w-max list-none overflow-hidden rounded-lg border-none bg-white bg-clip-padding text-left text-base shadow-lg dark:bg-neutral-700 [&[data-te-dropdown-show]]:block"
                aria-labelledby="dropdownMenuButton1" data-te-dropdown-menu-ref>
                <!-- Dropdown menu items -->
                <li>
                  <a class="block w-full whitespace-nowrap bg-transparent px-4 py-2 text-sm font-normal text-neutral-700 hover:bg-neutral-100 active:text-neutral-800 active:no-underline disabled:pointer-events-none disabled:bg-transparent disabled:text-neutral-400 dark:text-neutral-200 dark:hover:bg-white/30"
                    href="#" data-te-dropdown-item-ref>Some news</a>
                </li>
                <li>
                  <a class="block w-full whitespace-nowrap bg-transparent px-4 py-2 text-sm font-normal text-neutral-700 hover:bg-neutral-100 active:text-neutral-800 active:no-underline disabled:pointer-events-none disabled:bg-transparent disabled:text-neutral-400 dark:text-neutral-200 dark:hover:bg-white/30"
                    href="#" data-te-dropdown-item-ref>Another news</a>
                </li>
                <li>
                  <a class="block w-full whitespace-nowrap bg-transparent px-4 py-2 text-sm font-normal text-neutral-700 hover:bg-neutral-100 active:text-neutral-800 active:no-underline disabled:pointer-events-none disabled:bg-transparent disabled:text-neutral-400 dark:text-neutral-200 dark:hover:bg-white/30"
                    href="#" data-te-dropdown-item-ref>Something else here</a>
                </li>
              </ul>
            </li>

            <li class="relative px-2" data-te-dropdown-ref data-te-dropdown-alignment="end">
              <!-- Third dropdown trigger -->
              <a class="hidden-arrow mr flex items-center text-neutral-500 transition duration-200 hover:text-neutral-700 hover:ease-in-out focus:text-neutral-700 disabled:text-black/30 dark:text-neutral-200 dark:hover:text-neutral-300 dark:focus:text-neutral-300 [&.active]:text-black/90 dark:[&.active]:text-neutral-400 motion-reduce:transition-none"
                href="#" id="dropdownMenuButton1" role="button" data-te-dropdown-toggle-ref aria-expanded="false">
                <!-- Dropdown trigger icon -->
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="h-7 w-7">
                  <path fill-rule="evenodd"
                    d="M5.23 7.21a.75.75 0 011.06.02L10 11.168l3.71-3.938a.75.75 0 111.08 1.04l-4.25 4.5a.75.75 0 01-1.08 0l-4.25-4.5a.75.75 0 01.02-1.06z"
                    clip-rule="evenodd" />
                </svg>
              </a>
              <!-- Dropdown menu -->
              <ul
                class="absolute z-[1000] float-left hidden min-w-max list-none overflow-hidden rounded-lg border-none bg-white bg-clip-padding text-left text-base shadow-lg dark:bg-neutral-700 [&[data-te-dropdown-show]]:block"
                aria-labelledby="dropdownMenuButton1" data-te-dropdown-menu-ref>
                <!-- Dropdown menu items -->
                <li>
                  <a class="block w-full whitespace-nowrap bg-transparent px-4 py-2 text-sm font-normal text-neutral-700 hover:bg-neutral-100 active:text-neutral-800 active:no-underline disabled:pointer-events-none disabled:bg-transparent disabled:text-neutral-400 dark:text-neutral-200 dark:hover:bg-white/30"
                    href="#" data-te-dropdown-item-ref>Some news</a>
                </li>
                <li>
                  <a class="block w-full whitespace-nowrap bg-transparent px-4 py-2 text-sm font-normal text-neutral-700 hover:bg-neutral-100 active:text-neutral-800 active:no-underline disabled:pointer-events-none disabled:bg-transparent disabled:text-neutral-400 dark:text-neutral-200 dark:hover:bg-white/30"
                    href="#" data-te-dropdown-item-ref>Another news</a>
                </li>
                <li>
                  <a class="block w-full whitespace-nowrap bg-transparent px-4 py-2 text-sm font-normal text-neutral-700 hover:bg-neutral-100 active:text-neutral-800 active:no-underline disabled:pointer-events-none disabled:bg-transparent disabled:text-neutral-400 dark:text-neutral-200 dark:hover:bg-white/30"
                    href="#" data-te-dropdown-item-ref>Something else here</a>
                </li>
              </ul>
            </li>
          </ul>
          <!-- Right elements -->
        </div>
      </nav>





    </div>
  </nav>



  <!-- Carousel -->
  <!-- <div class="carousel">
    <div class="carousel-images">
      <img src="clg.webp" alt="Image 1" class="carousel-image">
      <img src="clg2.webp" alt="Image 2" class="carousel-image">
      <img src="clg3.webp" alt="Image 3" class="carousel-image">
    </div>
    <div class="search-overlay">
      <h1>Find Your Perfect College</h1>
      <input class="banner_search" type="text" placeholder="Search for courses, colleges, etc.">
    </div>
  </div> -->





  <!-- TW Elements is free under AGPL, with commercial license required for specific uses. See more details: https://tw-elements.com/license/ and contact us for queries at tailwind@mdbootstrap.com -->
  <div id="carouselExampleCaptions" class="relative" data-te-carousel-init data-te-ride="carousel">
    <!--Carousel indicators-->
    <div class="absolute bottom-0 left-0 right-0 z-[2] mx-[15%] mb-4 flex list-none justify-center p-0"
      data-te-carousel-indicators>
      <button type="button" data-te-target="#carouselExampleCaptions" data-te-slide-to="0" data-te-carousel-active
        class="mx-[3px] box-content h-[3px] w-[30px] flex-initial cursor-pointer border-0 border-y-[10px] border-solid border-transparent bg-white bg-clip-padding p-0 -indent-[999px] opacity-50 transition-opacity duration-[600ms] ease-[cubic-bezier(0.25,0.1,0.25,1.0)] motion-reduce:transition-none"
        aria-current="true" aria-label="Slide 1"></button>
      <button type="button" data-te-target="#carouselExampleCaptions" data-te-slide-to="1"
        class="mx-[3px] box-content h-[3px] w-[30px] flex-initial cursor-pointer border-0 border-y-[10px] border-solid border-transparent bg-white bg-clip-padding p-0 -indent-[999px] opacity-50 transition-opacity duration-[600ms] ease-[cubic-bezier(0.25,0.1,0.25,1.0)] motion-reduce:transition-none"
        aria-label="Slide 2"></button>
      <button type="button" data-te-target="#carouselExampleCaptions" data-te-slide-to="2"
        class="mx-[3px] box-content h-[3px] w-[30px] flex-initial cursor-pointer border-0 border-y-[10px] border-solid border-transparent bg-white bg-clip-padding p-0 -indent-[999px] opacity-50 transition-opacity duration-[600ms] ease-[cubic-bezier(0.25,0.1,0.25,1.0)] motion-reduce:transition-none"
        aria-label="Slide 3"></button>
    </div>

    <!--Carousel items-->
    <div class="relative w-full overflow-hidden after:clear-both after:block after:content-['']">
      <!--First item-->
      <div
        class="relative float-left -mr-[100%] w-full transition-transform duration-[600ms] ease-in-out motion-reduce:transition-none"
        data-te-carousel-active data-te-carousel-item style="backface-visibility: hidden">
        <img src="../../public/clg.webp" class="block w-full" alt="..." />
        <div class="absolute inset-x-[15%] bottom-5 hidden py-5 text-center text-white md:block">
          <h5 class="text-xl">First slide label</h5>
          <p>
            Some representative placeholder content for the first slide.
          </p>
        </div>
      </div>
      <!--Second item-->
      <div
        class="relative float-left -mr-[100%] hidden w-full transition-transform duration-[600ms] ease-in-out motion-reduce:transition-none"
        data-te-carousel-item style="backface-visibility: hidden">
        <img src="../../public/clg2.webp" class="block w-full" alt="..." />
        <div class="absolute inset-x-[15%] bottom-5 hidden py-5 text-center text-white md:block">
          <h5 class="text-xl">Second slide label</h5>
          <p>
            Some representative placeholder content for the second slide.
          </p>
        </div>
      </div>
      <!--Third item-->
      <div
        class="relative float-left -mr-[100%] hidden w-full transition-transform duration-[600ms] ease-in-out motion-reduce:transition-none"
        data-te-carousel-item style="backface-visibility: hidden">
        <img src="../../public/clg3.webp" class="block w-full" alt="..." />
        <div class="absolute inset-x-[15%] bottom-5 hidden py-5 text-center text-white md:block">
          <h5 class="text-xl">Third slide label</h5>
          <p>
            Some representative placeholder content for the third slide.
          </p>
        </div>
      </div>
    </div>

    <!--Carousel controls - prev item-->
    <button
      class="absolute bottom-0 left-0 top-0 z-[1] flex w-[15%] items-center justify-center border-0 bg-none p-0 text-center text-white opacity-50 transition-opacity duration-150 ease-[cubic-bezier(0.25,0.1,0.25,1.0)] hover:text-white hover:no-underline hover:opacity-90 hover:outline-none focus:text-white focus:no-underline focus:opacity-90 focus:outline-none motion-reduce:transition-none"
      type="button" data-te-target="#carouselExampleCaptions" data-te-slide="prev">
      <span class="inline-block h-8 w-8">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
          class="h-6 w-6">
          <path stroke-linecap="round" stroke-linejoin="round" d="M15.75 19.5L8.25 12l7.5-7.5" />
        </svg>
      </span>
      <span
        class="!absolute !-m-px !h-px !w-px !overflow-hidden !whitespace-nowrap !border-0 !p-0 ![clip:rect(0,0,0,0)]">Previous</span>
    </button>
    <!--Carousel controls - next item-->
    <button
      class="absolute bottom-0 right-0 top-0 z-[1] flex w-[15%] items-center justify-center border-0 bg-none p-0 text-center text-white opacity-50 transition-opacity duration-150 ease-[cubic-bezier(0.25,0.1,0.25,1.0)] hover:text-white hover:no-underline hover:opacity-90 hover:outline-none focus:text-white focus:no-underline focus:opacity-90 focus:outline-none motion-reduce:transition-none"
      type="button" data-te-target="#carouselExampleCaptions" data-te-slide="next">
      <span class="inline-block h-8 w-8">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor"
          class="h-6 w-6">
          <path stroke-linecap="round" stroke-linejoin="round" d="M8.25 4.5l7.5 7.5-7.5 7.5" />
        </svg>
      </span>
      <span
        class="!absolute !-m-px !h-px !w-px !overflow-hidden !whitespace-nowrap !border-0 !p-0 ![clip:rect(0,0,0,0)]">Next</span>
    </button>
  </div>
</template>

<script >
import { onBeforeMount, ref } from 'vue';
import axios from 'axios';
import router from '@/router';

const setup = () => {

  // document.addEventListener('DOMContentLoaded', function () {
  //   const carouselImages = document.querySelectorAll('.carousel-image');

  //   let currentIndex = 0;

  //   function showNextImage() {
  //     carouselImages[currentIndex].style.display = 'none';

  //     currentIndex = (currentIndex + 1) % carouselImages.length;

  //     carouselImages[currentIndex].style.display = 'block';
  //   }

  //   setInterval(showNextImage, 3000);
  // });

  const isLogin = ref(false);
  const user = ref(localStorage.getItem('user'));
  const modal = ref(false);
  const logout = () => {
    console.log('logout comming')
    localStorage.clear();
    router.push('/login');
  }

  return {
    modal,
    logout
  }

}

export default { setup };


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
  background-color: rgba(0, 0, 0, 0.6);
  padding: 10px 0;
  color: #fff;
  position: fixed;
  z-index: 99;
  width: 100%;
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
  border: 1px solid #fff;
  border-radius: 5px;
  width: 300px;
  max-width: 80%;
  /* background-color: transparent; */
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


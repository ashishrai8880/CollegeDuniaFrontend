<template>
  <nav class="navbar">
    <div class="container flex items-center justify-between">


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






  <!-- TW Elements is free under AGPL, with commercial license required for specific uses. See more details: https://tw-elements.com/license/ and contact us for queries at tailwind@mdbootstrap.com -->
  <!-- Button trigger modal -->
  <!-- TW Elements is free under AGPL, with commercial license required for specific uses. See more details: https://tw-elements.com/license/ and contact us for queries at tailwind@mdbootstrap.com -->
  <!-- Button trigger modal -->
  <button ref="modal" type="button" class="invisible   transition duration-150 ease-in-out " data-te-toggle="modal"
    data-te-target="#exampleModalFullscreen" data-te-ripple-init data-te-ripple-color="light">
    Launch demo modal full screen
  </button>

  <!-- Modal -->
  <div data-te-modal-init
    class="fixed left-0 top-0 z-[1055] hidden h-full w-full overflow-y-auto overflow-x-hidden outline-none"
    id="exampleModalFullscreen" tabindex="-1" aria-labelledby="exampleModalFullscreenLabel" aria-hidden="true">
    <div data-te-modal-dialog-ref
      class="pointer-events-none relative w-auto translate-y-[-50px] opacity-0 transition-all duration-300 ease-in-out min-[0px]:m-0 min-[0px]:h-full min-[0px]:max-w-none">
      <div
        class="pointer-events-auto relative flex w-full flex-col rounded-md bg-white bg-clip-padding text-current shadow-lg outline-none dark:bg-neutral-600 min-[0px]:h-full min-[0px]:rounded-none min-[0px]:border-0">
        <div
          class="flex flex-shrink-0 items-center justify-between rounded-t-md border-b-2 border-neutral-100 border-opacity-100 p-4 dark:border-opacity-50 min-[0px]:rounded-none">
          <!-- Modal title -->
          <h5 class="text-xl font-medium leading-normal text-neutral-800 dark:text-neutral-200"
            id="exampleModalFullscreenLabel">
            Modal title
          </h5>
          <!-- Close button -->
          <button type="button"
            class="box-content rounded-none border-none hover:no-underline hover:opacity-75 focus:opacity-100 focus:shadow-none focus:outline-none"
            data-te-modal-dismiss aria-label="Close">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
              stroke="currentColor" class="h-6 w-6">
              <path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
            </svg>
          </button>
        </div>

        <!-- Modal body -->
        <div class="relative p-4 min-[0px]:overflow-y-auto">

          <div class="h-full">
            <!-- Left column container with background-->
            <div class="g-6 flex h-full flex-wrap items-center justify-center lg:justify-between">
              <div class="shrink-1 mb-12 grow-0 basis-auto md:mb-0 md:w-9/12 md:shrink-0 lg:w-6/12 xl:w-6/12">
                <img src="https://tecdn.b-cdn.net/img/Photos/new-templates/bootstrap-login-form/draw2.webp" class="w-full"
                  alt="Sample image" />
              </div>

              <!-- Right column container -->
              <div class="mb-12 md:mb-0 md:w-8/12 lg:w-5/12 xl:w-5/12">
                <form>
                  <!--Sign in section-->
                  <div class="flex flex-row items-center justify-center lg:justify-start">
                    <p class="mb-0 mr-4 text-lg">Sign in with</p>

                    <!-- Facebook -->
                    <button type="button" data-te-ripple-init data-te-ripple-color="light"
                      class="inlne-block mx-1 h-9 w-9 rounded-full bg-primary uppercase leading-normal text-white shadow-[0_4px_9px_-4px_#3b71ca] transition duration-150 ease-in-out hover:bg-primary-600 hover:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.3),0_4px_18px_0_rgba(59,113,202,0.2)] focus:bg-primary-600 focus:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.3),0_4px_18px_0_rgba(59,113,202,0.2)] focus:outline-none focus:ring-0 active:bg-primary-700 active:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.3),0_4px_18px_0_rgba(59,113,202,0.2)] dark:shadow-[0_4px_9px_-4px_rgba(59,113,202,0.5)] dark:hover:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.2),0_4px_18px_0_rgba(59,113,202,0.1)] dark:focus:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.2),0_4px_18px_0_rgba(59,113,202,0.1)] dark:active:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.2),0_4px_18px_0_rgba(59,113,202,0.1)]">
                      <!-- Facebook -->
                      <svg xmlns="http://www.w3.org/2000/svg" class="mx-auto h-3.5 w-3.5" fill="currentColor"
                        viewBox="0 0 24 24">
                        <path
                          d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z" />
                      </svg>
                    </button>

                    <!-- Twitter -->
                    <button type="button" data-te-ripple-init data-te-ripple-color="light"
                      class="inlne-block mx-1 h-9 w-9 rounded-full bg-primary uppercase leading-normal text-white shadow-[0_4px_9px_-4px_#3b71ca] transition duration-150 ease-in-out hover:bg-primary-600 hover:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.3),0_4px_18px_0_rgba(59,113,202,0.2)] focus:bg-primary-600 focus:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.3),0_4px_18px_0_rgba(59,113,202,0.2)] focus:outline-none focus:ring-0 active:bg-primary-700 active:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.3),0_4px_18px_0_rgba(59,113,202,0.2)] dark:shadow-[0_4px_9px_-4px_rgba(59,113,202,0.5)] dark:hover:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.2),0_4px_18px_0_rgba(59,113,202,0.1)] dark:focus:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.2),0_4px_18px_0_rgba(59,113,202,0.1)] dark:active:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.2),0_4px_18px_0_rgba(59,113,202,0.1)]">
                      <!-- Twitter -->
                      <svg xmlns="http://www.w3.org/2000/svg" class="mx-auto h-3.5 w-3.5" fill="currentColor"
                        viewBox="0 0 24 24">
                        <path
                          d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z" />
                      </svg>
                    </button>

                    <!-- Linkedin -->
                    <button type="button" data-te-ripple-init data-te-ripple-color="light"
                      class="inlne-block mx-1 h-9 w-9 rounded-full bg-primary uppercase leading-normal text-white shadow-[0_4px_9px_-4px_#3b71ca] transition duration-150 ease-in-out hover:bg-primary-600 hover:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.3),0_4px_18px_0_rgba(59,113,202,0.2)] focus:bg-primary-600 focus:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.3),0_4px_18px_0_rgba(59,113,202,0.2)] focus:outline-none focus:ring-0 active:bg-primary-700 active:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.3),0_4px_18px_0_rgba(59,113,202,0.2)] dark:shadow-[0_4px_9px_-4px_rgba(59,113,202,0.5)] dark:hover:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.2),0_4px_18px_0_rgba(59,113,202,0.1)] dark:focus:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.2),0_4px_18px_0_rgba(59,113,202,0.1)] dark:active:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.2),0_4px_18px_0_rgba(59,113,202,0.1)]">
                      <!-- Linkedin -->
                      <svg xmlns="http://www.w3.org/2000/svg" class="mx-auto h-3.5 w-3.5" fill="currentColor"
                        viewBox="0 0 24 24">
                        <path
                          d="M4.98 3.5c0 1.381-1.11 2.5-2.48 2.5s-2.48-1.119-2.48-2.5c0-1.38 1.11-2.5 2.48-2.5s2.48 1.12 2.48 2.5zm.02 4.5h-5v16h5v-16zm7.982 0h-4.968v16h4.969v-8.399c0-4.67 6.029-5.052 6.029 0v8.399h4.988v-10.131c0-7.88-8.922-7.593-11.018-3.714v-2.155z" />
                      </svg>
                    </button>
                  </div>

                  <!-- Separator between social media sign in and email/password sign in -->
                  <div
                    class="my-4 flex items-center before:mt-0.5 before:flex-1 before:border-t before:border-neutral-300 after:mt-0.5 after:flex-1 after:border-t after:border-neutral-300">
                    <p class="mx-4 mb-0 text-center font-semibold dark:text-white">
                      Or
                    </p>
                  </div>

                  <!-- Email input -->
                  <div class="relative mb-6">
                    <input v-model="user.email" type="text"
                      class="peer block min-h-[auto] w-full rounded border-0 bg-transparent px-3 py-[0.32rem] leading-[2.15] outline-none transition-all duration-200 ease-linear focus:placeholder:opacity-100 data-[te-input-state-active]:placeholder:opacity-100 motion-reduce:transition-none dark:text-neutral-200 dark:placeholder:text-neutral-200 [&:not([data-te-input-placeholder-active])]:placeholder:opacity-0"
                      id="exampleFormControlInput2" placeholder="Email address" />
                    <label  v-if="!user.email" for="exampleFormControlInput2"
                      class="pointer-events-none absolute left-3 top-0 mb-0 max-w-[90%] origin-[0_0] truncate pt-[0.37rem] leading-[2.15] text-neutral-500 transition-all duration-200 ease-out peer-focus:-translate-y-[1.15rem] peer-focus:scale-[0.8] peer-focus:text-primary peer-data-[te-input-state-active]:-translate-y-[1.15rem] peer-data-[te-input-state-active]:scale-[0.8] motion-reduce:transition-none dark:text-neutral-200 dark:peer-focus:text-primary">Email
                      address
                    </label>
                  </div>

                  <!-- Password input -->
                  <div class="relative mb-6">
                    <input v-model="user.password" type="password"
                      class="peer block min-h-[auto] w-full rounded border-0 bg-transparent px-3 py-[0.32rem] leading-[2.15] outline-none transition-all duration-200 ease-linear focus:placeholder:opacity-100 data-[te-input-state-active]:placeholder:opacity-100 motion-reduce:transition-none dark:text-neutral-200 dark:placeholder:text-neutral-200 [&:not([data-te-input-placeholder-active])]:placeholder:opacity-0"
                      id="exampleFormControlInput22" placeholder="Password" />
                    <label  v-if="!user.password" for="exampleFormControlInput22"
                      class="pointer-events-none absolute left-3 top-0 mb-0 max-w-[90%] origin-[0_0] truncate pt-[0.37rem] leading-[2.15] text-neutral-500 transition-all duration-200 ease-out peer-focus:-translate-y-[1.15rem] peer-focus:scale-[0.8] peer-focus:text-primary peer-data-[te-input-state-active]:-translate-y-[1.15rem] peer-data-[te-input-state-active]:scale-[0.8] motion-reduce:transition-none dark:text-neutral-200 dark:peer-focus:text-primary">Password
                    </label>
                  </div>

                  <!-- Phone input -->
                  <div class="relative mb-6 flex">
                    <!-- TW Elements is free under AGPL, with commercial license required for specific uses. See more details: https://tw-elements.com/license/ and contact us for queries at tailwind@mdbootstrap.com -->
                    <select id="dial" v-model="user.dial" data-te-select-init data-te-select-filter="true">
                      <option v-for="dial in dialCode" :value="dial.dial_code">{{ ` (${dial.dial_code}) ${dial.name}` }}
                      </option>
                    </select>
                    <label  v-if="!user.dial" for="dial"
                      class="pointer-events-none absolute left-3 top-0 mb-0 max-w-[90%] origin-[0_0] truncate pt-[0.37rem] leading-[2.15] text-neutral-500 transition-all duration-200 ease-out peer-focus:-translate-y-[1.15rem] peer-focus:scale-[0.8] peer-focus:text-primary peer-data-[te-input-state-active]:-translate-y-[1.15rem] peer-data-[te-input-state-active]:scale-[0.8] motion-reduce:transition-none dark:text-neutral-200 dark:peer-focus:text-primary">Dial
                      Code (+91) India
                    </label>

                  </div>

                  <div class="relative mb-6 flex">
                  <input v-model="user.phone" type="text"
                      class="peer block min-h-[auto] w-full rounded border-0 bg-transparent px-3 py-[0.32rem] leading-[2.15] outline-none transition-all duration-200 ease-linear focus:placeholder:opacity-100 data-[te-input-state-active]:placeholder:opacity-100 motion-reduce:transition-none dark:text-neutral-200 dark:placeholder:text-neutral-200 [&:not([data-te-input-placeholder-active])]:placeholder:opacity-0 mt-1"
                      id="phone" placeholder="Phone Number" />
                    <label  v-if="!user.phone" for="phone"
                      class="pointer-events-none absolute left-3 top-0 mb-0 max-w-[90%] origin-[0_0] truncate pt-[0.37rem] leading-[2.15] text-neutral-500 transition-all duration-200 ease-out peer-focus:-translate-y-[1.15rem] peer-focus:scale-[0.8] peer-focus:text-primary peer-data-[te-input-state-active]:-translate-y-[1.15rem] peer-data-[te-input-state-active]:scale-[0.8] motion-reduce:transition-none dark:text-neutral-200 dark:peer-focus:text-primary">Phone
                    </label> 
                  </div>

                  <div class="relative mb-6 flex">
                    <select id="city" v-model="user.city" data-te-select-init data-te-select-filter="true">
                    <option v-for="city in cityList" >{{city}}</option>
                  </select>
                  <label v-if="!user.city" for="city"
                      class="pointer-events-none absolute left-3 top-0 mb-0 max-w-[90%] origin-[0_0] truncate pt-[0.37rem] leading-[2.15] text-neutral-500 transition-all duration-200 ease-out peer-focus:-translate-y-[1.15rem] peer-focus:scale-[0.8] peer-focus:text-primary peer-data-[te-input-state-active]:-translate-y-[1.15rem] peer-data-[te-input-state-active]:scale-[0.8] motion-reduce:transition-none dark:text-neutral-200 dark:peer-focus:text-primary">City
                       Vasant Kunj (Delhi , India)
                    </label>
                  </div>

                  <div class="relative mb-6 flex">
                    <select id="course" v-model="user.course" data-te-select-init data-te-select-filter="true">
                    <option v-for="course in courseList" >{{course}}</option>
                  </select>
                  <label v-if="!user.course" for="course"
                      class="pointer-events-none absolute left-3 top-0 mb-0 max-w-[90%] origin-[0_0] truncate pt-[0.37rem] leading-[2.15] text-neutral-500 transition-all duration-200 ease-out peer-focus:-translate-y-[1.15rem] peer-focus:scale-[0.8] peer-focus:text-primary peer-data-[te-input-state-active]:-translate-y-[1.15rem] peer-data-[te-input-state-active]:scale-[0.8] motion-reduce:transition-none dark:text-neutral-200 dark:peer-focus:text-primary">City
                       Course (BTech CSE)
                    </label>
                  </div>
                  

                  <div class="mb-6 flex items-center justify-between">
                    <!-- Remember me checkbox -->
                    <div class="mb-[0.125rem] block min-h-[1.5rem] pl-[1.5rem]">
                      <input
                        class="relative float-left -ml-[1.5rem] mr-[6px] mt-[0.15rem] h-[1.125rem] w-[1.125rem] appearance-none rounded-[0.25rem] border-[0.125rem] border-solid border-neutral-300 outline-none before:pointer-events-none before:absolute before:h-[0.875rem] before:w-[0.875rem] before:scale-0 before:rounded-full before:bg-transparent before:opacity-0 before:shadow-[0px_0px_0px_13px_transparent] before:content-[''] checked:border-primary checked:bg-primary checked:before:opacity-[0.16] checked:after:absolute checked:after:-mt-px checked:after:ml-[0.25rem] checked:after:block checked:after:h-[0.8125rem] checked:after:w-[0.375rem] checked:after:rotate-45 checked:after:border-[0.125rem] checked:after:border-l-0 checked:after:border-t-0 checked:after:border-solid checked:after:border-white checked:after:bg-transparent checked:after:content-[''] hover:cursor-pointer hover:before:opacity-[0.04] hover:before:shadow-[0px_0px_0px_13px_rgba(0,0,0,0.6)] focus:shadow-none focus:transition-[border-color_0.2s] focus:before:scale-100 focus:before:opacity-[0.12] focus:before:shadow-[0px_0px_0px_13px_rgba(0,0,0,0.6)] focus:before:transition-[box-shadow_0.2s,transform_0.2s] focus:after:absolute focus:after:z-[1] focus:after:block focus:after:h-[0.875rem] focus:after:w-[0.875rem] focus:after:rounded-[0.125rem] focus:after:content-[''] checked:focus:before:scale-100 checked:focus:before:shadow-[0px_0px_0px_13px_#3b71ca] checked:focus:before:transition-[box-shadow_0.2s,transform_0.2s] checked:focus:after:-mt-px checked:focus:after:ml-[0.25rem] checked:focus:after:h-[0.8125rem] checked:focus:after:w-[0.375rem] checked:focus:after:rotate-45 checked:focus:after:rounded-none checked:focus:after:border-[0.125rem] checked:focus:after:border-l-0 checked:focus:after:border-t-0 checked:focus:after:border-solid checked:focus:after:border-white checked:focus:after:bg-transparent dark:border-neutral-600 dark:checked:border-primary dark:checked:bg-primary dark:focus:before:shadow-[0px_0px_0px_13px_rgba(255,255,255,0.4)] dark:checked:focus:before:shadow-[0px_0px_0px_13px_#3b71ca]"
                        type="checkbox" value="" id="exampleCheck2" />
                      <label class="inline-block pl-[0.15rem] hover:cursor-pointer" for="exampleCheck2">
                        Remember me
                      </label>
                    </div>

                    <!--Forgot password link-->
                    <a href="#!">Forgot password?</a>
                  </div>

                  <!-- Login button -->
                  <div class="text-center lg:text-left">
                    <button v-on:click="register" type="button"
                      class="inline-block rounded bg-primary px-7 pb-2.5 pt-3 text-sm font-medium uppercase leading-normal text-white shadow-[0_4px_9px_-4px_#3b71ca] transition duration-150 ease-in-out hover:bg-primary-600 hover:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.3),0_4px_18px_0_rgba(59,113,202,0.2)] focus:bg-primary-600 focus:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.3),0_4px_18px_0_rgba(59,113,202,0.2)] focus:outline-none focus:ring-0 active:bg-primary-700 active:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.3),0_4px_18px_0_rgba(59,113,202,0.2)] dark:shadow-[0_4px_9px_-4px_rgba(59,113,202,0.5)] dark:hover:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.2),0_4px_18px_0_rgba(59,113,202,0.1)] dark:focus:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.2),0_4px_18px_0_rgba(59,113,202,0.1)] dark:active:shadow-[0_8px_9px_-4px_rgba(59,113,202,0.2),0_4px_18px_0_rgba(59,113,202,0.1)]"
                      data-te-ripple-init data-te-ripple-color="light">
                      Register
                    </button>

                    <!-- Register link -->
                    <p class="mb-0 mt-2 pt-1 text-sm font-semibold">
                      Already have an account?
                      <router-link to="/login">
                        <a href="#!"
                          class="text-danger transition duration-150 ease-in-out hover:text-danger-600 focus:text-danger-600 active:text-danger-700">Login</a>
                      </router-link>
                    </p>
                  </div>
                </form>
              </div>
            </div>
          </div>




        </div>

        <!-- Modal footer -->
        <div
          class="mt-auto flex flex-shrink-0 flex-wrap items-center justify-end rounded-b-md border-t-2 border-neutral-100 border-opacity-100 p-4 dark:border-opacity-50 min-[0px]:rounded-none">
          <button ref="closeModal" type="button"
            class="inline-block rounded bg-primary-100 px-6 pb-2 pt-2.5 text-xs font-medium uppercase leading-normal text-primary-700 transition duration-150 ease-in-out hover:bg-primary-accent-100 focus:bg-primary-accent-100 focus:outline-none focus:ring-0 active:bg-primary-accent-200"
            data-te-modal-dismiss>
            Close
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script >
import { onBeforeMount, ref, watch } from 'vue';
import axios from 'axios';
import router from '@/router';

const setup = () => {


  const user = ref({
    email: '',
    password: '',
    dial: '',
    phone: '',
    city: '',
    course: '',
  })

  watch(user.value.dial, (newval, oldval) => {
    console.log(newval)
  })

  const dialCode = ref();
  const cityList = ref();
  const courseList = ref([
    'Bachelor Of Technology (Computer Science)' ,
    'Bachelor Of Technology (Mechanical Engineering)' ,
    'Bachelor Of Technology (Civil Engineering)' ,
    'Bachelor Of Technology (Electronic Engineering)' ,
    'Bachelor Of Technology (Electrical Engineering)' ,
    'Bachelor Of Arts' ,
    'Bachelor Of Commerce' ,
    'Bachelor Of Science' ,
  ]);

  const isLogin = ref(false);
  const loggedInUser = ref(localStorage.getItem('user'));

  const modal = ref(null);
  const closeModal = ref(null);

  const logout = () => {
    console.log('logout comming')
    localStorage.clear();
    router.push('/login');
  }


  onBeforeMount(() => {

    axios.get('https://countriesnow.space/api/v0.1/countries/codes')
      .then((res) => {
        dialCode.value = res.data.data;
        // user.value.dial = dialCode.value[0].dial_code;
      })
      .catch((err) => {
        alert(` Error : ${err.response.data.error.message}`)
        console.log('Error : ', err);
      });

    axios.post('https://countriesnow.space/api/v0.1/countries/cities' , {"country": "india"})
      .then((res) => {
        cityList.value = res.data.data;
        // user.value.city = cityList.value[0];
      })
      .catch((err) => {
        alert(` Error : ${err.response.data.error.message}`)
        console.log('Error : ', err);
      });

  })

  const register = async () => {
    console.log('user data : ', user.value);
    
    user.value.phone = user.value.dial + user.value.phone ;
    delete user.value.dial
    console.log('user data : ', user.value);
    axios.post('http://127.0.0.1:3000/api/auth/register',{...user.value }, {
      headers: {
        'Content-Type': 'application/json'
      }
    })
      .then((res) => {
        localStorage.setItem("user", JSON.stringify(res.data.user));
        localStorage.setItem("token", JSON.stringify(res.data.token));
        alert(`Success : ${res.data.message}`)
        closeModal.value.click();
      })
      .catch((err) => {
        alert(` Error : ${err.response.data.error.message}`)
        console.log('Error : ', err);
      });

  }

  // onBeforeMount(()=>{
  setTimeout(() => {
    modal.value.click();
  }, 1000);


  return {
    modal,
    logout,
    user,
    register,
    closeModal,
    dialCode ,
    cityList ,
    courseList ,
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


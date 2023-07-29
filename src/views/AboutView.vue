<template>
  <div class="flex flex-col min-h-screen bg-black">
    <div class = "rounded-full flex justify-center items-center max-h-full w-10/12 h-16 mx-auto my-10 lg:flex">
    <nav class = "self-center w-5/12 ml-10">
      <ul class = "flex">
        <li class = "mr-8 text-lg text-white cursor-pointer"><router-link to="/projects">Projects</router-link></li>
        <li class = "mr-8 text-lg text-white cursor-pointer"><router-link to="/about">About Me</router-link></li>
        <li class = "mr-8 text-lg text-white cursor-pointer"><router-link to="/contact">Get In Touch</router-link></li>
      </ul>
    </nav>
    <router-link to="/">
      <img src = "/Name-Logo.png" class = "object-contain max-h-16 h-full w-full"/>
    </router-link>
    <div class = "flex justify-end w-5/12 h-16 mr-10">
      <a href = "https://www.linkedin.com/in/joshuajerin/" target = "_blank" class = "my-auto cursor-pointer ml-7">
        <i class = "text-2xl text-white fa-brands fa-linkedin"></i>
      </a>
      <a href = "https://www.github.com/joshuajerin" target = "_blank" class = "my-auto cursor-pointer ml-7">
        <i class = "text-2xl text-white fa-brands fa-github"></i>
      </a>
    </div>
    <router-view/>
  </div>

    <div class="flex-grow flex items-center justify-center flex-col bg-black">
      <!-- Form and other content -->
      <header class="w-10/12 text-center">
        <h1 class="main-heading text-[100px] text-white font-normal leading-tight font-[JustAnotherHand] ">
          PAGE AVAILABLE SOON!
        </h1>
      </header>

    </div>
    
      <div class=" flex flex-col gap-3 w-full items-center h-[100px] px-[530px] py-2 mt-[50px]">
          <div class="text-white flex flex-col gap-3 w-full items-center">
        <div class="text-3xl font-['Kaisei_Opti'] w-48 h-[46.25%]">
          Joshua Jerin
        </div>
        <div class="font-['Kaisei_Opti'] self-center w-48">
          Cincinnati, OH, USA
        </div>
      </div>
        </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>
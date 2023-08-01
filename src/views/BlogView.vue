<template>
  <div class="flex flex-col min-h-screen items-center bg-black">
    <div class="fixed rounded-full flex justify-between items-center max-h-full w-full md:w-6/12 h-12 mx-auto my-10 lg:flex bg-black">
      <nav class="w-3/12 ml-10 mr-10">
        <ul class="flex justify-end">
          <li class="mr-8 text-[15px] text-white cursor-pointer">
            <router-link to="/contact">Contact</router-link>
          </li>
          <li class="text-[15px] text-white cursor-pointer">
            <router-link to="/about">Profile</router-link>
          </li>
        </ul>
      </nav>
      <router-link to="/" class = " text-[20px] text-white">
        JOSHUA_JERIN
      </router-link>
      <nav class="w-3/12 ml-10">
        <ul class="flex justify-start">
          <li class="mr-8 text-[15px] text-white cursor-pointer">
            <router-link to="/projects">Projects</router-link>
          </li>
          <li class="text-[15px] text-white cursor-pointer">
            <router-link to="/blog">Blog</router-link>
          </li>
        </ul>
      </nav>
      <div class="flex justify-end w-3/12 h-16 ml-10 mr-10">
        <a
          href="https://www.linkedin.com/in/joshuajerin/"
          target="_blank"
          class="my-auto cursor-pointer"
        >
          <i class="text-2xl text-white fa-brands fa-linkedin"></i>
        </a>
        <a
          href="https://www.github.com/joshuajerin"
          target="_blank"
          class="my-auto cursor-pointer ml-7"
        >
          <i class="text-2xl text-white fa-brands fa-github"></i>
        </a>
        <a
          href="https://twitter.com/JoshuaJerin1"
          target="_blank"
          class="my-auto cursor-pointer ml-7"
        >
          <i class="text-2xl text-white fa-brands fa-twitter"></i>
          </a>
      </div>
    </div>
    <router-view />

    <div class="flex-grow flex items-center justify-center flex-col bg-black text-white text-[100px] mt-[80px] ">
      <p> COMING SOON!!</p>
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
//justify-between relative overflow-hidden

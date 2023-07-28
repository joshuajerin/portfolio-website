<template>
  <div class = " rounded-full flex justify-center items-center max-h-full w-10/12 h-16 mx-auto my-10  lg:flex bg-black">
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
      <a href = "" target = "_blank" class = "my-auto cursor-pointer ml-7">
        <i class = "text-2xl text-white fa-brands fa-instagram"></i>
      </a>
      <a href = "" target = "_blank" class = "my-auto cursor-pointer ml-7">
        <i class = "text-2xl text-white fa-brands fa-facebook"></i>
      </a>
      <a href = "" target = "_blank" class = "my-auto cursor-pointer ml-7">
        <i class = "text-2xl text-white fa-brands fa-linkedin"></i>
      </a>
      <a href = "" target = "_blank" class = "my-auto cursor-pointer ml-7">
        <i class = "text-2xl text-white fa-brands fa-twitter"></i>
      </a>
    </div>
    <router-view/>
  </div>


</template>

<script>
export default {
  name: "App",
};
</script>
//justify-between relative overflow-hidden
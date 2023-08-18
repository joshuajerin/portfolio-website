<template>
  <div class="home-page relative h-screen">
    <div v-if="loading" class="loading-screen">
      <!-- ... (loading screen content) ... -->
    </div>

    <div v-else>
      <video class="fixed inset-0 w-full h-full object-cover" autoplay muted loop id="myVideo">
        <source :src="require('/ColourExplodingVideo.mp4')" type="video/mp4">
        Your browser does not support the video tag.
      </video>

      <div class="content absolute inset-0 bg-none bg-opacity-50 text-white flex flex-col lg:flex-row items-start justify-between">
        <!-- Main content section -->
        <header class="w-full md:w-1/2 text-left pl-8 lg:pl-12 pt-8 lg:pt-20"> 
          <h1 class="main-heading text-white text-[50px] lg:text-[100px] font-normal leading-tight font-[JustAnotherHand]">
            Making Things <br>Sing since '04
          </h1>
          <p class="sub-heading text-[#EAEAEA] text-[20px] lg:text-[30px] font-normal leading-snug font-[RobotoSlab] mt-8 md:mt-14 text-left">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus lacinia odio vitae vestibulum. Donec in efficitur ipsum. Morbi malesuada quis erat at blandit. Sed placerat vehicula leo. Quisque at feugiat dui. Quisque at feugiat dui. Quisque at feugiat dui. Quisque at feugiat dui.
          </p>
        </header>

        <!-- Navigation links section -->
        <nav class="w-full lg:w-1/2 pr-8 lg:pr-12 flex flex-col justify-center items-center space-y-6 lg:space-y-10 mt-8 lg:mt-[100px]">
          <router-link class="text-[35px] md:text-[35px]" to="/projects">Projects</router-link>
          <router-link class="text-[35px] md:text-[35px]" to="/about">About Me</router-link>
          <router-link class="text-[35px] md:text-[35px]" to="/contact">Get In Touch</router-link>
          <router-link class="text-[35px] md:text-[35px]" to="/blog">Blog</router-link> <!-- added margin-bottom here -->

          <!-- Twitter links -->
          <div class=""></div>
            <div class="flex space-x-4 ">
              <a href="https://twitter.com/JoshuaJerin1" target="_blank">
                <i class="text-[50px] text-white fa-brands fa-twitter"></i>
              </a>
              <a href="https://twitter.com/JoshuaJerin1" target="_blank">
                <i class="ml-[30px] text-[50px] text-white fa-brands fa-github"></i>
              </a>
            </div>
            <div class="flex space-x-4 mt-[25px]">
              <a href="https://twitter.com/JoshuaJerin1" target="_blank">
                <i class="text-[50px] text-white fa-brands fa-linkedin mb-10"></i>
              </a>
              
          </div>
        </nav>
        
      </div>
    </div>
  </div>
</template>


<script>
// @ is an alias to /src
export default {
  name: 'HomeView',
  data() {
    return {
      //loading: true
    }
  }
  /* mounted() {
    setTimeout(() => {
      this.loading = false;
    }, 3000); // 5000 ms = 5 seconds
  } */
}
</script>

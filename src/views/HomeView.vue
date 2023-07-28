<template>
  <div class="home-page relative h-screen">
    <video class="fixed inset-0 w-full h-full object-cover" autoplay muted loop id="myVideo">
      <source :src="require('/ColourExplodingVideo.mp4')" type="video/mp4">
      Your browser does not support the video tag.
    </video>

    <div class="content absolute inset-0 bg-black bg-opacity-50 text-white flex items-center justify-center">
      <header class="w-10/12 text-center">
        <h1 class="main-heading text-white text-[100px] font-normal leading-tight font-[JustAnotherHand] ">
          Making Things <br>Sing since '07
        </h1>
        <p class="sub-heading text-[#EAEAEA] text-[40px] font-normal leading-snug font-[RobotoSlab] mt-14">
          Hello👋 I’m Joshua, a Software Developer. I love creating objects that I'm most passionate about💻🤖
        </p>
        <li class="mr-8 text-lg text-white cursor-pointer"><router-link to="/about">Portfolio</router-link></li>
      </header>
    </div>
    
  </div>
</template>


<script>
// @ is an alias to /src
export default {
  name: 'HomeView',
  components: {
    // List your components here
  }
}
</script>

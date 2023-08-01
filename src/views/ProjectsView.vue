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

    <div class="flex-grow flex items-center justify-center flex-col bg-black text-white mt-[80px] ">
      <div class="mb-[100px] mt-[50px] mr-[580px]">
        <div class="text-4xl font-['Kaisei_Opti'] font-medium w-[306px] h-[2.12%] mb-4">
          Main Heading
        </div>
        <div class="text-2xl font-['Kaisei_Opti'] w-[493px] h-[6.89%] mb-4">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Lorem ipsum dolor sit
          amet,
          <br />
          (subtext)
        </div>
      </div>
      <div class="grid grid-cols-2 gap-4 mb-1 ml-24 mr-20">
        <!-- Project 1 details -->
        <div class="overflow-hidden bg-[#c8c8c8] flex flex-col pb-4 gap-2 w-full items-start">
          <router-link to="/">
            <img
              src="https://file.rendit.io/n/v6v6igjTlf0uhuuDHz6j.png"
              class="min-h-0 min-w-0 self-center object-cover"
              style="height: 300px; width: 540px;"
            />
            <div class="text-2xl font-['Kaisei_Opti'] ml-4 w-24 h-[8.71%]">
              Master.AI
            </div>
            <div class="text-xs font-['Kaisei_Opti'] ml-4 w-2/5 h-[3.65%]">
              Branding, Strategy, Art Direction, Illustration
            </div>
          </router-link>
        </div>
        <!-- End of project 1 details -->

        <!-- Project 2 details -->
        <div class="overflow-hidden bg-[#c8c8c8] flex flex-col pb-4 gap-2 w-full items-start">
          <router-link to="/">
            <img
              src="https://file.rendit.io/n/v6v6igjTlf0uhuuDHz6j.png"
              class="min-h-0 min-w-0 self-center object-cover"
              style="height: 300px; width: 540px;"
            />
            <div class="text-2xl font-['Kaisei_Opti'] ml-4 w-24 h-[8.71%]">
              Project 2
            </div>
            <div class="text-xs font-['Kaisei_Opti'] ml-4 w-2/5 h-[3.65%]">
              Branding, Strategy, Art Direction, Illustration
            </div>
          </router-link>
        </div>
        <!-- End of project 2 details -->

        <!-- Project 3 details -->
        <div class="overflow-hidden bg-[#c8c8c8] flex flex-col pb-4 gap-2 w-full items-start">
          <router-link to="/">
            <img
              src="https://file.rendit.io/n/v6v6igjTlf0uhuuDHz6j.png"
              class="min-h-0 min-w-0 self-center object-cover"
              style="height: 300px; width: 540px;"
            />
            <div class="text-2xl font-['Kaisei_Opti'] ml-4 w-24 h-[8.71%]">
              Project 3
            </div>
            <div class="text-xs font-['Kaisei_Opti'] ml-4 w-2/5 h-[3.65%]">
              Branding, Strategy, Art Direction, Illustration
            </div>
          </router-link>
        </div>
        <!-- End of project 3 details -->

        <!-- Project 4 details -->
        <div class="overflow-hidden bg-[#c8c8c8] flex flex-col pb-4 gap-2 w-full items-start">
          <router-link to="/">
            <img
              src="https://file.rendit.io/n/v6v6igjTlf0uhuuDHz6j.png"
              class="min-h-0 min-w-0 self-center object-cover"
              style="height: 300px; width: 540px;"
            />
            <div class="text-2xl font-['Kaisei_Opti'] ml-4 w-24 h-[8.71%]">
              Project 4
            </div>
            <div class="text-xs font-['Kaisei_Opti'] ml-4 w-2/5 h-[3.65%]">
              Branding, Strategy, Art Direction, Illustration
            </div>
          </router-link>
        </div>
        <!-- End of project 4 details -->
      </div>
    </div>

    <div class="flex flex-col gap-3 w-full items-center h-[100px] px-[530px] py-2 mt-[50px]">
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

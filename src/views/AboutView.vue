<template>
  <div class="flex flex-col min-h-screen items-center bg-black">

    <div class="fixed rounded-full flex flex-col lg:flex-row w-9/12 xl:w-4/12 h-12 mx-auto my-10 bg-black">

      <div class="lg:hidden flex justify-between items-center w-full">
            <button @click="menuOpen = !menuOpen" class="px-3 py-1 text-white">
                ☰
            </button>

            <!-- Centered Text -->
            <router-link to="/" class="text-[30px] text-white mx-auto">
                JJ
            </router-link>

            <!-- Empty div to balance out the menu button -->
            <div class="px-3 py-1 opacity-0">
                ☰
            </div>

            <div v-if="menuOpen" class="absolute top-full left-10 transform -translate-x-1/2 mt-2 w-48 bg-black text-white rounded-lg shadow-md z-10 flex flex-col items-center">
                <router-link to="/projects" class="block w-full text-center px-4 py-2">Projects</router-link>
                <router-link to="/about" class="block w-full text-center px-4 py-2">Profile</router-link>
                <router-link to="/blog" class="block w-full text-center px-4 py-2">Blogs</router-link>
                <router-link to="/contact" class="block w-full text-center px-4 py-2">Contact</router-link>
            </div>
        </div>
      
        <!-- Left Navigation for Larger Screens -->
        <nav class="hidden lg:flex flex-grow justify-center items-center ml-5 mr-5">
          <ul class="flex">
                <li class="mr-8 text-[15px] text-white cursor-pointer">
                    <router-link to="/projects">Projects</router-link>
                </li>
                <li class="text-[15px] text-white cursor-pointer">
                    <router-link to="/about">Profile</router-link>
                </li>
            </ul>
        </nav>

        <!-- Centered Text -->
        <router-link to="/" class="hidden lg:block text-[30px] text-white self-center lg:mr-[30px]">
            JJ
        </router-link>

        <!-- Right Navigation for Larger Screens -->
        <nav class="hidden lg:flex flex-grow justify-center items-center mr-5">
          <ul class="flex">
                <li class="text-[15px] text-white cursor-pointer mr-8">
                    <router-link to="/blog">Blog</router-link>
                </li>
                <li class="text-[15px] text-white cursor-pointer">
                    <router-link to="/contact">Contact</router-link>
                </li>
            </ul>
        </nav>

        </div>
    <router-view />
    <div class="flex-grow flex items-center  justify-center flex-col text-white mt-[80px]">
      <!-- Centered Text -->
      <div class="text-center mt-20 mb-8 lg:self-start lg:text-start lg:ml-4">
        <div class="text-4xl font-['Kaisei_Opti'] ">
          Introducing.
        </div>
        <div class="text-6xl font-['Kaisei_Opti'] leading-[60px]">
          young.
          <br />
          enthusiastic.
        </div>
      </div>

      <!-- Images in Grid Layout -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:ml-[200px] gap-8 mb-8 lg:w-[822px] px-4">
        <div class="bg-[#d9d9d9] w-full lg:w-[388px] h-[352px] overflow-hidden">
          <img src="/IMG-9551.png" class="object-cover w-full h-full" />
        </div>
        <div class="bg-[#d9d9d9] w-full lg:w-[388px] h-[352px] overflow-hidden">
          <img src="/IMG_3456.jpeg" class="object-cover w-full h-full" />
        </div>
      </div>

      <!-- Text Description -->
      <div class="flex flex-row justify-center lg:justify-end w-full items-center mb-16 lg:ml-8">
        <div class="flex flex-col w-10/12 lg:w-[822px] lg:mr-24">
          <div class="text-2xl font-['Kaisei_Opti'] leading-[30px] h-[50%]">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas
            condimentum, mi sed posuere sollicitudin, lorem orci feugiat justo, eget
            venenatis tortor tortor sed est. Phasellus a aliquam lacus. Morbi id
            cursus dolor, et condimentum risus. Sed imperdiet ligula ac justo
            feugiat, eu tristique orci consectetur.
          </div><br>
          <div class="text-2xl font-['Kaisei_Opti'] leading-[30px] h-[50%]">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas
            condimentum, mi sed posuere sollicitudin, lorem orci feugiat justo, eget
            venenatis tortor tortor sed est. Phasellus a aliquam lacus. Morbi id
            cursus dolor, et condimentum risus. Sed imperdiet ligula ac justo
            feugiat, eu tristique orci consectetur.
          </div>
        </div>
      </div>

      <div class="flex-grow flex items-center  justify-center flex-col text-white ">
      <!-- Centered Text -->
      <div class="text-center  mb-8 lg:self-start lg:text-start lg:ml-4">
        <div class="text-4xl font-['Kaisei_Opti'] ">
          Introducing.
        </div>
        <div class="text-6xl font-['Kaisei_Opti'] leading-[60px]">
          young.
          <br />
          enthusiastic.
        </div>
      </div>

      <!-- Images in Grid Layout -->
      <div class="grid grid-cols-1 md:grid-cols-2 lg:ml-[200px] gap-8 mb-8 lg:w-[822px] px-4">
        <div class="bg-[#d9d9d9] w-full lg:w-[388px] h-[352px] overflow-hidden">
          <img src="/IMG-9551.png" class="object-cover w-full h-full" />
        </div>
        <div class="bg-[#d9d9d9] w-full lg:w-[388px] h-[352px] overflow-hidden">
          <img src="/IMG_3456.jpeg" class="object-cover w-full h-full" />
        </div>
      </div>

      <div class="flex flex-row justify-center lg:justify-end w-full items-center mb-10 lg:ml-8">
        <div class="flex flex-col w-10/12 lg:w-[822px] lg:mr-24">
          <div class="text-2xl font-['Kaisei_Opti'] leading-[30px] h-[50%]">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas
            condimentum, mi sed posuere sollicitudin, lorem orci feugiat justo, eget
            venenatis tortor tortor sed est. Phasellus a aliquam lacus. Morbi id
            cursus dolor, et condimentum risus. Sed imperdiet ligula ac justo
            feugiat, eu tristique orci consectetur.
          </div><br>
          <div class="text-2xl font-['Kaisei_Opti'] leading-[30px] h-[50%]">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas
            condimentum, mi sed posuere sollicitudin, lorem orci feugiat justo, eget
            venenatis tortor tortor sed est. Phasellus a aliquam lacus. Morbi id
            cursus dolor, et condimentum risus. Sed imperdiet ligula ac justo
            feugiat, eu tristique orci consectetur.
          </div>
        </div>
      </div>
      
      
      <div class="flex lg:self-end w-10/12 lg:w-[802px] flex-row gap-24 lg:items-start mb-12 lg:mx-24 lg:ml-[300px]">
        <div class="bg-[#d9d9d9] mb-2 w-full  lg:w-[802px]  lg:h-[352px] overflow-hidden"><img src="/IMG_9552.png" class=" w-full"/></div>
      </div>
      <div class="flex lg:self-end w-10/12 lg:w-[802px] flex-row gap-24 items-start mx-24 lg:ml-[300px]">
        <div class="bg-[#d9d9d9] mb-2 w-full lg:w-[802px] lg:h-[352px] overflow-hidden"><img src="/IMG_9621.JPG" class=" w-full"/></div>
      </div></div>
      
      
      <div class="flex space-x-10 mb-[30px] justify-center hidden lg:display-block">
      <div class=" flex justify-center items-center overflow-hidden text-center bg-[#d9d9d9] border-gray-300 w-[390px]"> 
      </div>
      <div class="flex justify-center items-center overflow-hidden text-center bg-[#d9d9d9] border-gray-300 w-[390px] ">
      </div>
      <div class="flex justify-center items-center overflow-hidden text-center bg-[#d9d9d9] border-gray-300 w-[390px]">
      </div>
     </div>
      </div> 
      <!-- Footer-->
    <div class="relative flex flex-col gap-3 w-full bg-black items-center h-[90px] mt-10 py-2 ">
    <!-- Social Media Links (Positioned to the absolute left) -->
    <div class="absolute left-10 flex space-x-4 mt-5 hidden lg:block">
        <a href="https://twitter.com/JoshuaJerin1" target="_blank">
            <i class="text-[30px] text-white fa-brands fa-twitter"></i>
        </a>
        <a href="https://twitter.com/JoshuaJerin1" target="_blank">
            <i class="text-[30px] text-white fa-brands fa-linkedin"></i>
        </a>
        <a href="https://twitter.com/JoshuaJerin1" target="_blank">
            <i class="text-[30px] text-white fa-brands fa-instagram"></i>
        </a>
    </div>

    <!-- Footer Content (Centered) -->
    <div class="text-white flex flex-col gap-3 items-center z-10 ml-10">
        <div class="text-3xl text-white font-['Kaisei_Opti'] w-48 h-[46.25%]">
            Joshua Jerin
        </div>
        <div class="font-['Kaisei_Opti'] text-white self-center w-48">
              Cincinnati, OH, USA
        </div>
    </div>

    <!-- Footer Content (Right)-->
    <div class = "absolute right-0 flex flex-col space-x-4 gap-2 item-center mt-2 hidden lg:block">
        <div class="font-['Kaisei_Opti'] text-white self-center w-48">
              jerinja@mail.uc.edu
        </div>
        <div class="font-['Kaisei_Opti'] text-white self-center w-48">
              +1 (513)957-5755
        </div>
    </div>
</div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      menuOpen: false
    };
  },
};

</script>
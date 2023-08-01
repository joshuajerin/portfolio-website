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
    <div class="flex-grow flex items-center justify-center flex-col text-white mt-[80px]">
      <div class="text-4xl font-['Kaisei_Opti'] self-start w-[267px] h-[0.5%] mt-20 ml-24">
        Introducing.
      </div>
      <div class="text-6xl font-['Kaisei_Opti'] leading-[60px] self-start w-[423px] h-[3.05%] mb-8 ml-24">
        young.
        <br />
        enthusiastic.
      </div>
      <div class="self-end flex flex-row gap-16 w-[822px] items-center mb-12 mr-24">
        <div class="bg-[#d9d9d9] w-[388px] h-[352px] overflow-hidden"><img src="/IMG-9551.png" class=" "/></div>
        <div class="bg-[#d9d9d9] w-[388px] h-[352px] overflow-hidden"><img src="/IMG_3456.jpeg" class=""/></div>
      </div>
      <div class="flex self-end flex-row gap-24 items-start mb-12 mx-24">
        <div class="bg-[#d9d9d9] mb-2 w-[822px] h-[352px] overflow-hidden"><img src="/IMG_9906.JPG" class=" w-full"/></div>
      </div>
      <div class="flex flex-row justify-end w-full items-center mb-16">
        <div class="flex flex-col w-[822px] mr-24">
          <div class="text-2xl font-['Kaisei_Opti'] leading-[30px] h-[50%]">
            Hi!!! I'm a sophomore at the University of Cincinnati and I'm currently
            pursuing my Bachelor of Science in Computer Science. One of the main goals
            of mine is to help people get the vast resources that has huge potential
            that's available out there
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
      <div class="text-4xl font-['Kaisei_Opti'] self-start w-[267px] h-[0.5%] ml-24">
        Introducing.
      </div>
      <div class="text-6xl font-['Kaisei_Opti'] leading-[60px] self-start w-[423px] h-[3.05%] mb-8 ml-24">
        young.
        <br />
        enthusiastic.
      </div>
      <div class="self-end flex flex-row gap-16 w-[822px] items-center mb-12 mr-24">
        <div class="bg-[#d9d9d9] w-[388px] h-[352px]"><img src="/IMG_7812.png" class=""/></div>
        <div class="bg-[#d9d9d9] w-[388px] h-[352px]"><img src="/IMG_9715.png" class=""/></div>
      </div>
      <div class="flex self-end flex-row gap-24 items-start mb-12 mx-24">
        <div class="bg-[#d9d9d9] mb-2 w-[822px] h-[352px] overflow-hidden"><img src="/IMG_9552.png" class=" w-full"/></div>
      </div>
      <div class="flex self-end flex-row gap-24 items-start mb-12 mx-24">
        <div class="bg-[#d9d9d9] mb-2 w-[822px] h-[352px] overflow-hidden"><img src="/IMG_9621.JPG" class=" w-full"/></div>
      </div>
      <div class="flex flex-row justify-end w-full items-center mb-16">
        <div class="flex flex-col w-[822px] mr-24">
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
      <div class="flex space-x-10 mb-[30px] justify-center">
      <div class="flex justify-center items-center overflow-hidden text-center bg-[#d9d9d9] border-gray-300 w-[390px] h-[500px]"> 
      <img src="/IMG_9090.JPG" class=" h-12 h-full w-full"/></div>
      <div class="flex justify-center items-center overflow-hidden text-center bg-[#d9d9d9] border-gray-300 w-[390px] h-[500px]">
      <img src="/IMG_8796.jpg" class=" w-full"/></div>
      <div class="flex justify-center items-center overflow-hidden text-center bg-[#d9d9d9] border-gray-300 w-[390px] h-[500px]">
      <img src="/IMG_9780.jpg" class=" w-full "/></div>
    </div></div>
      <div class=" flex flex-col gap-3 w-full items-center h-[100px] px-[530px] py-2 mt-[30px]">
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
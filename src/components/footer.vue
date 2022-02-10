<template>
  <footer class="px-8 divide-y bg-coolGray-200 text-coolGray-800">
    <div
      class="container flex flex-col justify-between py-10 mx-auto space-y-8 lg:flex-row lg:space-y-0"
    >
      <div class="lg:w-1/3 ">
          <div
            class="flex items-center justify-center w-12 space-y-5 h-12 rounded-full bg-violet-600"
          >
            <img class="block h-6 w-auto" :src="logo" alt="Workflow" />
          </div>
     
        
             <P
            >Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quae,
            corrupti cum? Optio dolorem quasi sed placeat asperiores dolores ut
            veniam, consectetur atque iste nam sit numquam consequatur accusamus
            nisi a?</P
          >
        <p class="py-6 text-sm text-coolGray-600">
          ©2020PADDLE
        </p> 
      </div>
      <div
        class="grid grid-cols-2 text-sm gap-x-1 gap-y-8  lg:w-1/2 sm:grid-cols-3"
      >
        <div class="space-y-5 ">
          <h3 class="tracking-wide uppercase text-coolGray-900">Product</h3>
          <ul class="space-y-1">
            <li>
              <a href="#">Praesent</a>
            </li>
            <li>
              <a href="#">Laoreet</a>
            </li>
            <li>
              <a href="#">Laoreet</a>
            </li>
            <li>
              <a href="#">Server</a>
            </li>
          </ul>
        </div>
        <div class="space-y-5">
          <h3 class="tracking-wide uppercase text-coolGray-900">Engage</h3>
          <ul class="space-y-1">
            <li>
              <a href="#">Privacy</a>
            </li>
            <li>
              <a href="#">Mauris</a>
            </li>
            <li>
              <a href="#">Aenean</a>
            </li>
            <li>
              <a href="#">Linsean</a>
            </li>
            <li>
              <a href="#">Linsean</a>
            </li>
          </ul>
        </div>
       
        <div class="space-y-5">
          <h3 class="tracking-wide uppercase text-coolGray-900">Earn money</h3>
          <ul class="space-y-1">
            <li>
              <a href="#">Ultrices</a>
            </li>
            <li>
              <a href="#">Fusce</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>


export default {
  data() {
    return {
      logo: require("../assets/PEDDLE.png"),
    };
  },
  
};
</script>

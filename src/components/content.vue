<template>
  <div>
    <div class="grid lg:gap-8 lg:grid-cols-2 mt-12 py-5">
      <div class="text-left px-8 md:w-1/2 lg:w-full">
        <h1
          class="font-medium text-6xl tracking-tight leading-tight sm:text-3xl text-black hero mt-8"
        >
          We are Everything We Aspire To BE
        </h1>

        <p class="color mb-6 mt-10 text-justify text-base lg:w-3/4 text-black">
          Lorem ipsum, dolor sit amet consectetur adipisicing elit. Iste optio
          voluptatum ratione facilis, quo eligendi delectus totam numquam vitae
          libero quod corporis est, dolorum error atque asperiores. Fuga,
          consequuntur necessitatibus.
        </p>
        <button
          class="border py-3 px-10 button text-pink-100 rounded font-bold"
        >
          Get Started
        </button>
      </div>
      <div aria-hidden="true">
        <div class="lg:w-full sm:w-1/2">
          <img :src="happyman" alt="happy man" />
        </div>
      </div>
    </div>

    <div
      class="shadow-2xl flex justify-evenly lg:w-1/2 w-full mx-auto mt-10 rounded py-4 mb-20"
    >
      <button
        class="inline-flex items-center px-6 sm:px-8 py-3 rounded-lg bg-violet-600 text-coolGray-50"
      >
        <img src="../assets/Icon/user.png" alt="icon" />
        <span class="flex flex-col items-start ml-4 leading-none">
          <span class="mb-1 text-xs">90+</span>
          <span class="font-semibold title-font">Users</span>
        </span>
      </button>
      <button
        class="inline-flex items-center px-6 py-3 rounded-lg bg-violet-600 text-coolGray-50"
      >
        <img src="../assets/Icon/location.png" alt="icon" />
        <span class="flex flex-col items-start ml-4 leading-none">
          <span class="mb-1 text-xs">30+</span>
          <span class="font-semibold title-font">Locations</span>
        </span>
      </button>
      <button
        class="inline-flex items-center px-6 py-3 rounded-lg bg-violet-600 text-coolGray-50"
      >
        <img src="../assets/Icon/Server.png" alt="icon" />
        <span class="flex flex-col items-start ml-4 leading-none">
          <span class="mb-1 text-xs">50+</span>
          <span class="font-semibold title-font">Servers</span>
        </span>
      </button>
    </div>

    <!-- features we provide -->

    <section class="bg-coolGray-100 text-coolGray-800">
      <div
        class="container max-w-xl p-6 py-12 mx-auto space-y-24 lg:px-8 lg:max-w-7xl"
      >
        <div>
          <div class="grid lg:gap-24 lg:grid-cols-2 lg:items-center">
            <div class="lg:col-start-2">
              <h3
                class="text-2xl font-bold tracking-tight sm:text-3xl text-coolGray-900"
              >
                Features We Provide For You
              </h3>
              <p class="mt-3 text-lg text-coolGray-600">
                Per odio fabellas consulatu cu. Utroque detracto mel ea, quo te
                latine theophrastus. Ea his tale nibh dissentias, mei exerci
                tamquam euripidis cu.
              </p>
              <div class="mt-12 space-y-12">
                <div class="flex">
                  <div class="flex-shrink-0">
                    <div
                      class="flex items-center justify-center w-12 h-6 rounded-md bg-violet-600 text-coolGray-50"
                    >
                      <img src="../assets/Rectangle.png" alt="smallbox" />
                    </div>
                  </div>
                  <div class="ml-4">
                    <h4 class="text-lg font-medium leading-6 text-coolGray-900">
                      At eum ferri luptatum lobortis
                    </h4>
                  </div>
                </div>
                <div class="flex">
                  <div class="flex-shrink-0">
                    <div
                      class="flex items-center justify-center w-12 h-6 rounded-md bg-violet-600 text-coolGray-50"
                    >
                      <img src="../assets/Rectangle.png" alt="smallbox" />
                    </div>
                  </div>
                  <div class="ml-4">
                    <h4 class="text-lg font-medium leading-6 text-coolGray-900">
                      At eum ferri luptatum lobortis
                    </h4>
                  </div>
                </div>
                <div class="flex">
                  <div class="flex-shrink-0">
                    <div
                      class="flex items-center justify-center w-12 h-6 rounded-md bg-violet-600 text-coolGray-50"
                    >
                      <img src="../assets/Rectangle.png" alt="smallbox" />
                    </div>
                  </div>
                  <div class="ml-4">
                    <h4 class="text-lg font-medium leading-6 text-coolGray-900">
                      Dicunt verterem evertitur eu sea
                    </h4>
                  </div>
                </div>
                <div class="flex">
                  <div class="flex-shrink-0">
                    <div
                      class="flex items-center justify-center w-12 h-6 rounded-md bg-violet-600 text-coolGray-50"
                    >
                      <img src="../assets/Rectangle.png" alt="smallbox" />
                    </div>
                  </div>
                  <div class="ml-4">
                    <h4 class="text-lg font-medium leading-6 text-coolGray-900">
                      Dicunt verterem evertitur eu sea
                    </h4>
                  </div>
                </div>
              </div>
            </div>
            <div class="mt-10 lg:mt-0 lg:col-start-1 lg:row-start-1">
              <img
                src="../assets/piano.png"
                alt="piano"
                class="mx-auto rounded-lg shadow-lg bg-coolGray-500"
              />
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- pricings -->

    <section class="py-6 bg-coolGray-100">
      <div class="container p-4 mx-auto sm:p-10">
        <div class="mb-12 space-y-4 text-center">
          <h1 class="pricing-text text-4xl font-medium leading-tight">
            Choose Your Plan
          </h1>
          <p class="px-4 color sm:px-8 lg:px-24 font-normal">
            Lets choose the package that is best for you and explore it happily
            and
            <span class="block">cheerfully</span>
          </p>
        </div>
        <div
          class="grid max-w-md grid-cols-1 gap-6 mx-auto auto-rows-fr lg:grid-cols-3 lg:max-w-full"
        >
          <div
            class="flex flex-col overflow-hidden border-2 rounded-md border-coolGray-300"
          >
            <div
              class="flex flex-col items-center justify-center px-2 py-8 space-y-4 bg-coolGray-100"
            >
              <img src="../assets/pricing1.png" alt="pricing" />
              <p class="text-lg font-medium pricing-text">Free Plan</p>
            </div>
            <div
              class="flex flex-col items-center justify-center px-2 py-8 bg-coolGray-50"
            >
              <ul class=" flex-1 space-y-8">
                <li class="flex flex-shrink-0 justify-center space-x-4">
                   <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>
                <li class="flex justify-center space-x-4">
                   <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>
                <li class="flex justify-center space-x-4">
                  <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>
                <li class="flex justify-center space-x-3">
                  <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>
              </ul>

              <p class="text-xl font-bold mt-48">Free</p>
              <button
                type="button"
                class="items-center px-8 py-3 text-sm font-semibold rounded text-white button shadow-sm focus:outline-none mt-4"
              >
                <span>Select</span>
              </button>
            </div>
          </div>
          <div
            class="flex flex-col overflow-hidden border-2 rounded-md border-violet-600"
          >
            <div
              class="flex flex-col items-center justify-center px-2 py-8 space-y-4 bg-coolGray-100"
            >
              <img src="../assets/pricing2.png" alt="pricing" />
              <p class="text-lg font-medium pricing-text">Standard Plan</p>
            </div>
            <div
              class="flex flex-col items-center justify-center px-2 py-8 bg-coolGray-50"
            >
              <ul class="self-stretch flex-1 space-y-8">
                <li class="flex justify-center space-x-6">
                   <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>
                <li class="flex justify-center space-x-6">
                   <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>
                <li class="flex justify-center space-x-6">
                   <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>
                <li class="flex justify-center space-x-6">
                   <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>
                <li class="flex justify-center space-x-6">
                   <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>
              </ul>
              <p class="text-3xl font-normal mt-36">
                8€
                <span class="text-sm text-coolGray-600 font-medium"> /mo</span>
              </p>
              <button
                type="button"
                class="items-center px-8 py-3 text-sm font-semibold rounded text-white button mt-4"
              >
                <span>Select</span>
              </button>
            </div>
          </div>
          <div
            class="flex flex-col overflow-hidden border-2 rounded-md border-coolGray-300"
          >
            <div
              class="flex flex-col items-center justify-center px-2 py-8 space-y-4 bg-coolGray-100"
            >
              <img src="../assets/pricing3.png" alt="pricing" />
              <p class="text-lg font-medium pricing-text">Premium Plan</p>
            </div>
            <div
              class="flex flex-col items-center justify-center px-2 py-5 bg-coolGray-50"
            >
              <ul class="self-stretch flex-1 space-y-8">
                <li class="flex justify-center space-x-6">
                   <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>

                <li class="flex justify-center space-x-6">
                   <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>
                <li class="flex justify-center space-x-6">
                   <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>
                <li class="flex justify-center space-x-6">
                   <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>
                <li class="flex justify-center space-x-6">
                   <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>
                <li class="flex justify-center space-x-6">
                   <img src="../assets/Vector.png" alt="" class="h-2 w-3 mt-2" />
                  <span>Lumet consectetur adipisicing</span>
                </li>
              </ul>
              <p class="text-3xl font-normal mt-20">
                $12
                <span class="text-sm text-coolGray-600 font-medium"> /mo</span>
              </p>
              <button
                type="button"
                class="items-center px-8 py-3 text-sm font-semibold rounded text-white button mt-4"
              >
                <span>Select</span>
              </button>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- get started -->
    <section class="bg-coolGray-100 text-coolGray-800">
      <div
        class="container mx-auto flex flex-col items-center px-4 py-16 text-center md:py-32 md:px-10 lg:px-32 xl:max-w-3xl"
      >
        <h1
          class="text-4xl font-bold leading-tight lg:leading-snug sm:text-5xl"
        >
          Get Started With
          <span>Paddle Today</span>
        </h1>
        <p class="px-4 mt-8 mb-4 text-base">
          Cupiditate minima voluptate temporibus quia? Architecto beatae esse ab
          amet vero eaque explicabo!
        </p>
        <div class="flex flex-wrap justify-center">
          <button
            class="px-12 py-3 m-2 text-lg button font-semibold rounded text-white"
          >
            Start Today
          </button>
        </div>
      </div>
    </section>

    <div
      class="grid max-w-md grid-cols-2 px-8 gap-10 mx-auto auto-rows-fr lg:grid-cols-5 lg:max-w-full lg:px-0"
    >
      <div>
        <img src="../assets/netflix.png" alt="netflix" />
      </div>
      <div>
        <img src="../assets/reddit.png" alt="netflix" />
      </div>
      <div>
        <img src="../assets/Amazon.png" alt="netflix" />
      </div>
      <div>
        <img src="../assets/Discord.png" alt="netflix" />
      </div>
      <div>
        <img src="../assets/spotify.png" alt="netflix" />
      </div>
    </div>

    <section class="bg-coolGray-100">
      <div
        class="container mx-auto flex flex-col items-center px-4 py-16 text-center md:py-32 md:px-10 lg:px-32 xl:max-w-3xl"
      >
        <h1 class="text-2xl font-medium leading-none sm:text-4xl">
          Trusted By Thousands Of
          <span>Happy Customers</span>
        </h1>
        <p class="px-2 pricing-text mt-4 mb-4 text-base">
          Cupiditate minima voluptate temporibus quia? Architecto beatae esse ab
          amet vero eaque explicabo! Cupiditate minima voluptate
        </p>
      </div>
    </section>

    <!-- reviews -->
	<div class="container border flex flex-col w-full max-w-lg p-6 px-8 mx-auto review rounded-md ">
		<div class="flex justify-between p-4">
			<div class="flex space-x-4">
				<div>
					<img src="../assets/Ellipse.png" alt="" class="object-cover w-12 h-12 rounded-full bg-coolGray-500">
				</div>
				<div>
					<h4 class="font-bold">Viezh Roberts</h4>
					<span class="text-xs text-coolGray-600">2 days ago</span>
				</div>
			</div>
			<div class="flex items-center space-x-2 text-yellow-500">
				<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512" class="w-5 h-5 fill-current">
					<path d="M494,198.671a40.536,40.536,0,0,0-32.174-27.592L345.917,152.242,292.185,47.828a40.7,40.7,0,0,0-72.37,0L166.083,152.242,50.176,171.079a40.7,40.7,0,0,0-22.364,68.827l82.7,83.368-17.9,116.055a40.672,40.672,0,0,0,58.548,42.538L256,428.977l104.843,52.89a40.69,40.69,0,0,0,58.548-42.538l-17.9-116.055,82.7-83.368A40.538,40.538,0,0,0,494,198.671Zm-32.53,18.7L367.4,312.2l20.364,132.01a8.671,8.671,0,0,1-12.509,9.088L256,393.136,136.744,453.3a8.671,8.671,0,0,1-12.509-9.088L144.6,312.2,50.531,217.37a8.7,8.7,0,0,1,4.778-14.706L187.15,181.238,248.269,62.471a8.694,8.694,0,0,1,15.462,0L324.85,181.238l131.841,21.426A8.7,8.7,0,0,1,461.469,217.37Z"></path>
				</svg>
				<span class="text-xl font-bold">4.5</span>
			</div>
		</div>
		<div class="p-4 space-y-2 text-sm text-coolGray-600">
			<p>Vivamus sit amet turpis leo. Praesent varius eleifend elit, eu dictum lectus consequat vitae. Etiam ut dolor id justo fringilla finibus.</p>
			<p>Donec eget ultricies diam, eu molestie arcu. Etiam nec lacus eu mauris cursus venenatis. Maecenas gravida urna vitae accumsan feugiat. Vestibulum commodo, ante sit urna purus rutrum sem.</p>
		</div>
	</div>

    <div
      class="lg:flex mt-20 rounded border-10 items-center justify-between px-8 py-8 lg:w-3/4 sm:w-full mx-auto border-white mb-12 bg-gray-100 "
    >
      <div class="lg:w-1/2">
        <h1 class="text-2xl font-medium leading-tight sm:text-4xl">
          Subscribe Now And
          <span>Get Special Features</span>
        </h1>
        <p class="py-4">
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Minima
          aliquam ipsam placeat pariatur 
          
        </p>
      </div>
      <div>
     <button
        class=" text-lg button font-semibold px-8 py-2  mt-4 lg:w-full rounded text-white "
      >
        Subscribe Now
      </button>
      </div>
    </div>

    
     
  </div>
</template>

<script>
export default {
  data() {
    return {
      happyman: require("../assets/developer.png"),
    };
  },
};
</script>

<style scoped>
.hero {
  color: #0b132a;
  text-shadow: 0px 1px 3px #0b132a;
}
.color {
  color: #4f5665;
}
.pricing-text {
  color: #0b132a;
}
.button {
  border: 2px solid #ba55d3;
}
.review{
  border: 3px solid #BA55D3;
  border-radius: 4px;
}
footer{
  background-color: #E5E5E5;
}
</style>

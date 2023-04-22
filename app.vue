<template>
  <div>
    <!-- <NuxtWelcome /> -->

    <!-- NAVBAR START -->
    <header
      class="sticky top-0 z-50 flex justify-between items-center space-x-1 border-b bg-white p-4 shadow-md"
    >
      <a href="" class="text-3xl font-mono">cartrader</a>
    </header>
    <!-- NAVBAR END -->

    <!-- HOME HERO START -->
    <div
      class="relative h-screen w-100 bg-no-repeat bg-cover bg-bottom bg-[url('https://hips.hearstapps.com/hmg-prod/images/20190923-pcoty-2489-ct-1574785275.jpg?crop=0.566xw:0.566xh;0.228xw,0.296xh&resize=980:*')]"
    >
      <div class="z-10 absolute w-full h-full flex justify-center items-center">
        <div class="text-center w-1/2">
          <h1 class="text-white text-8xl font-serif mb-10">Find your drive</h1>
          <!-- seacrh bar -->
          <div class="font-serif w-[1000px] text-2xl rounded-full bg-white flex justify-between overflow-hidden drop-shadow-2xl mx-auto">
            <input type="text" class="py-3 px-5 w-full text-2xl rounded-full focus:outline-none" placeholder="Search by city...">
            <button class="bg-sky-500 px-10 text-white">Search</button>
          </div>
          <!-- search bar -->
        </div>
      </div>
      <div class="z-1 absolute w-full h-full bg-black opacity-50"></div>
    </div>
    <!-- HOME HERO END -->
  </div>
</template>

<template>
  <div class="bg-white rounded-[10px] shadow-sm w-[601px] h-[228px]">
    <div class="flex flex-col space-y-[15px] py-[35px] px-[31px]">
      <div class="flex flex-row justify-between items-center">
        <div class="flex flex-col">
          <div class="inline-flex items-center space-x-[22px]">
            <!-- Avatar -->
            <div class="flex items-center justify-center w-[50px] h-[50px]">
              <NuxtImg src="me.jpg" class="rounded-full" alt="Gambar user" />
            </div>
            <!-- Name and username -->
            <div class="flex flex-col space-y-[1px]">
              <h1 class="font-bold text-[18px]">Adimas Sastra Nugraha</h1>
              <h2 class="text-[#000000] opacity-[60%] text-[16px]">
                @dimassastra
              </h2>
            </div>
          </div>
        </div>
        <img src="~/assets/img/twit-bird.png" alt="a bird" />
      </div>
      <p class="leading-[26px] text-[16px]">
        Why do they call it 'debugging' when it feels more like 'wildly guessing
        and hoping for the best'?
        <span class="text-[#1DA1F2]">#programming </span>
        <span class="text-[#1DA1F2]">#coding </span>
        <span class="text-[#1DA1F2]">#debugging</span>
      </p>
      <!-- Action button -->
      <div class="inline-flex items-center space-x-[20px]">
        <div class="inline-flex items-center space-x-[10px]">
          <NuxtImg src="love.png" alt="love" class="w-[20.9px] h-[18.23px]" />
          <span class="font-bold text-[#000000] opacity-[60%]">650</span>
        </div>
        <span class="text-[#000000] opacity-[60%] font-bold"
          >3:40 PM – Feb 24, 2022</span
        >
      </div>
    </div>
  </div>
</template>

<script setup>
definePageMeta({
  name: "BaseCard",
});
</script>

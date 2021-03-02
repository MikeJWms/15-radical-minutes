<template>
  <div>
    <div class="bg-indigo-800 px-4 rounded-lg mb-6 mx-6">
      <h2 class="text-white text-center pt-9 pb-0 text-2xl font-normal md:font-semibold md:text-3xl">Our previous guests:</h2>
      <div class="flex flex-wrap w-full justify-center py-5">
        <div class="personality sm:w-full md:w-40">
          <img src="@/assets/Nadya_Okamoto_400x400.jpg" alt="" />
          <p>Nadya Okamoto</p>
          <span class="text-gray-200 font-light">Entrepreneur</span>
        </div>

        <div class="personality sm:w-full md:w-40">
          <img src="@/assets/Ana_Chaud_400x400.jpg" alt="" />
          <p>Ana Chaud</p>
          <span class="text-gray-200 font-light">Entrepreneur</span>
        </div>

        <div class="personality sm:w-full md:w-40">
          <img src="@/assets/Skip_Newberry_400x400.jpg" alt="" />
          <p>Skip Newberry</p>
          <span class="text-gray-200 font-light">CEO @ TAO</span>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
img {
  clip-path: circle(50% at 50% 50%);
  max-width: 100%;
  @apply mx-auto;
  @apply mb-4;
}

.personality {
  @apply m-10;
  @apply text-center;
  @apply text-white;
  @apply flex-row-reverse;
}
</style>
<template>
  <div>
    <div class="bg-indigo-800 px-4 rounded-lg mb-6 mx-6">
      <h2
        class="text-white text-center pt-9 pb-0 text-2xl font-normal md:font-semibold md:text-3xl"
      >
        Our previous guests:
      </h2>
      <div class="flex flex-wrap w-full justify-center py-5">
        <div v-for="previousGuest in previousGuests" :key="previousGuest.name">
          <Guest
            :image="previousGuest.picturePath"
            :name="previousGuest.name"
            :title="previousGuest.title"
          />
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data() {
    return {
      previousGuests: [
        {
          picturePath: require('@/assets/sam_adams_400x400.jpg'),
          name: 'Sam Adams',
          title: 'Former Mayor, Portland, OR',
        },
        {
          picturePath: require('@/assets/Nadya_Okamoto_400x400.jpg'),
          name: 'Nadya Okamoto',
          title: 'Social Entrepreneur & Author',
        },
        {
          picturePath: require('@/assets/Ana_Chaud_400x400.jpg'),
          name: 'Ana Chaud',
          title: 'Food Entrepreneur & Startup Stratagist',
        },
        {
          picturePath: require('@/assets/Skip_Newberry_400x400.jpg'),
          name: 'Skip Newberry',
          title: 'CEO, Technology Association of Oregon',
        },
      ],
    }
  },
})
</script>

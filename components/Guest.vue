<template>
  <div class="personality sm:w-full md:w-40">
    <img
      :src="image"
      alt=""
      class="shadow-lg rounded-full max-w-full h-auto align-middle border-none"
    />
    <p class="text-xl font-semibold mt-3">{{ name }}</p>
    <span class="text-gray-200 font-light">{{ title }}</span>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  props: {
    image: {
      type: String,
      default: null,
    },
    name: {
      type: String,
      default: 'Null',
    },
    title: {
      type: String,
      default: '',
    },
  },
})
</script>


<style scoped>
.personality {
  @apply m-10;
  @apply text-center;
  @apply text-white;
  @apply flex-row-reverse;
}
</style>
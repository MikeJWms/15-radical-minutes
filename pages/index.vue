<template>
  <div>
    <div class="container">
      <div>
        <h1 class="text-indigo-900 text-6xl font-bold my-5">
          15 Radical Minutes
        </h1>
        <p class="text-gray-600 text-xl">with</p>
        <h2 class="text-gray-600 text-4xl my-2 mb-14">Michael & Cody</h2>
        <p>
          Join us on Clubhouse for 15 radical minutes with some of today's most
          inspiring thought leaders, builders, and innovators.
        </p>
        <br />
        <p>Follow <a href="https://twitter.com/15radicalmins" class="text-blue-500">@15radicalminutes</a> on twitter to see when we're live next!</p>
      </div>
    </div>
    <PreviousGuests class="max-w-6xl mx-auto" />
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 70vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  @apply px-4;
  @apply max-w-6xl;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

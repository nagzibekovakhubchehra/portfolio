<script setup lang="ts">

</script>

<template>
  <section id="contact" class="px-6 sm:px-10 md:px-16 py-12 bg-rose-100 dark:bg-gray-800">
    <h2 class="text-indigo-500 text-3xl sm:text-4xl font-semibold text-center mb-6">Connect with Me</h2>
    <p class=" dark:text-white text-black  text-lg text-center mb-8"></p>
    <form class="max-w-2xl mx-auto space-y-6">
      <input type="text" placeholder="Name" required class="w-full p-4 rounded-lg dark:bg-gray-700  bg-gray-300 text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-indigo-500">
      <input type="email" placeholder="Email" required class="w-full p-4 rounded-lg dark:bg-gray-700  bg-gray-300 text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-indigo-500">
      <textarea placeholder="Message" required class="w-full p-4 rounded-lg dark:bg-gray-700  bg-gray-300 text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-indigo-500" rows="5"></textarea>
      <button type="submit" class="w-full bg-blue-400 dark:bg-indigo-500 text-white py-3 rounded-lg font-semibold hover:bg-indigo-600 transition">Send</button>
    </form>
  </section>
</template>

<style scoped>

</style>
<template>
  <div>
    <NuxtLayout/>
    <div class="py-12 bg-cyan-700 h-auto theme-mode dark:bg-black">
      <div class="max-w-7xl mx-auto px-1 sm:px-6 lg:px-8">
        <div class=" inline-flex">
          <p class="mt-2 text-2xl leading-8 font-extrabold tracking-tight md:text-7xl dark:text-white">
            Full Stack <span class="bg-clip-text text-transparent bg-gradient-to-r from-indigo-500 to-teal-400 hover:from-green-500 hover:to-teal-400">Step by
              Step</span>
          </p>
          <img src="~/assets/img/header.png" class=" h-96" alt="LDPC Logo" />
        </div>
        <p class="text-white mb-4">
            Sea ipsum kasd eirmod kasd magna, est sea et diam ipsum est amet sed
            sit. Ipsum dolor no justo dolor et, lorem ut dolor erat dolore sed
            ipsum at ipsum nonumy amet. Clita lorem dolore sed stet et est justo
            dolore.
          </p>
      </div>
      <div class="flex justify-center my-20">
        <!-- <button @click="show = !show">Toggle Slide + Fade</button> -->
      </div>

    </div>
    <div class="flex justify-center">
      <site-map-grid />
    </div>
  </div>
  <footer>
      <Thefooter/>
  </footer>
</template>

<script setup>

</script>

<style scoped>

</style>
<template>
  <footer class="mt-32 mx-4 flex flex-col">
    <div class="flex flex-col justify-center items-center">
      <div
        class="logo w-12"
        v-html="require(`~/assets/icons/logo.svg?include`)"
      ></div>
      <!-- <p class="font-extrabold leading-tight">
        Digital&nbsp;Business&nbsp;Card
        <br />
        Generator
      </p> -->
      <p class="font-extrabold text-xl mt-2 leading-tight">Business Card Generator</p>
    </div>
    <p class="mt-6 text-center text-gray-400">
      Giving credit ❤️ to
      <a
        class="mt-6 text-center text-gray-400"
        rel="noopener noreferrer"
        >Vishnu&nbsp;Raghav</a
      >
    </p>
    <p class="mt-1 mb-8 text-center text-xs text-gray-400">
    AGPLv3 License
    </p>
  </footer>
</template>

<script>
export default {}
</script>

<style>
</style>
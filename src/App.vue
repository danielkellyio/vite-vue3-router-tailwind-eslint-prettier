<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup

</script>

<template>
  <ul class="flex mb-10 gap-4 bg-gray-500 p-5 text-white">
    <li><router-link :to="{name:'Home'}">Home</router-link></li>
    <li><router-link :to="{name:'About'}">About</router-link></li>
  </ul>
  <div class="max-w-5xl m-auto">
    <router-view/>
  </div>
</template>

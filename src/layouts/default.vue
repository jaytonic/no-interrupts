<script setup lang="ts">
import { RouterView } from 'vue-router';

</script>

<template>
  <header class="flex justify-around">
    <Header class="w-10/12 max-w-screen-lg"></Header>
  </header>

  <div class="grow h-full flex justify-around">
    <div class="bg-white m-5 rounded-lg p-3 w-10/12 max-w-screen-lg shadow-lg">

      <RouterView />
    </div>
  </div>
</template>


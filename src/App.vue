<script setup lang="ts">
let src =
  "https://images.unsplash.com/photo-1501196354995-cbb51c65aaea?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=facearea&facepad=4&w=256&h=256&q=80";
</script>
<template>
  <!-- start of heading -->
  <div name="heading" class="bg-blue-600 flex gap-4 p-4">
    <div class="flex flex-col items-center mx-auto">
      <img class="rounded-full w-36 mt-4" :src="src" />
      <strong class="mt-4">Andrew Alfred</strong>
      <span class="mt-8">Technical advisor</span>
    </div>
  </div>
  <!-- end of heading -->
</template>

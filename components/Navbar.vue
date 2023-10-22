<script lang="ts" setup>
import PawLogo from "./PawLogo.vue";
</script>
<template>
  <nav class="flex justify-between py-4">
    <h1 class="text-3xl flex gap-3 items-center justify-center font-bold">
      <div class="text-black">
        <PawLogo />
      </div>
      Nally
    </h1>

    <ul>
      <li>
        <Button>Join the waitlist</Button>
      </li>
    </ul>
  </nav>
</template>

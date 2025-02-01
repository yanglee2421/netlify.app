<script setup lang="ts">
import { NuxtPage } from "#components";

useHeadSafe({
  link: [
    {
      type: "image/vnd.microsoft.icon",
      href: "favicon.ico",
      rel: "icon",
    },
  ],
});
</script>

<template>
  <div class="dark">
    <NuxtPage />
  </div>
</template>

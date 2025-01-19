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
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>

<script lang="ts" setup>
import { NuxtLink } from "#components";
</script>

<template>
  <header
    class="fixed top-0 left-0 h-16 w-full border-b bg-white/60 px-5 py-3 backdrop-blur-xs"
  ></header>
  <aside class="fixed top-0 left-0 h-dvh w-64 pt-16">
    <nav class="h-full border-e">
      <ul>
        <li>
          <NuxtLink :to="'/'"> home </NuxtLink>
        </li>
        <li><NuxtLink :to="'/nuxt'"> about </NuxtLink></li>
      </ul>
    </nav>
  </aside>
  <div class="flex min-h-dvh flex-col ps-64 pt-16">
    <main class="grow p-5">
      <div class="h-full border dark:text-blue-500">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet nostrum
        optio dolores laboriosam esse architecto vel hic! Velit reiciendis
        corrupti quas totam ipsam vitae, eos fuga modi, iste nesciunt expedita!
      </div>
    </main>
    <footer class="px-5 py-3">&copy;2025 by yanglee</footer>
  </div>
</template>

<style lang="scss" scoped></style>

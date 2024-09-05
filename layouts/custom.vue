<script lang="ts" setup></script>

<template>
  <div
    class="flex min-h-dvh flex-col divide-y bg-white text-slate-700 dark:bg-black dark:text-slate-200"
  >
    <header class="flex items-center px-5 py-2">
      <NuxtLink to="/" class="me-auto">
        <h2 class="text-xl">Just TailwindCSS</h2>
      </NuxtLink>
      <div class="flex items-center gap-2">
        <div
          class="flex size-8 items-center justify-center rounded-full bg-red-500"
        >
          <span class="tracking-wider text-white">YL</span>
        </div>
        <div>
          <p class="text-sm">Yotu_Lee</p>
          <p class="text-xs">hello world</p>
        </div>
      </div>
    </header>
    <main class="flex flex-auto divide-x">
      <aside class="px-5 py-2">
        <nav>
          <ul>
            <li class="">
              <NuxtLink to="/components/button">Button</NuxtLink>
            </li>
            <li class="">
              <NuxtLink to="/components/list">List</NuxtLink>
            </li>
          </ul>
        </nav>
      </aside>
      <div class="min-w-0 flex-1 px-5 py-2">
        <slot></slot>
      </div>
    </main>
    <footer class="px-5 py-2">
      &copy;2024 by
      <a
        href="https://github.com/yanglee2421"
        class="text-blue-500 hover:underline"
        >yanglee2421</a
      >
    </footer>
  </div>
</template>

<style lang="scss" scoped></style>

<script lang="ts" setup>
const menus = [
  {
    href: "/components/button",
    label: "button",
  },
  {
    href: "/components/list",
    label: "list",
  },
  {
    href: "/components/table",
    label: "table",
  },
];
</script>

<template>
  <div
    class="flex min-h-dvh flex-col divide-y bg-white text-slate-900 antialiased dark:bg-slate-900 dark:text-white"
  >
    <header class="flex items-center px-5 py-2">
      <NuxtLink to="/" class="me-auto">
        <h2 class="text-xl tracking-tight">Just TailwindCSS</h2>
      </NuxtLink>
      <div class="flex items-center gap-2">
        <div
          class="flex size-8 items-center justify-center rounded-full bg-red-500"
        >
          <span class="tracking-wider text-white">YL</span>
        </div>
        <div>
          <p class="text-sm">Yotu_Lee</p>
          <p class="text-xs text-slate-500 dark:text-slate-400">hello world</p>
        </div>
      </div>
    </header>
    <main class="flex flex-auto divide-x">
      <aside class="w-48">
        <nav>
          <ul>
            <li v-for="item in menus" :key="item.href">
              <NuxtLink
                :to="item.href"
                class="block w-full px-5 py-2 font-medium capitalize tracking-wide text-slate-500 hover:bg-gray-100 hover:text-blue-500 aria-[current=page]:text-blue-600"
                >{{ item.label }}</NuxtLink
              >
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

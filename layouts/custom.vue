<script lang="ts" setup>
const menus = [
  {
    href: "/components/buttons",
    label: "buttons",
  },
  {
    href: "/components/list",
    label: "list",
  },
  {
    href: "/components/datagrid",
    label: "datagrid",
  },
  {
    href: "/components/tags",
    label: "tags",
  },
  {
    href: "/components/checkbox",
    label: "checkbox",
  },
  {
    href: "/components/textfield",
    label: "textfield",
  },
  {
    href: "/components/card",
    label: "card",
  },
];
</script>

<template>
  <div
    class="flex min-h-dvh flex-col bg-white text-slate-900 antialiased dark:bg-slate-900 dark:text-white"
  >
    <header
      class="sticky top-0 flex h-14 w-full items-center border-b bg-white/50 px-5 py-2 backdrop-blur dark:bg-black/50"
    >
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
    <div class="flex flex-auto">
      <aside class="fixed bottom-0 top-14 w-48 overflow-y-auto border-e">
        <nav class="">
          <ul>
            <li v-for="item in menus" :key="item.href">
              <NuxtLink
                :to="item.href"
                class="block w-full px-5 py-2 font-medium capitalize tracking-wide text-slate-500 hover:bg-slate-100 hover:text-blue-500 aria-[current=page]:text-blue-600 dark:hover:bg-slate-800"
                >{{ item.label }}</NuxtLink
              >
            </li>
          </ul>
          <div class="h-96" v-for="item in 3" :key="item"></div>
        </nav>
      </aside>
      <div class="flex min-h-full w-full flex-col ps-48">
        <main class="flex-auto px-5 py-2">
          <slot></slot>
        </main>
        <footer class="border-t px-5 py-2">
          &copy;2024 by
          <a
            href="https://github.com/yanglee2421"
            class="text-blue-500 hover:underline"
            >yanglee2421</a
          >
        </footer>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped></style>

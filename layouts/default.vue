<script lang="ts" setup>
const links = [
  [
    {
      label: "Profile",
      avatar: {
        src: "https://avatars.githubusercontent.com/u/739984?v=4",
      },
      badge: 100,
    },
    {
      label: "Installation",
      icon: "i-heroicons-home",
      to: "/getting-started/installation",
    },
    {
      label: "Vertical Navigation",
      icon: "i-heroicons-chart-bar",
      to: "/components/vertical-navigation",
    },
    {
      label: "Command Palette",
      icon: "i-heroicons-command-line",
      to: "/components/command-palette",
    },
  ],
  [
    {
      label: "Examples",
      icon: "i-heroicons-light-bulb",
    },
    {
      label: "Help",
      icon: "i-heroicons-question-mark-circle",
    },
  ],
];

const state = reactive({ showNav: false });
</script>

<template>
  <header
    class="fixed left-0 top-0 z-20 h-16 w-full bg-gray-800/60 backdrop-blur"
  >
    <div
      class="flex h-full items-center border-b border-gray-200 px-2.5 dark:border-gray-800"
    >
      <UButton
        @click="state.showNav = !state.showNav"
        icon="i-heroicons-list-bullet"
        class="sm:hidden"
      ></UButton>
      <h2 class="hidden sm:block">NETLIFY.APP</h2>
    </div>
  </header>
  <aside
    :aria-hidden="state.showNav"
    class="fixed z-10 h-dvh w-full pt-16 aria-hidden:hidden sm:!block sm:max-w-72"
  >
    <div class="h-full border-e border-gray-200 dark:border-gray-800">
      <UVerticalNavigation :links="links" />
    </div>
  </aside>
  <div
    :aria-hidden="!state.showNav"
    class="flex min-h-dvh flex-col pt-16 aria-hidden:hidden sm:!flex sm:ps-72"
  >
    <main class="flex-grow p-5">
      <slot></slot>
    </main>
    <footer class="container mx-auto px-5 py-3.5">&copy;2025 by yanglee</footer>
  </div>
</template>

<style lang="scss" scoped></style>

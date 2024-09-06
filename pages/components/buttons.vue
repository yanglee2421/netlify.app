<script lang="ts" setup>
const colorSchema = {
  primary: "blue-500",
  error: "red-500",
  success: "green-500",

  text: {
    primary: "slate-900",
    secondary: "slate-500",
  },

  actions: {
    hover: "",
    active: "",

    focus: "",

    disabled: "",
    selected: "",
  },
};
</script>

<template>
  <NuxtLayout name="custom">
    <div class="space-y-6">
      <section class="space-y-1">
        <p class="paper font-semibold capitalize tracking-wide">red</p>
        <p class="flex flex-wrap gap-2 rounded border p-3 shadow">
          <button class="min-w-16 rounded bg-red-500 px-3 py-1 text-white">
            red
          </button>
          <button class="min-w-16 rounded bg-red-600 px-3 py-1 text-white">
            red:hover
          </button>
          <button class="min-w-16 rounded bg-red-700 px-3 py-1 text-white">
            red:active
          </button>
          <button
            class="min-w-16 rounded bg-red-500 px-3 py-1 text-white outline outline-offset-2 outline-red-400"
          >
            red:focus
          </button>
        </p>
      </section>
      <section class="space-y-1">
        <p class="paper font-semibold capitalize tracking-wide">green</p>
        <p class="flex flex-wrap gap-2 rounded border p-3 shadow">
          <button class="min-w-16 rounded bg-green-500 px-3 py-1 text-white">
            green
          </button>
          <button class="min-w-16 rounded bg-green-600 px-3 py-1 text-white">
            green:hover
          </button>
          <button class="min-w-16 rounded bg-green-700 px-3 py-1 text-white">
            green:active
          </button>
          <button
            class="min-w-16 rounded bg-green-500 px-3 py-1 text-white outline outline-offset-2 outline-green-400"
          >
            green:focus
          </button>
        </p>
      </section>
      <section class="space-y-1">
        <p class="paper font-semibold capitalize tracking-wide">blue</p>
        <p class="flex flex-wrap gap-2 rounded border p-3 shadow">
          <button class="min-w-16 rounded bg-blue-500 px-3 py-1 text-white">
            blue
          </button>
          <button class="min-w-16 rounded bg-blue-600 px-3 py-1 text-white">
            blue:hover
          </button>
          <button class="min-w-16 rounded bg-blue-700 px-3 py-1 text-white">
            blue:active
          </button>
          <button
            class="min-w-16 rounded bg-blue-500 px-3 py-1 text-white outline outline-offset-2 outline-blue-400"
          >
            blue:focus
          </button>
        </p>
      </section>
      <section class="space-y-1">
        <p class="paper font-semibold capitalize tracking-wide">indigo</p>
        <p class="flex flex-wrap gap-2 rounded border p-3 shadow">
          <button class="min-w-16 rounded bg-indigo-500 px-3 py-1 text-white">
            indigo
          </button>
          <button class="min-w-16 rounded bg-indigo-600 px-3 py-1 text-white">
            indigo:hover
          </button>
          <button class="min-w-16 rounded bg-indigo-700 px-3 py-1 text-white">
            indigo:active
          </button>
          <button
            class="min-w-16 rounded bg-indigo-500 px-3 py-1 text-white outline outline-offset-2 outline-indigo-400"
          >
            indigo:focus
          </button>
        </p>
      </section>
      <section class="space-y-1">
        <p class="paper font-semibold capitalize tracking-wide">disabled</p>
        <p class="flex flex-wrap gap-2 rounded border p-3 shadow">
          <button
            disabled
            class="min-w-16 rounded border border-transparent px-3 py-1 text-sm disabled:cursor-not-allowed disabled:bg-slate-200 disabled:text-slate-400"
          >
            disabled
          </button>
        </p>
      </section>
    </div>
  </NuxtLayout>
</template>

<style lang="scss" scoped></style>

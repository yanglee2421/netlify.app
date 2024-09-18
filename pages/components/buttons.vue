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

      <div class="flex items-center justify-center">
        <button
          type="button"
          class="inline-flex items-center rounded-md bg-indigo-500 px-4 py-2 text-sm font-semibold leading-6 text-white shadow"
          disabled
        >
          <svg
            class="-ml-1 mr-3 h-5 w-5 animate-spin text-white motion-reduce:hidden"
            fill="none"
            viewBox="0 0 24 24"
          >
            <circle
              class="opacity-25"
              cx="12"
              cy="12"
              r="10"
              stroke="currentColor"
              stroke-width="4"
            ></circle>
            <path
              class="opacity-75"
              fill="currentColor"
              d="M4 12a8 8 0 018-8V0C5.373 0 0 5.373 0 12h4zm2 5.291A7.962 7.962 0 014 12H0c0 3.042 1.135 5.824 3 7.938l3-2.647z"
            ></path>
          </svg>
          Processing...
        </button>
      </div>

      <button
        class="rounded-full bg-sky-500 px-5 py-2 text-sm font-semibold leading-5 text-white hover:bg-sky-700"
      >
        Save changes
      </button>

      <button
        type="button"
        class="rounded-full bg-violet-500 px-5 py-2 text-sm font-semibold leading-5 text-white hover:bg-violet-600 focus:outline-none focus:ring focus:ring-violet-300 active:bg-violet-700"
      >
        Save changes
      </button>
      <!--  -->
    </div>
  </NuxtLayout>
</template>

<style lang="scss" scoped></style>

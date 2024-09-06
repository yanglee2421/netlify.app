<template>
  <NuxtLayout name="custom">
    <div class="space-y-6 *:shadow">
      <section class="border p-3">
        <label>input</label>
        <fieldset
          class="relative mt-1.5 overflow-clip rounded after:absolute after:bottom-0 after:block after:w-full after:scale-x-0 after:border-b-2 after:border-blue-500 after:transition-transform after:content-[''] has-[input:focus]:after:scale-x-100"
        >
          <input
            type="text"
            class="block w-full rounded border px-1.5 py-0.5 outline-none"
          />
        </fieldset>
      </section>
    </div>
  </NuxtLayout>
</template>

<script lang="ts" setup>
useHead({
  titleTemplate(productCategory) {
    return productCategory
      ? `${productCategory} - Just TailwindCSS`
      : "Just TailwindCSS";
  },
});
</script>

<template>
  <NuxtLayout name="custom">
    <div>home</div>
  </NuxtLayout>
</template>

<style lang="scss" scoped></style>

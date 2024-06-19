<template>
  <div class="grid grid-cols-5 gap-4">
    <div
        v-for="product in products"
        class="flex flex-col shadow-md bg-white p-6 rounded-md"
    >
      <img class="w-[75px] h-auto self-center" :src="product.image" alt="" />
      <h2 class="text-black mt-auto text-sm">{{ product.title }}</h2>
    </div>
  </div>
</template>

<script setup>
const { data: products } = await useFetch("https://fakestoreapi.com/products");
</script>
<style lang="scss" scoped>

</style>

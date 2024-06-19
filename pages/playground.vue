<template>
<!--  <div class="inline-block p-6 bg-gradient-to-bl from-green-400 to-blue-400"></div>-->
  <div class="mt-10 ml-10 w-[1280px] h-[769px] bg-gradient-to-bl from-[#FFFBE3] to-[#FFD031]">

  </div>
</template>

<script setup>
const { data: products } = await useFetch("https://fakestoreapi.com/products");
</script>

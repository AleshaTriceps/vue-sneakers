<script setup>
import Heeader from './components/Heeader.vue'
import CardList from './components/CardList.vue'
</script>

<template>
  <div class="bg-white w-4/5 m-auto h-screen rounded-xl shadow-xl mt-14">
    <Heeader />

    <div class="p-10">
      <h2 class="text-3xl font-bold mb-8">Все Кроссовки</h2>
      <CardList />
    </div>
  </div>
</template>

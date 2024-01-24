<script setup>
import Card from './Card.vue'
</script>
<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      title="Мужские кроссовки"
      image-url="/sneakers/sneakers-1.jpg"
      :price="5000"
      :is-favorite="true"
    />
  </div>
</template>

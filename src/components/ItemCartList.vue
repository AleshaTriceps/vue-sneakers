<script setup>
import { inject } from 'vue'
import ItemCart from './ItemCart.vue'

const { cart, removeFromCart } = inject('cart')

console.log(cart)
</script>

<template>
  <div class="flex flex-col gap-4 justify-between" v-auto-animate>
    <ItemCart
      v-for="item in cart"
      :key="item.id"
      :title="item.title"
      :price="item.price"
      :image-url="item.imageUrl"
      @on-click-remove="() => removeFromCart(item)"
    />
  </div>
</template>

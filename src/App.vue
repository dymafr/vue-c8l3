<script setup lang="ts">
import TheHeader from './components/Header.vue';
import TheFooter from './components/Footer.vue';
import Shop from './components/Shop.vue';
import Cart from './components/Cart.vue';
</script>

<template>
  <div>
    <TheHeader />
    <Shop />
    <Cart />
    <TheFooter />
  </div>
</template>

<style lang="scss">
@import './assets/base.scss';
@import './assets/debug.scss';
</style>

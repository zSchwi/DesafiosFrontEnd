<script setup>
import HeaderComponent from './components/HeaderComponent.vue'
import PromotionSection from './components/PromotionTextComponent.vue'
import ListProducts from './components/ListProductComponent.vue'

  
</script>

<template>
  
  <header>
    <HeaderComponent />
  </header>

  <main>

    <section>
      <PromotionSection />
    </section>

    <section>
      <ListProducts />
    </section>

  </main>

</template>

<style scoped>
  
</style>

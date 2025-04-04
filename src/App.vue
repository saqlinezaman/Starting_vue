<script setup>
import HeaderSectionComponent from './components/HeaderSectionComponent.vue';
import HeroSectionComponent from './components/HeroSectionComponent.vue';
import CategorySectionComponents from './components/CategorySectionComponents.vue';
import NewCollectionComponents from './components/NewCollectionComponents.vue';
import ProductSectionComponenets from './components/ProductSectionComponenets.vue';
import ContactSectionComponents from './components/ContactSectionComponents.vue';
import FooterSectionComponents from './components/FooterSectionComponents.vue';
</script>

<template>
  <!-- header section -->
   <HeaderSectionComponent/>
  <!-- header section end -->

  <!-- hero section -->
    <HeroSectionComponent/>
  <!-- Hero section end  -->

  <!-- Category section -->
    <CategorySectionComponents/>

  <!-- Category section end -->

  <!-- New collection section -->
   <NewCollectionComponents/>
  <!-- New collection section end -->

  <!-- product section -->
   <ProductSectionComponenets/>
  <!-- product section end -->

  <!-- contact section -->
  <ContactSectionComponents/>
   <!-- contact section end -->

  <!-- foter section -->
   <FooterSectionComponents/>
   <!-- foter section end -->
</template>

<style scoped>
</style>

<script setup>


import HeaderAllComponent from '../components/HeaderAllComponent.vue'
import AboutUsComponent from '../components/AboutUsComponent.vue'
import FooterComponent from '../components/FooterComponent.vue'
import CopyrightComponent from '../components/CopyrightComponent.vue'
import ProductComponent from '@/components/ProductComponent.vue';

</script>

<template>
    <div>
        <HeaderAllComponent></HeaderAllComponent>
  <ProductComponent></ProductComponent>
 
  <FooterComponent/>
  <CopyrightComponent/>
    </div>
  
</template>


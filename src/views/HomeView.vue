<script setup>
import Home from '../components/Home.vue'

import HeaderComponent from '../components/HeaderComponent.vue'
import AboutUsComponent from '../components/AboutUsComponent.vue'
import ProductComponent from '../components/ProductComponent.vue'
import ServicesComponent from '../components/ServicesComponent.vue'
import FeedbackComponent from '../components/FeedbackComponent.vue'
import FooterComponent from '../components/FooterComponent.vue'
import CopyrightComponent from '../components/CopyrightComponent.vue'
import HasilPekerjaanComponent from '../components/HasilPekerjaanComponent.vue'
import TeamComponent from '@/components/TeamComponent.vue';
</script>

<template>
  <main>
   <HeaderComponent></HeaderComponent>
  <AboutUsComponent></AboutUsComponent>
  <ProductComponent></ProductComponent>
  <ServicesComponent/>
  <FeedbackComponent/>
  <HasilPekerjaanComponent/>
  <TeamComponent/>
  <FooterComponent/>
  <CopyrightComponent/>
  
  
  </main>
</template>


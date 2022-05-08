<template>
  <main class="font-display">
    <!-- not yet responsive to mobile or any small screens -->
    <!-- refactor later -->
    <MainSection />
    <!-- <SlideButton />
    <Header /> -->
    <!-- <Slider /> -->
    <!-- <Button /> -->
    <!-- <NewFile /> -->
    <!-- <Feature /> -->
    <!-- <SisyphusSection /> -->
    <!-- <FeatureSection /> -->
    <!-- <FaqSection /> -->
    <!-- <LaunchSection /> -->
    <!-- <FreeTrial /> -->
    <!-- <Footer /> -->
  </main>
</template>

<script lang="ts">
import Vue from 'vue'
import { BootstrapVue, BootstrapVueIcons } from 'bootstrap-vue'
import MainSection from './MainSection.vue'
// import Header from '../components/Header.vue'
// import SlideButton from '../components/SlideButton.vue'
// import Slider from '../components/SliderButton.vue'
// import Button from '../components/Button.vue'
// import NewFile from '../components/NewFile.vue'
// import Feature from '../components/Feature.vue'
// import SisyphusSection from '../components/SisyphusSection.vue'
// import FeatureSection from '../components/FeatureSection.vue'
// import FaqSection from '../components/FaqSection.vue'
// import LaunchSection from '../components/LaunchSection.vue'
// import FreeTrial from '../components/FreeTrial.vue'
// import Footer from '../components/Footer.vue'
Vue.use(BootstrapVue)
Vue.use(BootstrapVueIcons)
// google font nuxt
export default Vue.extend({
  name: 'IndexPage',
  components: {
    MainSection,
    // Header,
    // SlideButton,
    // Slider,
    // Button,
    // NewFile,
    // Feature,
    // SisyphusSection,
    // FeatureSection,
    // FaqSection,
    // LaunchSection,
    // FreeTrial,
    // Footer,
  },
})
</script>
<style scope>
/* main {
  text-align: center;
  margin: 0 auto;
  width: 100vw;
} */
</style>

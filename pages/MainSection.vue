<template>
  <!-- <MainNav /> -->
  <div>
    <MainNav />
    <!-- <Header /> -->
    <Slider />
    <Button />
    <Feature />
    <SisyphusSection />
    <FeatureSection />
    <FaqSection />
    <LaunchSection />
    <FreeTrial />
    <Footer />
  </div>
</template>

<script lang="ts">
// import Header from '../components/Header.vue'
import Slider from '../components/SliderButton.vue'
import Button from '../components/Button.vue'
import MainNav from '../components/MainNav.vue'
import Feature from '../components/Feature.vue'
import SisyphusSection from '../components/SisyphusSection.vue'
import FeatureSection from '../components/FeatureSection.vue'
import FaqSection from '../components/FaqSection.vue'
import LaunchSection from '../components/LaunchSection.vue'
import FreeTrial from '../components/FreeTrial.vue'
import Footer from '../components/Footer.vue'

export default {
  name: 'IndexPage',
  components: {
    // Header,
    Slider,
    Button,
    MainNav,
    Feature,
    SisyphusSection,
    FeatureSection,
    FaqSection,
    LaunchSection,
    FreeTrial,
    Footer,
  },
}
</script>

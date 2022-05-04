<template>
  <!-- <MainNav /> -->
  <div>
    <MainNav />
    <Header />
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
import Header from '../components/Header.vue'
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
    Header,
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

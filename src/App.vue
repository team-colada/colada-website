<script setup>
import HeaderBar from './components/HeaderBar.vue'
import HeroContainer from './components/HeroContainer.vue'
import FeaturesContainer from './components/FeaturesContainer.vue'
import InstallContainer from './components/InstallContainer.vue'
import HowToUse from './components/HowToUse.vue'
import DemoProject from './components/DemoProject.vue'
import ScreenshotsContainer from './components/ScreenshotsContainer.vue'
import ContributorsContainer from './components/ContributorsContainer.vue'
import FooterBar from './components/FooterBar.vue'


</script>

<template>
  <div class="main flex flex-col h-full justify-between bg-slate-900">
    <HeaderBar />
    <HeroContainer />
    <FeaturesContainer />
    <InstallContainer />
    <HowToUse />
    <DemoProject />
    <ScreenshotsContainer />
    <ContributorsContainer />
    <FooterBar />
  </div>
</template>


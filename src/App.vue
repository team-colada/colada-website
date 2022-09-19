<script setup>
import HeaderBar from './components/HeaderBar.vue'
import HeroContainer from './components/HeroContainer.vue'
import InstallContainer from './components/InstallContainer.vue'
import ContributorsContainer from './components/ContributorsContainer.vue'
import FooterBar from './components/FooterBar.vue'
</script>

<template>
  <div class="main">
    <HeaderBar />
    <HeroContainer />
    <InstallContainer />
    <ContributorsContainer />
    <FooterBar />
  </div>
</template>

<style scoped>
  .main{
    display:flex;
    flex-direction:column;
  }
</style>

<script setup>
// import HelloWorld from './components/HelloWorld.vue'
// import TheWelcome from './components/TheWelcome.vue'
import Announcement from './components/Announcement.vue'
import NavMenu from './components/NavMenu.vue'
import Banner from './components/Banner.vue'
</script>

<template>
  <header>
    <Announcement />
    <NavMenu />
  </header>
  <main>
    <Banner 
      layout="right"
      title="Nieuwe titel voor deze banner"
      text="Dit is de tekst voor mijn nieuwe banner!!"/>
    
    <Banner
      title="Dit is mijn tweede banner"
      text="Dit is de tekst voor mijn tweede banner" />


  </main>
  <footer></footer>
</template>


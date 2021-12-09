<template>
  <div id="app">

    <header>
      <!-- top -->
      <HeaderTop/>
      <!-- bottom -->
      <HeaderBottom/>
      
    </header>

    <main>
      <!-- 1 -->
      <HeroSection/>
      <!-- 2 -->
      <BluBar/>

    </main>

    <footer></footer>

  </div>
</template>

<script>
import HeaderTop from '@/components/HeaderTop.vue';
import HeaderBottom from '@/components/HeaderBottom.vue';
import HeroSection from '@/components/HeroSection.vue';
import BluBar from '@/components/BluBar.vue';

export default {
  name: 'App',
  components: {
     HeaderTop,
     HeaderBottom,
     HeroSection,
     BluBar,

  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Mukta', sans-serif;
}

.l-st {
  list-style: none;
}
</style>

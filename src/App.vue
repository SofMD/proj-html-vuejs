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
      <!-- 3 -->
      <AwardSection/>
      <!-- 4 -->
      <ServiceSection/>
      <!-- 5 -->
      <MoveEasySection/>
      <!-- 6 -->
      <TestimonialSection/>

    </main>

    <footer></footer>

  </div>
</template>

<script>
import HeaderTop from '@/components/HeaderTop.vue';
import HeaderBottom from '@/components/HeaderBottom.vue';
import HeroSection from '@/components/HeroSection.vue';
import BluBar from '@/components/BluBar.vue';
import AwardSection from '@/components/AwardSection.vue';
import ServiceSection from '@/components/ServiceSection.vue';
import MoveEasySection from '@/components/MoveEasySection.vue';
import TestimonialSection from '@/components/TestimonialSection.vue';


export default {
  name: 'App',
  components: {
     HeaderTop,
     HeaderBottom,
     HeroSection,
     BluBar,
     AwardSection,
     ServiceSection,
     MoveEasySection,
     TestimonialSection,
  }
}
</script>

<style lang="scss">
@import '@/components/variables.scss'; 
@import '@/components/utility.scss';

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Mukta', sans-serif;
}


</style>

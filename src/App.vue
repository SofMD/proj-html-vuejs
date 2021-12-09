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

export default {
  name: 'App',
  components: {
     HeaderTop,
     HeaderBottom,
     HeroSection,
     BluBar,
     AwardSection,

  }
}
</script>

<style lang="scss">
@import '@/components/variables.scss'; 

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Mukta', sans-serif;
}

.l-st {
  list-style: none;
}

.Awsubtitle{
  font-weight: bold;
  color: $lightgrey;
  font-size: 15px;
  text-transform: uppercase;
    letter-spacing: 0px;
}

h2{
  width: 50%;
  margin: 0 auto;
  font-weight: 900;
  color: $greenLima;
  font-size: 45px;
  letter-spacing: -2px;
  line-height: 1.2;
}

.description{
  color: $maintext;
  margin: 30px 0;
}

.Buttons{
    background-color: $buttoncolor;
    padding: 5px 25px;
    border-radius: 25px;
    border: none;
    color: white;
    text-transform: uppercase;
    font-weight: 800;
    cursor: pointer;
    letter-spacing: 1px;
}
</style>

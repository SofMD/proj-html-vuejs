<template>
  <div id="app">

    <header>
      <!-- top -->
      <HeaderTop/>
      <!-- bottom -->
      <HeaderBottom/>
      
    </header>

    <main></main>

    <footer></footer>

  </div>
</template>

<script>
import HeaderTop from '@/components/HeaderTop.vue';
import HeaderBottom from '@/components/HeaderBottom.vue';

export default {
  name: 'App',
  components: {
     HeaderTop,
     HeaderBottom,

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

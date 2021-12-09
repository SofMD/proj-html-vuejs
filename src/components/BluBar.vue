<template>
  <section class="p-5">
      <a href="/"><i class="far fa-paper-plane"></i> GET A FREE QUOTE ONLINE NOW!</a>
  </section>
</template>

<script>
export default {
    name: 'BluBar',
}
</script>

<style scoped lang="scss">
@import '@/components/variables.scss';

section {
    background-color: $buttoncolor;
    color: white;
    text-align: center;
    
    a{
        text-decoration: none;
        color: white;
    }
}

</style>
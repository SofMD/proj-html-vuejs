<template>
  <section class="d-flex align-items-center justify-content-center">
      <div class="HeroTitle">
          <div>MOVING WITHOUT THE HASSLE</div>
          <h1>WE MAKE IT SIMPLE</h1>
          <div>PROFESSIONAL SERVICE WITH QUALITY AND CUSTOMER SATISFACTION</div>
      </div>
  </section>
</template>

<script>
export default {
    name: 'HeroSection',

}
</script>

<style scoped lang="scss">
@import '@/components/variables.scss';

section {
    background-image: url('../assets/avada-movers-homeherobackground-final.jpg');
    height: 610px;
    background-size: cover; 

    .HeroTitle{
        text-align: center;
        div{
            font-weight: 900;
            color: $heroText;
            font-size: 16px;
        }

        h1{
            font-size: 60px;
            font-weight: 900;
        }
    }
}

</style>
<template>
  <section>
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

    .HeroTitle{
        text-align: center;
        margin: 200px 0;

        div{
            font-weight: bold;
            color: $heroText;
            font-size: 15px;
        }

        h1{
            font-size: 60px;
            font-weight: 900;
        }
    }
}

</style>
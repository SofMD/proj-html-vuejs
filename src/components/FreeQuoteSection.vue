<template>
  <section>
      <div class="quoteContainer">
          <!-- title -->
          <h2>Request a Free Quote</h2>
          <!-- text -->
          <p class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Pariatur omnis architecto distinctio quos, alias vero consequatur quidem, voluptatum aspernatur praesentium quasi sint inventore adipisci. Laudantium, saepe aliquam. Eligendi, perspiciatis vel!</p>
          <!-- button -->
          <button class="Buttons mt-4">Click Here</button>
      </div>
  </section>
</template>

<script>
export default {
    name: 'FreeQuoteSection',
}
</script>

<style scoped lang="scss">
@import '@/components/variables.scss';

section{
    margin-top: 120px;
    background-image: url('../assets/avada-movers-request-quote-background.jpg');
    padding: 150px;

    .quoteContainer{
        text-align: center;
        width: 50%;
        margin: 0 auto;
    }
}

</style>
<template>
  <section class="p-5">
      <div class="servContainer">
          <div class="Awsubtitle">We are a professional</div>
          <h2>Full-Service Solution</h2>

          <!-- card section -->
          <div class="d-flex justify-content-between pt-5">
              <!-- card -->
              <div class="serviceCard">
                  <!-- image -->
                  <img src="../assets/avada-movers-serviceonephoto-final-400x255.jpg" alt="">
                  <!-- title -->
                  <h3 class="mt-4" >Two Man Teams</h3>
                  <!-- description -->
                  <div class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam sed ipsa soluta dignissimos, et quam reprehenderit vero explicabo voluptatum provident!</div>
                  <!-- button -->
                  <button class="Buttons mt-3">Read More</button>

              </div>
              <!-- card 2-->
              <div class="serviceCard">
                  <!-- image -->
                  <img src="../assets/avada-movers-servicetwophoto-final-400x255.jpg" alt="">
                  <h3  class="mt-4">We Do All The Lifting</h3>
                  <!-- description -->
                  <div class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam sed ipsa soluta dignissimos, et quam reprehenderit vero explicabo voluptatum provident!</div>
                  <!-- button -->
                  <button class="Buttons mt-3">Read More</button>

              </div>
              <!-- card 3-->
              <div class="serviceCard">
                  <!-- image -->
                  <img src="../assets/avada-movers-servicethreephoto-final-400x255.jpg" alt="">
                  <h3 class="mt-4">Coast To Coast</h3>
                  <!-- description -->
                  <div class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam sed ipsa soluta dignissimos, et quam reprehenderit vero explicabo voluptatum provident!</div>
                  <!-- button -->
                  <button class="Buttons mt-3">Read More</button>

              </div>
          </div>

      </div>
  </section>
</template>

<script>
export default {
    name: 'ServiceSection',
}
</script>

<style scoped lang="scss">
@import '@/components/variables.scss';

section{
    margin: 150px 0;

    .servContainer{
        width: 65%;
        margin: 0 auto;
        text-align: center;

        .serviceCard{

            img {
                width: 350px;
            }

            .description{
                width: 275px;
                margin: 10px auto;
                font-size: 15px;
            }
        }
    }
}

</style>

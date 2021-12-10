<template>
  <section>
      <div class="TestContainer mb-5">
           <div class="Awsubtitle">happy customers</div>
          <h2>Testimonials</h2>

          <!-- card section -->
          <div class="d-flex justify-content-between pt-5">
              <!-- card -->
              <div class="serviceCard">
                  <!-- image -->
                  <img src="../assets/avada-movers-johndoe-final.jpg" alt="">
                  <!-- title -->
                  <h3 class="mt-4" >John Doe</h3>
                  <!-- description -->
                  <div class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam sed ipsa soluta dignissimos, et quam reprehenderit vero explicabo voluptatum provident!</div>

              </div>
              <!-- card 2-->
              <div class="serviceCard">
                  <!-- image -->
                  <img src="../assets/avada-movers-janedoe-final.jpg" alt="">
                  <h3  class="mt-4">Jane Doe</h3>
                  <!-- description -->
                  <div class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam sed ipsa soluta dignissimos, et quam reprehenderit vero explicabo voluptatum provident!</div>

              </div>
              <!-- card 3-->
              <div class="serviceCard">
                  <!-- image -->
                  <img src="../assets/avada-movers-johnsmith-final.jpg" alt="">
                  <h3 class="mt-4">John Smith</h3>
                  <!-- description -->
                  <div class="description">Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam sed ipsa soluta dignissimos, et quam reprehenderit vero explicabo voluptatum provident!</div>

              </div>
          </div>

          <!-- bottone -->
          <button class="Buttons my-5">read more testimonials</button>

      </div>
  </section>
</template>

<script>
export default {
    name: 'TestimonialSection',
}
</script>

<style scoped lang="scss">
@import '@/components/variables.scss';

section{
    margin-top: 150px;
}

.TestContainer{
    width: 65%;
    margin: 0 auto;
    text-align: center;

    .serviceCard{

            img {
                width: 140px;
                border-radius: 50%;
            }

            .description{
                width: 330px;
                margin: 10px auto;
                font-size: 15px;
                font-style: italic;
            }
    }
}


</style>
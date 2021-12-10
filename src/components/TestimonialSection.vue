<template>
  <section>
      <div class="TestContainer mb-5">
           <div class="Awsubtitle">happy customers</div>
          <h2>Testimonials</h2>

          <!-- card section -->
          <div class="d-flex justify-content-between pt-5">
              <!-- card -->
              <div class="testCard" v-for="(el, index) in testimonialsList" :key="`service-${index}`">

                  <TestimonialsCards :src="el.src" :title="el.title" :description="el.description"/>

              </div>
          </div>

          <!-- bottone -->
          <button class="Buttons my-5">read more testimonials</button>

      </div>
  </section>
</template>

<script>
import TestimonialsCards from '@/components/TestimonialsCards.vue';

export default {
    name: 'TestimonialSection',
    components: {
        TestimonialsCards,
    },

    data(){
        return {
            testimonialsList: [
                {
                    src: require('../assets/avada-movers-johndoe-final.jpg'),
                    title: 'John Doe',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam sed ipsa soluta dignissimos, et quam reprehenderit vero explicabo voluptatum provident!',
                },
                {
                    src: require('../assets/avada-movers-janedoe-final.jpg'),
                    title: 'Jane Doe',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam sed ipsa soluta dignissimos, et quam reprehenderit vero explicabo voluptatum provident!',
                },
                {
                    src: require('../assets/avada-movers-johnsmith-final.jpg'),
                    title: 'John Smith',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam sed ipsa soluta dignissimos, et quam reprehenderit vero explicabo voluptatum provident!',
                }
            ]
        }
    }
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

    .testCard{

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
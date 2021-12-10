<template>
  <section class="p-5">
      <div class="servContainer">
          <div class="Awsubtitle">We are a professional</div>
          <h2>Full-Service Solution</h2>

          <!-- card section -->
          <div class="d-flex justify-content-between pt-5">
              <!-- card -->
              <div class="serviceCard" v-for="(el, index) in serviceList" :key="`service-${index}`">

                  <ServiceCards :src="el.src" :title="el.title" :description="el.description" :button="el.button" />
                  
              </div>
              
          </div>

      </div>
  </section>
</template>

<script>
import ServiceCards from '@/components/ServiceCards.vue';

export default {
    name: 'ServiceSection',

    components: {
        ServiceCards,
    },

    data(){
        return {
            serviceList: [
                {
                    src: require('../assets/avada-movers-serviceonephoto-final-400x255.jpg'),
                    title: 'Two Man Teams',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam sed ipsa soluta dignissimos, et quam reprehenderit vero explicabo voluptatum provident!',
                    button: 'Read More',
                },
                {
                    src: require('../assets/avada-movers-servicetwophoto-final-400x255.jpg'),
                    title: 'We Do All The Lifting',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam sed ipsa soluta dignissimos, et quam reprehenderit vero explicabo voluptatum provident!',
                    button: 'Read More',
                },
                {
                    src: require('../assets/avada-movers-servicethreephoto-final-400x255.jpg'),
                    title: 'Coast To Coast',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam sed ipsa soluta dignissimos, et quam reprehenderit vero explicabo voluptatum provident!',
                    button: 'Read More',
                }
            ]
        }
    }
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
    }
}

</style>

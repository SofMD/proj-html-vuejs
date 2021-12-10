<template>
  <section>
      <div class="d-flex p-3 justify-content-between align-items-center">
          <!-- logo -->
          <div class="headerImage">
              <img src="../assets/avada-movers-logo.png" alt="">
          </div>
          <!-- lista -->
          <div>
              <ul class="headerList l-st d-flex justify-content-end align-items-center">
                  <!-- menu dinamico  -->
                  <li class="ms-4" v-for="(el, index) in menuList" :key="`menu-${index}`">{{el}}</li>
                <!-- bottone -->
                  <li class="ms-5 "> <button class="Buttons">Free Quote</button></li>
              </ul>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name: 'HeaderBottom',
    data() {
        return {
            menuList: [
                'Home',
                'Rates',
                'Testimonials',
                'FAQ',
                'Blog',
                'Contact',
            ]
        }
    }
}
</script>

<style scoped lang="scss">
@import '@/components/variables.scss';

section {
    div{
        width: $sectionwidth;
        margin: 0 auto;

        .headerImage{
            img {
                width: 170px;
            }
        }

        .headerList{
            font-size: 15px;
            font-weight: 800;

            li:hover{
                color: $greenLima;
                cursor: pointer;
            }
            li:first-child{
                color: $greenLima;
            }

            
            
        }
    }
}
</style>
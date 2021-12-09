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
                  <li class="ms-4">Home</li>
                  <li class="ms-4">Rates</li>
                  <li class="ms-4">Testimonials</li>
                  <li class="ms-4">FAQ</li>
                  <li class="ms-4">Blog</li>
                  <li class="ms-4">Contact</li>
                  <li class="ms-5 "> <button class="headerButton">Free Quote</button></li>
              </ul>
          </div>
      </div>
  </section>
</template>

<script>
export default {
    name: 'HeaderBottom',
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
            font-size: 14px;
            font-weight: 800;

            li:hover{
                color: $greenLima;
                cursor: pointer;
            }

            .headerButton{
                background-color: $buttoncolor;
                padding: 5px 25px;
                border-radius: 25px;
                border: none;
                color: white;
                text-transform: uppercase;
                font-weight: 800;
                cursor: pointer;
            }
            
        }
    }
}
</style>
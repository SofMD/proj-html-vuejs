<template>
  <section>
      <!-- parte sopra -->
      <div class="footerTop">
          <div class="ftContainer d-flex justify-content-between">
              <!-- 1 -->
              <div >
                  <h4 class="fotTitle">about</h4>
                  <p class="mt-3">Lorem, ipsum dolor sit amet consectetur adipisicingostrum atque in optio fuga vero doloremque perferendis! Eum magni eligendi quidem deleniti?</p>
                  <img class="my-5" src="../assets/avada-movers-logo.png" alt="logo">
              </div>

              <!-- 2 -->
              <div>
                  <h4 class="fotTitle">Avada movers</h4>
                  <ul class="l-st">
                      <li><i class="fas fa-chevron-right"></i> Home</li>
                      <li><i class="fas fa-chevron-right"></i> Rates</li>
                      <li><i class="fas fa-chevron-right"></i> Testimonials</li>
                      <li><i class="fas fa-chevron-right"></i> Blog</li>
                      <li><i class="fas fa-chevron-right"></i> Free Quote</li>
                  </ul>
              </div>

              <!-- 3 -->
              <div >
                  <h4 class="fotTitle">recent posts</h4>
                  <ul class="l-st">
                      <li><i class="fas fa-chevron-right"></i> Heading Out To College?</li>
                      <li><i class="fas fa-chevron-right"></i> Moving Your Business?</li>
                      <li><i class="fas fa-chevron-right"></i> Outstanding Quality</li>
                      <li><i class="fas fa-chevron-right"></i> Cost of Moving</li>
                      <li><i class="fas fa-chevron-right"></i> Best Moving Tips</li>
                  </ul>
              </div>

          </div>
      </div>
      <!-- sotto -->
      <div class="footerbottom p-4">
          <div class="fbContainer">
              <div>&copy; Copyright 2021-2020  |  Avada Theme by ThemeFusion  |  All Rights Reserved  |  Powered by WordPress</div>

              <div class="mt-3">
                  <ul class="socialList l-st d-flex justify-content-center">
                       <li class="ms-3"><i class="fab fa-facebook-f"></i></li>
                       <li class="ms-3"><i class="fab fa-twitter"></i></li>
                       <li class="ms-3"><i class="fab fa-instagram"></i></li>
                       <li class="ms-3"><i class="fab fa-youtube"></i></li>
                  </ul>
               </div>


          </div>
      </div>
      
  </section>
</template>

<script>
export default {
    name: 'Footer',
}
</script>

<style scoped lang="scss">
@import '@/components/variables.scss';

section{

    color: $textblack;

    .fotTitle{
        font-weight: 900;
        text-transform: uppercase;
        font-size: 18px;
    }

    .footerTop{
        background-color: white;
        border-top: 20px solid $greenLima;
        padding: 50px;

        .ftContainer{
            width: 50%;
            margin-left: 15%;

            i {
               font-size: 10px;
            }

            p{
                width: 300px;
                font-size: 15px;
            }

            li{
                margin-top: 20px;
                font-size: 15px;
                font-weight: 500;
            }
            li:hover{
                color: $greenLima;
            }
            li:first-child{
                color: $greenLima;
            }
        }
    }

    .footerbottom{
        background-color: $greenLima;

        .fbContainer{
            width: 50%;
            margin: 0 auto;
            text-align: center;
            font-size: 14px;
            color: white;
        }

        i{
            font-size: 18px;
        }
    }
}
</style>
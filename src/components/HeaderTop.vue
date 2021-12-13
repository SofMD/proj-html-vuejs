<template>
  <section>
    <div class="p-2 d-flex justify-content-between">
      <!-- left -->
      <div>
        <span class="mx-2"><i class="fas fa-phone"></i> </span>
        Call us for a Free Quote: 1.800.555.6789
      </div>

      <!-- right -->
      <div>
        <ul class="socialList l-st d-flex justify-content-end">
          <li class="ms-3"><i class="fab fa-facebook-f"></i></li>
          <li class="ms-3"><i class="fab fa-twitter"></i></li>
          <li class="ms-3"><i class="fab fa-instagram"></i></li>
          <li class="ms-3"><i class="fab fa-youtube"></i></li>
        </ul>
      </div>
      
    </div>
  </section>
</template>

<script>
export default {
  name: 'HeaderTop',
}
</script>

<style scoped lang="scss">
@import '@/components/variables.scss';

section {
  background-color: $greenLima;
  color: white;
  font-size: 14px;

  div{
      width: $sectionwidth;
      margin: 0 auto;
      
      .socialList{
        li{
          cursor: pointer;
          transition: all .2s
        }
        li:hover{
          transform: scale(1.5);
        }
      }
  }
}

</style>
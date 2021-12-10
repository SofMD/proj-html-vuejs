<template>
  <section>
      <div class="GreenContainer p-4">
          <div class="upTitle">we remove the headache from moving</div>
          <h1>Move With Ease</h1>
          <p class="p-4">With our super simple service we can take you from getting a quote right through to being in your new homr with all of your belongings securely packed and safely delivered, even in the rooms of your choice.</p>
          <button class="Buttons m-2">get a free quote now</button>
      </div>
  </section>
</template>

<script>
export default {
    name: 'MoveEasySection',
}
</script>

<style scoped lang="scss">
@import '@/components/variables.scss';

section{
    margin-bottom: 60px;
    background-image: url('../assets/avada-movers-movewithease-background-new.jpg');    
    height: 730px;
    background-size: cover; 
    position: relative;


    .GreenContainer{
        text-align: center;
        width: 30%;
        color: white;
        background-color: $greenLima;
        border: 10px solid #5aa511;
        position: absolute;
        right: 15%;
        top: 50%;
        transform: translateY(-50%);

        .upTitle{
            font-size: 16px;
            font-weight: 900;
            text-transform: uppercase;
        }

        h1{
            width: 60%;
            margin: 0 auto;
            font-size: 40px;
            font-weight: 900;
            border-bottom: 1px solid greenyellow;
        }

        p{
            font-size: 15px;
        }

        .Buttons{
            font-size: 18px;
        }
    }
}

</style>
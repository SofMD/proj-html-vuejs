<template>
  <div>
       <!-- image -->
        <img :src="src" :alt="title">
        <!-- title -->
        <h3 class="mt-4" >{{title}}</h3>
        <!-- description -->
        <div class="description">{{description}}</div>
        <!-- button -->
        <button class="Buttons mt-3">{{button}}</button>
  </div>
</template>

<script>


export default {
    name: 'Cards',

    props: {
        src: String,
        title: String,
        description: String,
        button: String
    }
}
</script>

<style scoped lang="scss">

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
</style>
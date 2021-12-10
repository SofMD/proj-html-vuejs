<template>
<div>
    <!-- image -->
    <img :src="src" alt="title">
    <!-- title -->
    <h3 class="mt-4" >{{title}}</h3>
    <!-- description -->
    <div class="description">{{description}}</div>
</div>
</template>

<script>
export default {
    name:'TestimonialsCards',

    props: {
        src: String,
        title: String,
        description: String,
    }
}
</script>

<style scoped>

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

</style>
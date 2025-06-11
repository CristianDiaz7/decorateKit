<template>
    <div class="post-card">
        <h1>Titulo</h1>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ea modi eaque explicabo rerum eligendi, fuga cumque unde tenetur eos quis atque aut iusto quasi minima perferendis voluptas, veniam, est corporis?</p>    
        <postButton/>
    </div>
</template>

<script setup>
import postButton from './PostButton.vue';
</script>

<style scoped>
.post-card{
    border-radius: 15px;
    padding: 10px;
    margin: 5px;
    border: 1px solid #ccc;
}

</style>
<template>
    <h3>{{ counter }}</h3>
    <button @click="addCounter"> Incrementar</button>

</template>

<script>
import { defineComponent } from 'vue';
export default defineComponent({
    /* Propiedades*/
    name: "CounterOptcion",
    /* Metodos*/
    data(){
        let counter=0;
        return {counter}
    },
    methods: {
        addCounter(){
            this.counter++
        }
    }
})
</script>

<style>
</style>
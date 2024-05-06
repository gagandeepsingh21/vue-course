<script setup>
import {ref} from 'vue'
let count = ref(0);

const IncrementCounter = () => count.value++;
const DecrementCounter = () => count.value--;


</script>
<template>
    <h1>Count: {{ count }}</h1>
    <!-- can use v-on or @ -->
    <!--method 1 -->
    <!-- <button v-on:click="count++">Increment</button>
    <button v-on:click="count--">Decrement</button> -->
    <!--method 2 -->
    <button v-on:click="IncrementCounter">Increment</button>
    <button v-on:click="DecrementCounter">Decrement</button>
</template>
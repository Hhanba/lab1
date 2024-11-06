<template>
    <h1>{{ greeting }}</h1>
    <button @click="changeGreeting">Click de thay doi</button>
</template>

<script setup>
import {ref} from "vue";
const greeting = ref("Xin chao ban!");
const changeGreeting = ()=>{
    greeting.value = "hello world!";
}
</script>
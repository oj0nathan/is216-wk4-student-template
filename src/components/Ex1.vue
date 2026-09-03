<script setup>
    import { ref } from 'vue'

    const message = ref("Choose your favorite fruit: ")
    const fruits = ref(['apple', 'orange', 'peach'])
</script>

<template>
    {{ message }}

    <label for=""> <input type="radio" name="fruit"> {{ fruits[0] }} </label>
    <label for=""> <input type="radio" name="fruit"> {{ fruits[1] }} </label>
    <label for=""><input type="radio" name="fruit"> {{ fruits[2] }} </label>
</template>

<style scoped>
</style>

<script setup>
    import { ref } from 'vue'

    // Add code here
    // challenge: use array
    const message = ref("Choose your favourite fruit: ");
    const array = ref(['apple', 'orange', 'peach']);

</script>

<template>
    {{ message }}

    <label for=""> <input type="radio" name="fruit"> {{ array[0] }} </label>
    <label for=""> <input type="radio" name="fruit"> {{ array[1] }} </label>
    <label for=""><input type="radio" name="fruit"> {{ array[2] }} </label>

</template>

<style scoped>
</style>

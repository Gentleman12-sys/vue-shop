<script setup>
import { ref, watch } from 'vue'

const text = ref('')
watch(text, () => {
    console.log(text.value)
})
</script>


<template>
    <main>
        <input type="text" v-model="text">
    </main>
</template>
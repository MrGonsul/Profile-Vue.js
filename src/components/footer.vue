<script setup>
import { ref } from 'vue'
const title = ref('GitHub')
</script>

<template>
    <footer>
        <p>Learn more about me at <a target="_blank" href="https://github.com/MrGonsul/">{{ title }}</a></p>
    </footer>
</template>

<style scoped>
footer {
    margin-top: 35px;
    font-size: 0.8rem;
}

footer a {
    color: #40b883;
}
</style>

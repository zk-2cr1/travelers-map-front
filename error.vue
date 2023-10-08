<template>
    <div v-if="error.statusCode === 404">
        <hi>Error!</hi>
        <p>{{ error.message }}</p>
    </div>
</template>
<script setup>
const error = useError()
</script>
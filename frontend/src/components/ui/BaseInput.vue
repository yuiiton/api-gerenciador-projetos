<script setup lang="ts">

defineProps<{
    id: string
    tipo: string
    textoPlaceholder: string
}>()
</script>


<template>
    <input class="border rounded-sm border-gray-500 p-1.5 text-sm text-gray-300 bg-gray-800 focus:outline-none focus:ring-2 focus:ring-blue-500" :id='id' :type="tipo" :placeholder="textoPlaceholder" required>
</template>
<script setup lang="ts">
defineProps<{
    for: string
    titulo: string
}>()

</script>


<template>
    <label :for="for" class="font-black text-gray-400 text-sm">{{ titulo }}</label>
</template>
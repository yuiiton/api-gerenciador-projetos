<script setup lang="ts">
    import ProjectHeader from '@/components/project/ProjectHeader.vue';
    import ProjectForm from '@/components/project/ProjectForm.vue';
    import ProjectList from '@/components/project/ProjectList.vue';
</script>



<template>
    <header class="flex flex-col bg-linear-to-r from-blue-900 to-blue-600 justify-center items-center h-28 gap-3">
        <ProjectHeader/>
    </header>
     <main class="bg-gray-800 flex flex-col justify-center items-center p-5 gap-10">
        <ProjectForm/>
        <ProjectList/>
     </main>

</template>
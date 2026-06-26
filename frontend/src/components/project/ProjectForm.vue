<script setup lang="ts">
    import BaseInput from '../ui/BaseInput.vue';
    import BaseLabel from '../ui/BaseLabel.vue';
    import BaseSelect from '../ui/BaseSelect.vue';
    

</script>


<template>
    <form action="" class="bg-gray-700 p-7 w-175 rounded-sm border-t-4 border-blue-600 flex flex-col gap-2.5">
        <header>
            <h2 class="text-amber-50 text-2xl font-bold">Adicionar novo projeto</h2>
        </header>

        <section class="flex flex-col gap-1.5">
            <BaseLabel for="nome" titulo="NOME DO PROJETO"/>
            <BaseInput id="nome" tipo="text" textoPlaceholder="Digite o nome do projeto"/>
        </section>
        
        <section class="flex flex-col gap-1.5">
            <BaseLabel for="descricao" titulo="DESCRIÇÃO DO PROJETO"/>
            <BaseInput id="descricao" tipo="text" textoPlaceholder="Digite a descrição do projeto"/>
        </section>

        <section class="flex gap-20">

            <div class="flex flex-col">
                <BaseLabel for="prioridade" titulo="PRIORIDADE"/>
                <BaseSelect>
                    <option value="" disabled selected>Selecione uma prioridade</option>
                    <option value="low">Baixa</option>
                    <option value="medium">Média</option>
                    <option value="high">Alta</option>
                </BaseSelect>
            </div>

            <div class="flex flex-col">
                <BaseLabel for="status" titulo="STATUS"/>
                <BaseSelect>
                    <option value="" disabled selected>Selecione um status</option>
                </BaseSelect>
            </div>
        </section>


        <section>
            <button class=" w-full h-8 mt-5 rounded-sm bg-blue-500 text-amber-50 font-bold hover:bg-blue-600 hover:cursor-pointer">Salvar projeto</button>
        </section>
    </form>
</template>
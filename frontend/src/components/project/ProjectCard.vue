

<template>
    <section class="bg-gray-900 p-4 rounded w-60 flex flex-col gap-1">
        <h3 class="text-amber-50 text-lg font-bold">Data Migration</h3>
        <div class="flex gap-3">
            <div class="pl-1 pr-1 h-6 flex bg-red-600 justify-center rounded-lg text-amber-50 font-light">Alta</div>
            <div class="pl-1 pr-1 h-6 flex bg-orange-400 justify-center rounded-lg text-amber-50 font-light">Pendente</div>
        </div>
        <div>
            <p class="text-amber-50 text-md font-medium">Criado: 12/04/2026</p>
            <p class="text-amber-50 text-md font-medium">Concluído: 12/05/2026</p>
        </div>
        <div class="flex gap-3 w-full border-t-2">
            <button class=" w-1/2 h-6 mt-5 rounded-sm bg-blue-500 text-amber-50 font-bold hover:bg-blue-600 hover:cursor-pointer">Editar</button>
            <button class=" w-1/2 h-6 mt-5 rounded-sm bg-gray-600 text-red-400 font-bold hover:bg-gray-700 hover:cursor-pointer">Excluir</button>
        </div>
    </section>
</template>
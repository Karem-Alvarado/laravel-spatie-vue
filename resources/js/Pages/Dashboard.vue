<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';
import Welcome from '@/Components/Welcome.vue';
</script>

<template>
    <AppLayout title="Dashboard">
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Dashboard
            </h2>
        </template>
    <!-- <Welcome/> -->
        <div class="py-12">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <div class="bg-white overflow-hidden shadow-xl sm:rounded-lg">
                    <main class="">
                        <div class="grid lg:gap-8">
                            <div class="relative flex items-center gap-6 lg:items-end">
                                <div id="docs-card-content" class="flex items-start gap-6 lg:flex-col">
                                    <div class="p-6">
                                        <h2 class="text-xl font-semibold text-black dark:text-blue-600">Instalación Laravel-vue-inertia v11.25</h2>
                                            <p class="text-sm/relaxed"> 
                                                composer create-project laravel/laravel nombre-proyecto
                                            </p>
                                            <hr class="p-2">
                                        <h2 class="text-xl font-semibold text-blue-500 dark:text-blue-600">Agregar nueva tabla en Laravel</h2>
                                            <p class="text-sm/relaxed"> 
                                                php artisan make:migration create_nombre_table
                                            </p>
                                            <hr class="p-2">
                                        <h2 class="text-xl font-semibold text-blue-500 dark:text-blue-600">WHERE IN para arrary</h2>
                                            <p class="text-sm/relaxed"> 
                                                $sectionIds = $request->input('section_id', []); <br>
                                                $listStudents = StudentAssistance::whereIn('paralelo', $sectionIds)->get();
                                            </p>
                                         <hr class="p-2">
                                        <h2 class="text-xl font-semibold text-blue-500 dark:text-blue-600">Crear un controlador</h2>
                                            <p class="text-sm/relaxed">php artisan make:controller nombre-controlador</p>   
                                    </div>
                                </div>
                            </div>
                        </div>
                    </main>
                </div>
            </div>
        </div>
    </AppLayout>
</template>

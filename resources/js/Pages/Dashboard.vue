<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';
import Welcome from '@/Components/Welcome.vue';
import { BeakerIcon } from '@heroicons/vue/24/solid';
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
                                        <h2 class="text-xl font-semibold text-black dark:text-blue-600">Instalación Laravel-vue-inertia v11.25 https://tailwindcss.com/docs/fill</h2>
                                            <p class="text-sm/relaxed"> 
                                                composer create-project laravel/laravel nombre-proyecto
                                            </p>
                                            <hr class="p-2">
                                        <h2 class="text-xl font-semibold text-blue-500 dark:text-blue-600">Agregar nueva tabla en Laravel</h2>
                                            <p class="text-sm/relaxed"> 
                                                php artisan make:migration create_attendance_dates_table
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
                                            <hr class="p-2">
                                        <h2 class="text-xl font-semibold text-blue-500 dark:text-blue-600">Crear campos adicionales a una tabla especifica</h2>
                                            <p class="text-sm/relaxed">php artisan make:migration add_access_ci_student_to_supports_table --table=supports</p>
                                        <hr class="p-2">
                                        <h2 class="text-xl font-semibold text-blue-500 dark:text-blue-600">Crear archivo para importacion</h2>
                                        <i class="chevron-double-right"></i><p class="">NombreDeTuImportacion: El nombre de tu clase de importación. <br> --model=NombreDelModelo: (Opcional) Relaciona la importación con un modelo existente.</p>
                                            <p class="text-sm/relaxed">php artisan make:import NombreDeTuImportacion --model=NombreDelModelo</p>
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

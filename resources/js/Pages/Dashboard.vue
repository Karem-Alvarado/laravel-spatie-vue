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
    <Welcome/>
        <div class="py-12">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <div class="bg-white overflow-hidden shadow-xl sm:rounded-lg">
                    <main class="mt-6">
                        <div class="grid gap-6 lg:grid-cols-2 lg:gap-8">
                            <div class="relative flex items-center gap-6 lg:items-end">
                                <div id="docs-card-content" class="flex items-start gap-6 lg:flex-col">
                                    <div class="flex flex-col items-start gap-6 overflow-hidden rounded-lg bg-white p-6 shadow-[0px_14px_34px_0px_rgba(0,0,0,0.08)] ring-1 ring-white/[0.05] transition duration-300 hover:text-black/70 hover:ring-black/20 focus:outline-none focus-visible:ring-[#FF2D20] md:row-span-3 lg:p-10 lg:pb-10 dark:bg-zinc-900 dark:ring-zinc-800 dark:hover:text-white/70 dark:hover:ring-zinc-700 dark:focus-visible:ring-[#FF2D20]">
                                        <div class="relative flex items-center gap-6 lg:items-end">
                                            <div id="docs-card-content" class="flex items-start gap-6 lg:flex-col">
                                                <div class="pt-3 sm:pt-5 lg:pt-0">
                                                    <!-- size-6 shrink-0 stroke-[#FF2D20]" -->
                                                    <h2 class="text-xl font-semibold text-black dark:text-white">Instalación Laravel-vue-inertia v11.25</h2>
                                                    <p class="mt-4 text-sm/relaxed">
                                                        composer create-project laravel/laravel nombre-proyecto
                                                    </p>
                                                    <h2 class="text-xl font-semibold text-black dark:text-white">Importante poner Mayuscula la primera letra del archivo o carpeta en Vue</h2>
                                                    <p class="mt-4 text-sm/relaxed">
                                                        Ejemplo: Menu.vue
                                                    </p>

                                                </div>
                                            </div>
                                            <!-- <svg class="size-6 shrink-0 stroke-[#FF2D20]" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5"><path stroke-linecap="round" stroke-linejoin="round" d="M4.5 12h15m0 0l-6.75-6.75M19.5 12l-6.75 6.75"/></svg> -->
                                        </div>
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

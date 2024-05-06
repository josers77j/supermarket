<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';
import { Head } from '@inertiajs/vue3';
</script>

<template>
    <Head title="Dashboard"></Head>
    <AppLayout title="Dashboard">
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Aca la info del plebe
            </h2>
        </template>

        <div class="py-4">
            <h1>Welcome Plebeyo</h1>
        </div>
    </AppLayout>
</template>

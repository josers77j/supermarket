<script setup>
import AdminLayout from '@/Layouts/AdminLayout.vue';
import Welcome from '@/Components/Welcome.vue';
import { Head } from '@inertiajs/vue3';
</script>

<template>
    <Head title="Admin - Dashboard"></Head>
    <AdminLayout title="Dashboard">
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Aca la info del admin
            </h2>
        </template>

        <div class="py-4">
            <h1>Welcome Admin </h1>
            

        </div>
    </AdminLayout>
</template>

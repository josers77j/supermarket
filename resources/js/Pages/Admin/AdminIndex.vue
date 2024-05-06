<script setup>
import AdminLayout from '@/Layouts/AdminLayout.vue';
import Welcome from '@/Components/Welcome.vue';
</script>

<template>
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

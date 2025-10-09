<script setup lang="ts">
const items = ref(['G.Mamidada', 'Bikkavolu', 'Komaripalem', 'Pedapudi', 'Ramachandrapuram', 'Rayavarm'])
const value = ref('G.Mamidada')
</script>

<template>
    <USelectMenu v-model="value" icon="i-lucide-map-pin" size="md" :items="items" class="w-48" />
</template>

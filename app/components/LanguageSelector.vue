<script setup lang="ts">
const items = ref(['Eng', 'Tel',])
</script>

<template>
    <UPopover :content="{ side: 'bottom', align: 'start' }">
        <UButton icon="i-lucide-languages" color="neutral" variant="subtle" />

        <template #content>
            <URadioGroup size="xs" indicator="hidden" variant="table" default-value="Eng" :items="items" />
        </template>
    </UPopover>
</template>

<template>
    <q-chip
        outline
        class="no-border"
        color="orange-4"
        text-color="white"
        dense
        icon="star"
    >
        <slot />
    </q-chip>
</template>

<script>
export default {
    name: 'Rating',
};
</script>

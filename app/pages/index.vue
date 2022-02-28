<template>
    <div>
        {{ auth.user }}
    </div>
</template>

<script setup lang="ts">
    import { useAuthStore } from '~/store';

    const auth = useAuthStore();
</script>

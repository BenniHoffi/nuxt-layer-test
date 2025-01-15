<template>
    <UContainer>
        <div class="flex justify-between items-center py-4">
            <UHorizontalNavigation :links="links" />
            <ColorModeSwitch />
        </div>
        <slot />
    </UContainer>
</template>
<script setup lang="ts">
    const links  = useLinks()
</script>
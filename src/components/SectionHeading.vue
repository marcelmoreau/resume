<script setup>

import IconBase from "./icons/IconBase.vue";

const props = defineProps({
    iconName: String,
    label: String,
});
</script>

<template>
    <span class="section__headingAsset">
        <slot name="icon"></slot>
    </span>
    <span class="section__headingLabel">
        <slot>
            {{ label }}
        </slot>
    </span>
</template>

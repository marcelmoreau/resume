<script setup>
import IconLayers from "./IconLayers.vue";
import IconPencil from "./IconPencil.vue";
import IconWrench from "./IconWrench.vue";

const props = defineProps({
    viewBox: {
        type: String,
        default: "0 0 16 16",
    },
    width: {
        type: [Number, String],
        default: "16",
    },
    height: {
        type: [Number, String],
        default: "16",
    },
    iconColor: {
        type: String,
        default: "currentColor",
    },
});


</script>

<template>
    <svg xmlns="http://www.w3.org/2000/svg"
        :width="width"
        :height="height"
        :viewBox="viewBox"
    >
        <g :fill="iconColor">
            <slot  />
        </g>
    </svg>
</template>

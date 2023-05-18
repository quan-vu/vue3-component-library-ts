<template>
    <h1>{{ text }}</h1>
</template>
  
<script lang="ts">
import { defineComponent, PropType } from 'vue';

export default defineComponent({
    props: {
        text: {
            type: String as PropType<string>,
            required: true,
        },
    },
});
</script>
  
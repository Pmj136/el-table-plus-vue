<template>
   <div :class="['crud-table-header',props.inline && 'crud-table-header--inline']">
      <slot />
   </div>
</template>

<script setup lang="ts">
const props = defineProps({
   inline: Boolean
});
</script>

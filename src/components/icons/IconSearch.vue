
<template>
  <svg
    xmlns="http://www.w3.org/2000/svg"
    role="img"
    :width="width"
    :height="height"
    fill="none"
    stroke="currentColor"
    stroke-linecap="round"
    stroke-linejoin="round"
    stroke-width="2"
    preserveAspectRatio="xMidYMid meet"
    viewBox="0 0 24 24"
  ><path d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
</template>

<script lang="ts">
export default defineComponent({
  name: 'IconSearch',
  props: {
    width: {
      type: [Number, String],
      default: 18,
    },
    height: {
      type: [Number, String],
      default: 18,
    },
  },
})
</script>

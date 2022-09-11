<template>
  <component :is="tag">
    <slot>This is the heading!</slot>
  </component>
</template>

<script>
export default {
  name: 'TheHeading',
  props: {
    tag: {
      type: String,
      default: 'h2',
    },
  },
}
</script>

<script setup>
import { TwoHeadings } from 'connection'
import { TheHeading } from 'core'
</script>

<template>
  <TheHeading tag='h1'>Example of pnpm monorepo</TheHeading>
  
  <section>
    <p>This is from <strong>connection/two-headings</strong></p>
    <TwoHeadings />
  </section>

  <section>
    <p>This is from <strong>core/the-heading</strong></p>
    <TheHeading />
  </section>

</template>

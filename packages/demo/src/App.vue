<script setup>
import { TwoHeadings } from 'marketplace'
import { TheHeading } from 'base'
</script>

<template>
  <TheHeading tag='h1'>Example of pnpm monorepo</TheHeading>
  
  <section>
    <p>This is from <strong>marketplace/two-headings</strong></p>
    <TwoHeadings />
  </section>

  <section>
    <p>This is from <strong>base/the-heading</strong></p>
    <TheHeading />
  </section>

</template>

<script setup lang="ts">
import type { Image } from '~~/types'

defineProps<{
  image: Image
  alt?: string
}>()
</script>

<template>
  <img :src="getStrapiUrl(image)" :alt="alt">
</template>


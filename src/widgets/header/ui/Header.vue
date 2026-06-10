<script setup lang="ts">
import { Logo } from '@/shared/ui/logo'
</script>

<template>
  <header class="header">
    <Logo />
  </header>
</template>

<style scoped>
.header {
  height: 72px;

  display: flex;
  align-items: center;

  padding-inline: 32px;
}
</style>
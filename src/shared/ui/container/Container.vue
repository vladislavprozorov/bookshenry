<template>
  <div class="container">
    <slot />
  </div>
</template>

<style scoped>
.container {
  width: 100%;

  max-width: var(--container-max-width);

  margin-inline: auto;

  padding-inline: var(--container-padding);
}
</style>
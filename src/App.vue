<script setup>

  import { RouterLink, RouterView } from 'vue-router'

  import { useColorMode } from '@vueuse/core';

  const mode = useColorMode()
  mode.value = 'dark'

</script>

<template>
  <RouterView />
</template>

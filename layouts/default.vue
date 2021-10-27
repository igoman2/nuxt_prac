<template>
  <div>
    <AppHeader />
    <Nuxt />
  </div>
</template>

<script>
import AppHeader from '@/components/AppHeader.vue'

export default {
  components: { AppHeader },
}
</script>
<style>
@import '@/assets/css/reset.css';
</style>

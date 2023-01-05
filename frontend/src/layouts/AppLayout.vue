<template>
  <div class="app_layout">
    <app-layout-header/>
    <slot/>
  </div>
</template>

<script>
import AppLayoutHeader from '@/layouts/AppLayoutHeader.vue'
export default {
  name: 'AppLayout',
  components: {
    AppLayoutHeader
  }
}
</script>

<style scoped>

</style>

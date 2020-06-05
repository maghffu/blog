<template>
  <v-app>
    <core-app-bar />
    <nuxt />
  </v-app>
</template>

<script>
  export default {
    components: {
      CoreAppBar: () => import('@/components/core/AppBar')
    },
  }
</script>

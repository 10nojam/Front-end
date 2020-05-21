<template>
  <v-app>
    <home-system-bar />

    <home-app-bar />

    <home-view />

    <home-footer />

    <home-settings />
  </v-app>
</template>

<script>
  export default {
    name: 'HomeLayout',

    components: {
      HomeAppBar: () => import('@/layouts/home/AppBar'),
      HomeView: () => import('@/layouts/home/View'),
      HomeFooter: () => import('@/layouts/home/Footer')
    },
  }
</script>

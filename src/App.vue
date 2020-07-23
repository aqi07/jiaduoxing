<template>
  <v-app>

    <v-main>
      <router-link to="/home"> 首页 </router-link>
      <router-link to="/about"> 关于 </router-link>
      <router-view></router-view>
    </v-main>

  </v-app>
</template>

<script>

export default {
  name: 'App',
  data: () => ({
    //
  }),
};
</script>

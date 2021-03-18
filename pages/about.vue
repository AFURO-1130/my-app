<template>
  <v-app>
    <div>
      <nuxt-link to="/">ホームへ</nuxt-link>

      <home />
    </div>
  </v-app>
</template>
<script>
import Home from "~/components/home.vue";
export default {
  components: {
    Home,
  },
};
</script>

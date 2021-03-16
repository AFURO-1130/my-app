<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="8" md="6">
      <v-container>
        <div class="text-center"></div>
        <v-flex d-flex flex-column>
          <nuxt-link to="/about" class="font-weight-black font-size"
            >aboutへ</nuxt-link
          >
          <nuxt-link to="/works" class="font-weight-black font-size"
            >worksへ</nuxt-link
          >
          <nuxt-link to="/contact" class="font-weight-black font-size"
            >contactへ</nuxt-link
          >
        </v-flex>
      </v-container>
    </v-col>
  </v-row>
</template>
<style>
.font-size {
  font-size: 2em;
  margin: 10%;
  text-decoration: none;
}
.font-size:hover{
  opacity: 0.7;
}
</style>


<script>
export default {
  //  layout: 'home',
};
</script>


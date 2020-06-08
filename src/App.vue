<template>
  <div>
    <v-app>
      <Header></Header>
      <main>
          <Home></Home>
      </main>
    </v-app>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Header from "./components/Header.vue";
import Home from "./components/Home.vue"

export default Vue.extend({
  name: "App",

  components: {
    Header,
    Home
  },

  data: () => ({
    //
  })
});
</script>

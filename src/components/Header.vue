<template>
    <div>
    <v-toolbar
      dense
      dark
    >
      <v-toolbar-title>Александра Грахова</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-toolbar-items><v-btn text>Опыт работы</v-btn></v-toolbar-items>

      <v-toolbar-items><v-btn text>Профессиональные навыки</v-btn></v-toolbar-items>

      <v-toolbar-items><v-btn text>Портфолио</v-btn></v-toolbar-items>

    </v-toolbar>
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class LobbyList extends Vue {
    
}
</script>
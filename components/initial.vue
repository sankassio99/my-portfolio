<template>
  <v-row justify="center" align="center" class="row-main">
    <v-col sm="8" md="6" align="center" justify="center">
      <v-avatar color="blue darken-2" size="128">
        <v-icon dark> mdi-account-circle </v-icon>
      </v-avatar>
      <h1>Kássio Santana</h1>
      <p>
        Hello, i'm a brasilian Full Stack Web Software Engineer. Welcome to my
        new portfolio!
      </p>
      <v-spacer></v-spacer>
      <a href="#about-me-section"><v-icon class="more-icon" large> mdi-chevron-down </v-icon></a>
    </v-col>
    <effects></effects>
  </v-row>
</template>

<script>
import effects from './shared/effects.vue';
export default {
  components: { effects },};
</script>

<style scoped>
    .more-icon {
        cursor: pointer;
        /* position: absolute;
        top: 90vh; */
    }
    .row-main {
        min-height: 92vh;
    }
</style>
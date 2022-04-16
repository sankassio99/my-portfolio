<template>
  <v-row
    justify="center"
    align="center"
    class="row-main"
    id="about-me-section"
  >
    <v-row class="d-flex flex-wrap">
      <v-col cols="12" sm="6" align="center">

        <v-sheet class="card-function mb-3" color="d-flex" max-width="400" align="start" rounded outlined>
          <v-card-title align="center">
            <v-icon large> mdi-devices </v-icon>
          </v-card-title>
          <v-col cols="8">
            <v-card-title>{{teste}}</v-card-title>
            <v-card-subtitle>76 projects</v-card-subtitle>
          </v-col>
        </v-sheet>
        <v-sheet class="card-function mb-3" color="d-flex" max-width="400" align="start" rounded outlined>
          <v-card-title align="center">
            <v-icon large> mdi-laptop </v-icon>
          </v-card-title>
          <v-col cols="8">
            <v-card-title>{{teste}}</v-card-title>
            <v-card-subtitle>76 projects</v-card-subtitle>
          </v-col>
        </v-sheet>
        <v-sheet class="card-function mb-3" color="d-flex" max-width="400" align="start" rounded outlined>
          <v-card-title align="center">
            <v-icon large> mdi-laptop </v-icon>
          </v-card-title>
          <v-col cols="8">
            <v-card-title>{{teste}}</v-card-title>
            <v-card-subtitle>76 projects</v-card-subtitle>
          </v-col>
        </v-sheet>

        <!-- <v-img
            class="img-aboute-me"
            src="https://cdn.vuetifyjs.com/images/parallax/material.jpg"
            aspect-ratio="1.7"
        ></v-img> -->
      </v-col>

      <v-col cols="12" sm="6" class="pa-5">
        <v-row class="mb-5">
          <h1>What do i help?</h1>
          <p>
            Ao contrário do que se acredita, Lorem Ipsum não é simplesmente um
            texto randômico. Com mais de 2000 anos, suas raízes podem ser
            encontradas em uma obra de literatura latina clássica datada de 45 AC.
            Richard McClintock, um professor de latim do Hampden-Sydney College na
            Virginia
          </p>
        </v-row>

        <v-row class="mb-10">
          <v-col>
            <h1>9+</h1>
            <span>Projects Completed</span>
          </v-col>
          <v-col>
            <h1>10000+</h1>
            <span>Happy Clients</span>
          </v-col>
        </v-row>

        <v-row>
          <v-row cols="4" sm="2" justify="center">
            <div class="pa-2">
            <v-icon large> mdi-facebook </v-icon>
            </div>
            <div class="pa-2">
            <v-icon large> mdi-whatsapp </v-icon>
            </div>
            <div class="pa-2">
            <v-icon large> mdi-instagram </v-icon>
            </div>
          </v-row>
        </v-row>
      </v-col>
    </v-row>
  </v-row>
</template>

<script>
export default {
  name: "AboutMe",
  data(){
    return {
      teste: "Front-End Develop"
    }
  }
};
</script>

<style scoped>
.row-main {
  height: 90vh;
}
.img-aboute-me {
  border-radius: 10px;
}
</style>
<template>
  <div class="education-section">
        <h1>Education</h1>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maiores, cumque facilis ad, eveniet perspiciatis ipsam dolore quia corporis necessitatibus repellat aspernatur ducimus rem. Libero tempora dignissimos totam, minima reprehenderit eius.</p>
        <v-carousel hide-delimiters height="300" class="">
            <v-carousel-item class="carousel-page">
                <v-sheet class="education-card mr-4"
                color="white"
                elevation="10"
                height="200"
                width="500"
                >
                </v-sheet>
                <v-sheet class="education-card"
                color="white"
                elevation="10"
                height="200"
                width="500"
                >
                </v-sheet>
            </v-carousel-item>
            <v-carousel-item class="carousel-page">
                <v-sheet class="education-card mr-4"
                color="white"
                elevation="10"
                height="200"
                width="500"
                >
                </v-sheet>
                <v-sheet class="education-card"
                color="white"
                elevation="10"
                height="200"
                width="500"
                >
                </v-sheet>
            </v-carousel-item>
        </v-carousel>
  </div>
</template>

<script>
export default {
    data(){
        return {
            item: 10
        }
    }
}
</script>

<style>
    .education-section{
        display: flex;
        flex-direction: column;
        justify-content: center;
        height: 100vh;
    }
    .education-card {
        border-radius: 10px;
    }
    .carousel-page {
        display: flex;
    }
    .v-responsive__content {
        display: flex;
        justify-content: center;
        align-items: center;
    }
</style>
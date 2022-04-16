<template>
    <v-row justify="center" align="center">
        <h1>My Work Experience</h1>
        <timeline-experience></timeline-experience>
    </v-row>
</template>

<script>
import timelineExperience from "./shared/timeline-experience.vue";

export default{
    components: { timelineExperience }, 
}

</script>

<style>

</style>
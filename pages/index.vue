<template>
  <v-col class="main-index">
    <initial></initial>
    <about-me></about-me>
    <experience></experience>
    <education></education>
  </v-col>
</template>

<script>
import AboutMe from '~/components/about-me.vue';
import Education from '~/components/education.vue';
import Expierence from '~/components/experience.vue';
import Initial from '~/components/initial.vue';
import Effects from '~/components/shared/effects.vue';
export default {
  name: 'IndexPage',
  components: {Initial, AboutMe, Expierence, Education, Effects},
  data(){
    return {

    }
  }
}
</script>
<style scoped>
  .main-index {
    scroll-behavior: smooth;
  }
</style>
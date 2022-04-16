
<template>
  <div>
        <v-timeline>
            <v-timeline-item
            v-for="(year, i) in years"
            :key="i"
            :color="year.color"
            small
            >
            <template v-slot:opposite>
                <span
                :class="`headline font-weight-bold ${year.color}--text`"
                v-text="year.year"
                ></span>
            </template>
            <div class="py-4">
                <h2 :class="`headline font-weight-light  ${year.color}--text`">
                {{year.title}}
                </h2>
                <span>{{year.occupation}}</span>
                <div class="mt-4">
                    {{year.desc}}
                </div>
            </div>
            </v-timeline-item>
        </v-timeline>
  </div>
</template>

<script>
export default {
    name: "timelineExperience",
    data: () => ({
      years: [
        {
            title: 'Ministerio Público Tocantins - MPE',
            occupation: 'Trainee',
            color: 'grey',
            year: '2021',
            desc: "Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit, an vim zril disputando voluptatibus, vix an salutandi sententiae."
        },
        {
            title: 'Niceplanet',
            occupation: 'Front-end Engineer',
            color: 'cyan',
            year: '2021',
            desc: "Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit, an vim zril disputando voluptatibus, vix an salutandi sententiae."},
        {
            title: 'Siteware Solutions',
            occupation: 'Full-stack Software Engineer',
            color: 'red',
            year: '2022',
            desc: "Lorem ipsum dolor sit amet, no nam oblique veritus. Commune scaevola imperdiet nec ut, sed euismod convenire principes at. Est et nobis iisque percipit, an vim zril disputando voluptatibus, vix an salutandi sententiae."},
      ],
    }),
}
</script>

<style>

</style>
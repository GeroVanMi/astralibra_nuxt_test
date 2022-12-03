<template>
  <Section>
    <SubHeader>Education & Work</SubHeader>
    <div v-for="date in dates" class="mt-3">
      <div class="text-white font-bold">{{ date.date }}</div>
      <div class="text-white" v-html="date.text"></div>
    </div>
  </Section>
</template>

<script>
import SubHeader from "../SubHeader";
import Section from "../Section";

export default {
  name: "Bio",
  components: {Section, SubHeader},
  data() {
    return {
      dates: [
        {
          date: "2021-present",
          text: "Studying (Bachelor's Degree) Data Science at the Zurich University for Applied Sciences."
        },
        {date: "2021 (Jan-May)", text: "Military Basic Training in the Swiss Armed Forces in Radio Reconnaissance."},
        {date: "2019-2021", text: "Worked 2 Years for <a href='https://www.andeo.ch'>Andeo AG</a> as a Web Developer."},
        {
          date: "2015-2019",
          text: "Software Engineering Trade School at the \"Informatikmittelschule Kantonsschule Büelrain\" in Winterthur."
        },
      ]
    }
  }
}
</script>

<style scoped>

</style>

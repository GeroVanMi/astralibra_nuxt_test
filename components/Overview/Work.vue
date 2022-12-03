<template>
  <Section>
    <SubHeader>About Me</SubHeader>
    <p class="indented text-white mt-3">
      I am a developer living on my own in Winterthur, Switzerland and like programming things that serve a purpose /
      solve some problem. The challenge of solving real-world issues with code, data and hardware excites me.
    </p>
    <p class="indented text-white">
      In my free time I often play games, though I would like to read more. I also like to go to my school's library
      when studying for my data science degree.
    </p>
    <p class="indented text-white">
      If you'd like, you can challenge me to a chess game or ask me any questions via
      <a href="mailto:gerome.meyer@icloud.com">&#128231;gerome.meyer@icloud.com</a>.
    </p>
  </Section>
</template>

<script>
import SubHeader from "../SubHeader";
import Section from "../Section";

export default {
  name: "Work",
  components: {Section, SubHeader}
}
</script>

<style scoped>

</style>

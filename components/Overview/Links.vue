<template>
  <Section>
    <SubHeader>Links</SubHeader>
    <ul>
      <li>
        <Github/>
      </li>
    </ul>
  </Section>
</template>

<script>
import SubHeader from "../SubHeader";
import Github from "../icons/Github";
import Section from "../Section";
export default {
  name: "Links",
  components: {Section, Github, SubHeader}
}
</script>

<style scoped>

</style>

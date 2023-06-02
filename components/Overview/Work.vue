<template>
  <Section>
    <SubHeader>About Me</SubHeader>
    <p class="indented text-white mt-3">
      I am a developer living in Winterthur, Switzerland 🇨🇭. I like to loose
      myself in solving obscure problems. When I'm not doing that, then I'm
      likely trying to learn about something new.
    </p>
    <p class="indented text-white">
      In my free time I watch Anime, read and tend to plants. I am looking to
      write more, since it seems to be a good way of retaining information!
    </p>
    <br />
    <p class="indented text-white">
      If you'd like, you can challenge me to a chess game or ask me any
      questions via
      <a href="mailto:gerome.meyer@icloud.com">gerome.meyer@icloud.com</a>.
    </p>
  </Section>
</template>

<script>
import SubHeader from "../SubHeader";
import Section from "../Section";

export default {
  name: "Work",
  components: { Section, SubHeader },
};
</script>

<style scoped></style>

<template>
  <article class="container mx-auto px-5">
    <Hello/>
    <Title/>
    <Work/>
    <Bio/>
  </article>
</template>

<script>
import Hello from "./Overview/Hello";
import Title from "./Overview/Title";
import Work from "./Overview/Work";
import Bio from "./Overview/Bio";
import Links from "./Overview/Links";

export default {
  name: "Overview",
  components: {Links, Bio, Work, Title, Hello}
}
</script>

<style scoped>

.container {
  max-width: 518px;
}
</style>

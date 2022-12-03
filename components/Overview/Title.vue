<template>
  <Section class="flex justify-between">
    <div>
      <h1 class="text-white text-large md:text-5xl font-bold">Gérôme Meyer</h1>
      <h2 class="text-white text-sm">Web Developer, Statistician and (sometimes) Gardner</h2>
    </div>
    <div>
      <img class="mt-3 md:mt-1 w-16 md:w-19 rounded-full border-2" :src="require('@/static/head_icon.jpg')" alt="Picture of me"/>
    </div>
  </Section>
</template>

<script>
import Section from "../Section";
export default {
  name: "Title",
  components: {Section}
}
</script>

<style scoped>

</style>

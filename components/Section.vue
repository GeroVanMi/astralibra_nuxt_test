<template>
  <div class="mt-8 section">
    <slot></slot>
  </div>
</template>

<script>
export default {
  name: "Section",
  mounted() {
    // TODO: This isn't optimal yet. Every section that is mounted will loop through every other section and make
    // TODO: it visible if it isn't yet. Instead each section should just make itself visible and nothing else.
    const sections = document.getElementsByClassName('section');
    for (const section of sections) {
      // If a section isn't visible yet, when it is mounted, then make it visible.
      if (section.className.indexOf('visible') === -1)
        section.className += ' visible';
    }
  }
}
</script>

<style scoped>

</style>

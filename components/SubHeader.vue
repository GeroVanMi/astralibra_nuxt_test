<template>
  <h3 class="text-white font-bold ">
    <slot></slot>

  </h3>
</template>

<script>
export default {
  name: "SubHeader"
}
</script>

<style scoped>
h3 {
  text-decoration: underline;
  text-underline-offset: 6px;
  text-decoration-color: #525252;
  text-decoration-thickness: 4px;
}
</style>

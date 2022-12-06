<template>
  <main class="container mx-auto">
    <Navigation/>
    <Overview/>
    <Footer/>
  </main>
</template>

<script>
import Navigation from "../components/Navigation";
import Overview from "../components/Overview";
import Footer from "../components/Footer";
export default {
  name: 'IndexPage',
  components: {Footer, Overview, Navigation},
}
</script>

<style lang="css">
  body {
    background: #252533;
    min-height: 100vh;
  }

  .indented {
    text-indent: 1em;
    text-align: justify;
  }

  a {
    color: #aaaaaa;
    text-decoration: underline;
    text-decoration-color: transparent;
    text-underline-offset: 5px;
    transition: color 500ms, text-decoration-color 500ms;
  }

  a:hover {
    color: #00D9FFFF;
    text-decoration-color: #00D9FFFF;
  }

  .section {
    opacity: 0;
    transition: opacity 500ms, transform 600ms;
    transform: translateY(15px);
  }

  .visible {
    opacity: 1;
    transform: translateY(0);
  }
</style>

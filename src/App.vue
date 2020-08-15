<template>
  <div id="app">
    <Header />
    <Article />
    <Footer />
  </div>
</template>

<script>
import Article from "./components/Article/Article.vue";
import Header from "./components/Header/Header.vue";
import Footer from "./components/Footer/Footer.vue";
import "./reset.css";
export default {
  name: "App",
  components: {
    Header,
    Article,
    Footer
  }
};
</script>

<style>

</style>

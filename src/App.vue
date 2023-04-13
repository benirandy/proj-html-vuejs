<template>
  <div id="app">
    <div class="back">
      <Header />
      <Jumbo />
      <Recipes />
      <Collection />
      <Farm />
      <NewsLetter />
      <Footer/>
      <Sfooter />
    </div>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Jumbo from "./components/Jumbo.vue";
import Recipes from "./components/Recipes.vue";
import Collection from "./components/Collection.vue";
import Farm from "./components/Farm.vue";
import NewsLetter from "./components/NewsLetter.vue";
import Footer from "./components/Footer.vue";
import Sfooter from "./components/Sfooter.vue";
export default {
  name: "App",
  components: {
    Header,
    Jumbo,
    Recipes,
    Collection,
    Farm,
    NewsLetter,
    Footer,
    Sfooter,
  },
};
</script>

<style lang="scss">
@import url("https://use.fontawesome.com/releases/v5.7.1/css/all.css");
body,
html {
  margin: 0;
  padding: 0;
}
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
.back {
  background-color: #f6f7f1;
}
</style>
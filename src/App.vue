<template>
  <HomePage
    data="Rohail Ramesh"
    message="This is the homepage to my website."
  />
  <ContactPage username="ec21488" />
</template>

<script>
import HomePage from "./components/HomePage.vue";
import ContactPage from "./components/ContactPage.vue";

export default {
  name: "App",
  components: {
    HomePage,
    ContactPage,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

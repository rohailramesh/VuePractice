<template>
  <div>
    <h1>Hello from the home component</h1>
    <h2>{{ data }}</h2>
    <p>{{ message }}</p>
    <button v-on:click="homePageFunc">Home Page</button>
    <button v-on:click="alert('You clicked the alert button')">Alert</button>
  </div>
</template>

<script>
export default {
  name: "HomePage",
  props: { data: String, message: String },
  methods: {
    homePageFunc() {
      console.log("This is the homePageFunc");
    },
    alert(data) {
      window.alert(data);
    },
  },
};
</script>

<style>
button {
  display: block;
  margin-bottom: 10px;
  justify-content: center;
  justify-items: center;
  align-content: center;
  align-items: center;
  display: flex;
}
</style>

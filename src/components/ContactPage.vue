<template>
  <div>
    <h1>Contact Page</h1>
    <p>Please contact me @ {{ username }}</p>
  </div>
</template>

<script>
export default {
  name: "ContactPage",
  props: { username: String },
  methods: {
    ContactPageFunction() {
      console.log("This is a contact page function");
    },
  },
};
</script>

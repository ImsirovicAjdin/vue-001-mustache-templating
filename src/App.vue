<template>
  <div id="app">
    <MustacheTemplating msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import MustacheTemplating from "./components/MustacheTemplating.vue";

export default {
  name: "App",
  components: {
    MustacheTemplating
  }
};
</script>

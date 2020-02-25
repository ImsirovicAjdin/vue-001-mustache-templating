<template>
  <div class="hello">
    <h1>{{ heading1 }}</h1>
    <h2>Just an {{ heading2 }}</h2>
    <p>{{ paragraph1 }} is fun</p>
  </div>
</template>

<script>
export default {
  name: "MustacheTemplating",
  props: {
    msg: String
  },
  data() {
    return {
      heading1: "Just an h1 heading here",
      heading2: "heading 2 here",
      paragraph1: "Vue JS"
    };
  }
  // 'data' property must be a function so this won't work:
  // data: {
  //   heading1: "Just an h1 heading here",
  //   heading2: "heading 2 here",
  //   paragraph1: "Vue JS"
  // }
};
</script>

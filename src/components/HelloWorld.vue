<template>
  <div class="hello">{{ number }}</div>
</template>

<script>
import {  } from "";
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  data() {
    return {
      number: 10,
    };
  },
  mounted() {},
  methods: {
    compute(value) {
      return value
    },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>

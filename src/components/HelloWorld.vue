<template>
  <div class="hello">{{ number }}</div>
</template>

<script>
import { multiply3 } from "../publicComponents/utils/index";
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
  mounted() {
    this.number = this.compute(this.number);
  },
  methods: {
    compute(value) {
      return multiply3(value);
    },
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>

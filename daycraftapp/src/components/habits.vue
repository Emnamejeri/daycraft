<template>
  <navbar />
  <h1>The list of habits is below</h1>

  <footerc />
</template>
<style scoped></style>
<script>
import navbar from "./navbar";
import footerc from "./footerc";
export default {
  name: "habits",
  components: {
    navbar,
    footerc,
  },
};
</script>

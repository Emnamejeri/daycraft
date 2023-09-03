<template>
  <navbar />
  <h1>The list of days is below</h1>

  <footerc />
</template>
<style scoped></style>
<script>
import navbar from "./navbar";
import footerc from "./footerc";
export default {
  name: "days",
  components: {
    navbar,
    footerc,
  },
};
</script>

<template>
  <NavigationComponent />
  <h1>The list of habits is below</h1>

  <FooterSection />
</template>
<style scoped></style>
<script>
import NavigationComponent from "./navigationComponent.vue";
import FooterSection from "./footerSection.vue";
export default {
  name: "habitsList",
  components: {
    NavigationComponent,
    FooterSection,
  },
};
</script>

<template>
  <NavigationComponent />
  <BodyText />
  <AdviceDisplay />
  <FooterSection />
  <DaysContent />
  <HabitsList />
</template>

<script>
import NavigationComponent from "./components/navigationComponent.vue";
import BodyText from "./components/bodyText.vue";
import AdviceDisplay from "./components/adviceDisplay.vue";
import FooterSection from "./components/footerSection.vue";
import DaysContent from "./components/daysContent.vue";
import HabitsList from "./components/habitsList.vue";
export default {
  name: "App",
  components: {
    NavigationComponent,
    BodyText,
    FooterSection,
    DaysContent,
    HabitsList,
    AdviceDisplay,
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
  margin-top: 2vh;
  border: 3px solid red;
}
</style>

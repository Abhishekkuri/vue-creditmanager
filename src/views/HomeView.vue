<template>
  <div class="home">
    <h1>Welcome to your Portfolio</h1>
    <div class="portfolio-container">
      <!-- <administration-details /> -->
      <administration-details />
      <agenda-items />
      <ageing-analysis />
      <true-dso />
    </div>
  </div>
</template>

<script>
import AdministrationDetails from "@/components/AdministrationDetails.vue";
import AgeingAnalysis from "@/components/AgeingAnalysis.vue";
import AgendaItems from "@/components/Agenda-Items.vue";
import TrueDso from "@/components/TrueDso.vue";
export default {
  name: "HomeView",
  components: { AdministrationDetails, AgeingAnalysis, AgendaItems, TrueDso },
};
</script>

<style lang="scss" scoped>
.visma-logo {
  height: 2rem;
}
.home {
  .portfolio-container {
    display: grid;
    max-width: 100%;
    min-height: 70vh;
    grid-template-columns: repeat(6, 1fr);
    grid-template-rows: repeat(5, 3fr);
    align-items: stretch;
    justify-items: stretch;
    padding: 1rem 4rem;
    gap: 1rem;
  }
  @media screen and (max-width: 820px) {
    .portfolio-container {
      display: flex;
      flex-direction: column;
      align-items: stretch;
      justify-items: stretch;
      gap: 1rem;
    }
  }
}
</style>

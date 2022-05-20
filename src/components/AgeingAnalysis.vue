<template>
  <div class="aging-analysis-container">aging-analysis</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.aging-analysis-container {
  background-color: lightcoral;
  grid-row: 3/6;
  grid-column: 1/4;
  display: flex;
  align-items: center;
  justify-content: center;
}
@media screen and (max-width: 820px) {
  .aging-analysis-container {
    min-height: 20vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
}
</style>

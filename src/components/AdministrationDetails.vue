<template>
  <div class="administration-details-container">Administration Details</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.administration-details-container {
  background-color: grey;
  grid-row: 1/3;
  grid-column: 1/4;
  display: flex;
  align-items: center;
  justify-content: center;
}
@media screen and (max-width: 820px) {
  .administration-details-container {
    min-height: 20vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
}
</style>

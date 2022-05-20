<template>
  <div class="true-dso-container">true-dso</div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.true-dso-container {
  background-color: lightseagreen;
  grid-row: 4/6;
  grid-column: 4/7;
  display: flex;
  align-items: center;
  justify-content: center;
}
@media screen and (max-width: 820px) {
  .true-dso-container {
    min-height: 20vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
}
</style>

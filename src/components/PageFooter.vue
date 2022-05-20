<template>
  <div class="footer-container">
    <a href="#" target="_blank">CreditManager (3.21)</a> |
    <a href="#" target="_blank">Copyright © 2012 - 2022, Visma</a> |
    <a href="#" target="_blank">Onguard B.V.</a> |
    <a href="#" target="_blank">Disclaimer</a> |
    <a href="#" target="_blank">Privacy Statement (3.21)</a>
  </div>
</template>

<script>
export default {
  name: "PageFooter",
};
</script>

<style lang="scss" scoped>
.footer-container {
  background-color: #f0f2f5 !important;
  width: 100vw;
  overflow: hidden;
  display: flex;
  align-items: center;
  justify-content: space-around;
  a {
    text-decoration: none;
    color: black;
  }
}
</style>

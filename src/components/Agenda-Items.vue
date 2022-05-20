<template>
  <div class="agenda-items-container">
    <table>
      <th>Number</th>
      <th>Description</th>
      <th>invoice</th>
      <th>amount</th>
      <tr>
        <td>Number</td>
        <td>Number</td>
        <td>Number</td>
        <td>Number</td>
      </tr>
      <tr>
        <td>Number</td>
        <td>Number</td>
        <td>Number</td>
        <td>Number</td>
      </tr>
      <tr>
        <td>Number</td>
        <td>Number</td>
        <td>Number</td>
        <td>Number</td>
      </tr>
      <tr>
        <td>Number</td>
        <td>Number</td>
        <td>Number</td>
        <td>Number</td>
      </tr>
      <tr>
        <td>Number</td>
        <td>Number</td>
        <td>Number</td>
        <td>Number</td>
      </tr>
    </table>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.agenda-items-container {
  background-color: lightblue;
  grid-row: 1/4;
  grid-column: 4/7;
  display: flex;
  align-items: center;
  justify-content: center;
  table {
    display: table;
  }
}
@media screen and (max-width: 820px) {
  .agenda-items-container {
    min-height: 20vh;
    display: flex;
    align-items: center;
    justify-content: center;
  }
}
</style>

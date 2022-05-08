<template>
  <section>
    <div
      class="some-page-wrapper d-flex justify-content-center align-items-center"
    >
      <div class="row">
        <div class="column">
          <div class="orange-column"><img src="../assets/Layer.png" /></div>
        </div>
        <div class="column">
          <div class="blue-column"><img src="../assets/Sisyphus.png" /></div>
        </div>
        <div class="column">
          <div class="green-column"><img src="../assets/Circooles.png" /></div>
        </div>
      </div>
      <div class="row 2">
        <div class="column">
          <div class="green-column"><img src="../assets/Catalog.png" /></div>
        </div>
        <div class="column">
          <div class="orange-column"><img src="../assets/Qoutient.png" /></div>
        </div>
        <div class="column">
          <div class="blue-column"><img src="../assets/Hourglass.png" /></div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: 'NewFile',
}
</script>
<style scoped>
.some-page-wrapper {
  margin: 15px auto;
  text-align: center;
}
.column img {
  height: 48px;
  width: 186.99998474121094px;
}

.row {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  /* width: 100%; */
  width: 1440px;
}

.column {
  display: flex;
  flex-direction: column;
  flex-basis: 100%;
  flex: 1;
}

.blue-column {
  /* background-color: blue; */
  /* height: 100px; */
}

.green-column {
  /* background-color: green; */
  /* height: 100px; */
}
@media screen and (min-width: 800px) {
  .column img {
    height: 34px;
    width: 100px;
  }
  .double-column img {
    height: 34px;
    width: 100px;
  }
  .column {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0 auto;
    flex: 1;
  }

  .double-column {
    flex: 2;
  }
}
</style>

<template>
  <div>
    <div class="container">
      <div class="row mb-4">
        <div class="col-4">
          <div class="card">
            <div class="card-body">
              <img src="\images\ando.jpg">
            </div>
            <div class="card-body">
              <img src="\images\r2.png" height="170">
            </div>
          </div>
        </div>
        <div class="col-8">
          <div class="card">
            <div class="card-body">
              <chart></chart>
            </div>
          </div>
        </div>
      </div>
      <div class="row mb-4">
        <div class="col-4">
          <donut-chart></donut-chart>
        </div>
        <div class="col-4">
          <donut-chart></donut-chart>
        </div>
        <div class="col-4">
          <donut-chart></donut-chart>
        </div>
      </div>
     
    </div>

  </div>
</template>

<script>
  import Chart from "@/components/Chart";
  import DonutChart from "@/components/DonutChart";


  export default {
  name: 'HelloWorld',
  components: {
    Chart,
    DonutChart
  }

}
</script>

<style >

</style>

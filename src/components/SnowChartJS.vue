<template>
  <section class="container">
    <h1>Demo examples of vue-chartjs</h1>
    <div class="columns">
      <div class="column">
        <h3>Line chart</h3>
          <SnowLineChart></SnowLineChart>
      </div>
    </div>
  </section>
</template>

<script>
import SnowLineChart from '@/components/SnowLineChart'
export default {
  name: 'VueChartJS',
  components: {
    SnowLineChart
  },
}
</script>

<style scoped>
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
<template>
  <section class="container">
    <ul>
      <li><router-link to="/Home">Home</router-link></li>
      <li><router-link to="/chartjs">vue-chartjs</router-link></li>
    </ul>
    <h1>Demo examples of vue-chartjs</h1>
    <div class="columns">
      <div class="column">
        <h3>Line chart</h3>
          <LineChart></LineChart>
      </div>
      <div class="column">
        <h3>Bar chart</h3>
          <bar-chart></bar-chart>
      </div>
    </div>
  </section>
</template>

<script>
import LineChart from '@/components/LineChart'
import BarChart from '@/components/BarChart'
export default {
  name: 'VueChartJS',
  components: {
    LineChart,
    BarChart
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
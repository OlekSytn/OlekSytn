<template>
    <Line :data="data1" :options="options1" />
  </template>


  
  <script>
  import {
    Chart as ChartJS,
    CategoryScale,
    LinearScale,
    PointElement,
    LineElement,
    Title,
    Tooltip,
    Legend,
    Filler
  } from 'chart.js'
  import { Line } from 'vue-chartjs'
  import * as chartConfig from './chartConfig.js'
  
  ChartJS.register(
    CategoryScale,
    LinearScale,
    PointElement,
    LineElement,
    Title,
    Tooltip,
    Legend,
    Filler
  )
   
  export default {
    name: 'App',
    components: {
      Line
    },
    data() {
      return chartConfig
    }
  }
  </script>
  
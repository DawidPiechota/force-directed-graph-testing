<template>
  <div id="app">
    <VisualiseData msg="Graph testing"/>
  </div>
</template>

<script>

import VisualiseData from './components/VisualiseData.vue'
import * as d3 from "d3";

export default {
  name: 'App',
  components: {
    VisualiseData
  }
}
</script>

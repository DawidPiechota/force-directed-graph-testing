<template>
  <div id="app">
    <Graph msg="Graph testing"/>
  </div>
</template>

<script>

import Graph from './components/Graph.vue'
import * as d3 from "d3";

export default {
  name: 'App',
  components: {
    Graph
  }
}
</script>

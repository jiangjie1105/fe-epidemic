<template>
  <div id="app">
    <Header />
    <TabChange />
    <EpidemicMap/>
    <RealTime />
    <RumourReny />
    <DiseaseKnowledge/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import RealTime from "./components/RealTime.vue";
import DiseaseKnowledge from "./components/DiseaseKnowledge.vue";
import TabChange from "./components/TabChange.vue";
import EpidemicMap from './components/EpidemicMap.vue';
import RumourReny from "./components/RumourReny.vue";

export default {
  name: "App",
  components: {
    Header,
    TabChange,
    EpidemicMap,
    DiseaseKnowledge,
    RumourReny,
    RealTime
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>

<template>
  <div id="Visualization">
    <GagesBarChartAnimation />
    <MapboxSlider />
<!--    <AnnotatedTimeline />-->
    <TakeAway />
    <DataSources />
    <Methods />
    <References />
  </div>
</template>

<script>
  import GagesBarChartAnimation from "../components/GagesBarChartAnimation";
  import MapboxSlider from "../components/MapboxSlider";
  import DataSources from "../components/DataSources";
  // import AnnotatedTimeline from "../components/AnnotatedTimeline";
  import Methods from "../components/Methods";
  import References from '../components/References';
  import TakeAway from '../components/TakeAway';
  export default {
      name: 'Visualization',
      components: {
          GagesBarChartAnimation,
          MapboxSlider,
          // AnnotatedTimeline,
          TakeAway,
          DataSources,
          Methods,
          References
      }
  }
</script>

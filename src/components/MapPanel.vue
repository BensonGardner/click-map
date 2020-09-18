<template>
  <div id="map-panel" class="panel" />
</template>

<script>
import mapboxgl from 'mapbox-gl';
import 'mapbox-gl/dist/mapbox-gl.css';

// TODO put your own token here
mapboxgl.accessToken = 'pk.eyJ1IjoicGFuYmFsYW5nYSIsImEiOiJja2Y3cGxiM2QwMTZ5MnFvMzd6Z2syNHo4In0.rmd2bjUlB03qdYpUGUZmfg';

export default {
  mounted() {
    const map = new mapboxgl.Map({
      container: 'map-panel',
      style: 'mapbox://styles/mapbox/streets-v11',
      center: [-98.579169, 39.828148],
      zoom: 3,
    });
    this.map = map;
  },
};
</script>

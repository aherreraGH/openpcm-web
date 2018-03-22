<template>
  <div id="app">
    <app-canvas/>
  </div>
</template>

<script>


import { EventBus } from "./configuration/config";
import Canvas from './components/main/Canvas.vue';

export default {
  data() {
    return {};
  },
  mounted() {},
  beforeCreate() {
    this.$options.components.AppCanvas = Canvas;
  },
  methods: {},
  created() {}
};
</script>

<style lang="scss">
@import '~bulma/css/bulma.css';


</style>
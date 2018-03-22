<template>
  <div id="canvas-div">
    <app-header/>
    <widgets />
    <!-- <a class="btn btn-danger btn-large">Bootstrap Button</a> -->
    <app-footer/>
  </div>
</template>
<script>
/*
 * This is the main canvas. We should keep App.vue as clean as possible.
 */
import AppHeader from '../common/Header.vue';
import AppFooter from '../common/Footer.vue';
import Widgets from './Widgets.vue';

export default {
  name: "openpcm-canvas",
  data() {
    return {};
  },
  mounted() {},
  beforeCreate() {
        this.$options.components.AppHeader = AppHeader;
        this.$options.components.AppFooter = AppFooter;
        this.$options.components.Widgets = Widgets;
  },
  methods: {},
  created() {}
}
</script>
<style scoped>

</style>

<template>
  <div id="widgets-div">
      <widget v-for="(widget, idx) in numWidgets" :key="idx" :count="idx"/>
  </div>
</template>
<script>

import Widget from './Widget.vue';

export default {
  name: "openpcm-widgets",
  data() {
    return {
        numWidgets: [0, 1, 2, 3, 4, 5, 1, 2, 3, 4, 5, 1, 2, 3, 4, 5, 1, 2, 3, 4, 5]
    };
  },
  mounted() {},
  beforeCreate() {
        this.$options.components.Widget = Widget;
  },
  methods: {},
  created() {}
}
</script>
<style scoped>
#widgets-div {
    display: inline-flex;
    flex-wrap: wrap;
}
</style>

<template>
  <div id="widget-div" class="widget-box">
      Widget {{count}}
  </div>
</template>
<script>

export default {
    props: ["count"],
  name: "openpcm-widget",
  data() {
    return {
    };
  },
  mounted() {},
  beforeCreate() {
  },
  methods: {},
  created() {}
}
</script>
<style scoped>
.widget-box {
    width: 100px;
    min-width: 100px;
    height: 100px;
    min-height: 100px;
    border: 1px solid lightgray;
    border-radius: 10px;
    margin: 10px;
    display: inline-flex;
    align-content: center;
    align-items: center;
    text-align: center;
    background-color: rgba(5,5,5,0.2);
    border-color: #000;
    padding: 10px;
}
</style>

<template>
<nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="https://openpcm.org">
      <img class="openpcm-logo" src="/src/assets/openpcm-logo3.png" alt="">
    </a>
  </div>
</nav>
</template>
<script>
export default {
  name: "openpcm-header",
  data() {
    return {};
  },
  mounted() {},
  beforeCreate() {},
  methods: {},
  created() {}
};
</script>
<style scoped>
.openpcm-logo {
  max-height: 79px !important;
  margin-top: 15px;
}

.navbar {
    border-bottom: 1px solid #000;
    min-height: 80px !important;
}
</style>

<template>
  <section class="container">
    <div>
      <h1 class="title">top</h1>
      <div class="links"></div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {};
  },
  mounted() {},
  methods: {
    clickAnju20190812() {
      console.log('clickIllust');
      this.$router.push('/anjuinami/20190812/');
    },
    clickAnju20191225() {
      console.log('clickIllust');
      this.$router.push('/anjuinami/20191225/');
    },
  },
  head() {
    return {
      title: 'トップ',
    };
  },
};
</script>

<style scoped>
.links {
  padding-top: 15px;
}
.button-area {
  padding: 8px 0;
}
</style>

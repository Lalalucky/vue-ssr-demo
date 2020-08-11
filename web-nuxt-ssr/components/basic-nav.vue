<template>
  <div class="navs">
    <ul>
      <li>nav</li>
      <li>nav</li>
      <li>nav</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'basic-nav',
  data() {
    return {}
  },
  components: {},
  mounted() {},
  methods: {},
}
</script>

<style scoped lang="scss">
@import '~/assets/scss/_reset.scss';
.navs {
  width: 100%;
  ul {
    width: 100%;
    display: grid;
    grid-template-columns: 75px 75px 75px;
  }
}
</style>

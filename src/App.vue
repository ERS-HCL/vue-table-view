<template>
  <div class="container" >
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: { },
  data() {
    return { }
  },
  methods: { }
};
</script>

<style scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  height:90vh;
}
</style>

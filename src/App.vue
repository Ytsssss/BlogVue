<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <div class="box">
      <div class="son"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {

    }
  },
  props: {},
  methods: {},
  created() {},
  mounted() {}
}
</script>

<style lang='less'>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.box {
  width: 100px;
  height: 100px;
  border: 1px solid #000;
  .son {
    width: 50px;
    height: 50px;
    background-color: #0dd;
  }
}
</style>

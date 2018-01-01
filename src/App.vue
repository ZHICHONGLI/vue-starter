<template>
  <div id="app">
    <div class="nav">
      <a href="#/">
        <button class="btn btn-default">
          Main
        </button>
      </a>
      <a href="#/index"><button class="btn btn-default">Index</button></a>
    </div>
    <hr/>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app',
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<template>
  <div id="app">
      <div style="width:100%;height:100%">
          <v-element-scrollbar direction="both">
              <div style="height:2000px"></div>
          </v-element-scrollbar>
      </div>
  </div>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>
html,body{
    height: 100%;
    margin: 0;
    padding: 0;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100%;

}
</style>

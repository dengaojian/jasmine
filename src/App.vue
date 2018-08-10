<template>
  <div id="app">
    <div class="fsaf">
      <div class="title">邓傲剑笔记本</div>
    </div>
    <div class="abc">
      fdsafsda
    </div>

    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="stylus">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.fsaf
  .title
    color red
    box-sizing: border-box;
</style>

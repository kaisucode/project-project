<template>
  <div id="app">
    <div id="nav">
      <router-link to="/week">This Week</router-link> |
      <router-link to="/month">This Month</router-link> | 
      <router-link to="/year">This Year</router-link> | 
      <router-link to="/categories">Categories</router-link> 
			<br>
			<router-link to="/help">Help</router-link> | 
			<router-link to="/about">About</router-link>
    </div>
    <div id="router-view-div">
      <router-view/>
    </div>
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #5c8735;
    }
  }
}
</style>
<script>
global.jQuery = require('jquery');
var $ = global.jQuery;
window.$ = $;
</script>

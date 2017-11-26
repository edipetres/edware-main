<template>
  <div id="app">
    <nav class="navbar navbar-light bg-light">
      <span class="navbar-brand mb-0 h1 padded-nav-item">edware.io</span>
    </nav>
    <main>
      <router-view></router-view>
    </main>
  </div>
</template>

<script>
export default {
  name: 'app',
};
</script>

<style>
body {
  margin: 0;
}

#app {
  /* font-family: 'Avenir', Helvetica, Arial, sans-serif; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

main {
  text-align: center;
  /* margin-top: 40px; */
}

nav {
  padding: 0 !important;
}

.padded-nav-item {
  padding: 10px
}

nav .h1 {
  font-family: 'Open Sans', sans-serif;
  font-weight: 600;
  letter-spacing: 2px;
}

span:hover {
  background-color: #EAFDF2;
  border-right: 2px solid #595959;
}
</style>

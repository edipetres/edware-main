<template>
  <div id="app">
    <!-- Navbar -->
    <nav class="navbar navbar-expand-sm navbar-light bg-light justify-content-between">
      <a class="navbar-brand nav-logo" href="#">
        <img src="/static/edware.io-logo.png" class="d-inline-block align-top" alt="">
      </a>
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown"
        aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home
              <span class="sr-only">(current)</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Projects</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
        </ul>
      </div>

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

.nav-logo:hover {
  background-color: #EAFDF2;
  border-right: 2px solid #595959;
}

.nav-item:hover {
  background-color: #EAFDF2;
}

nav img {
  height: 50px;
  width: auto;
  padding-left: 10px;
}
</style>

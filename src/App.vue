<template>
  <div id="app">
    <!-- <nav class="navbar navbar-light bg-light">
      <span class="navbar-brand mb-0 h1 padded-nav-item">edware.io</span>

    </nav> -->

    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-light bg-light justify-content-between">
      <div class="nav-logo">
        <a class="navbar-brand mb-0 h1 padded-nav-item" href="">edware.io</a>
      </div>
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
            <a class="nav-link" href="#">Features</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Pricing</a>
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

.padded-nav-item {
  padding: 10px
}

.nav-logo {
  font-family: 'Open Sans', sans-serif;
  font-weight: 600;
  letter-spacing: 2px;
  padding-left: 15px;
}

.nav-logo:hover {
  background-color: #EAFDF2;
  border-right: 2px solid #595959;
}

.nav-item:hover {
  background-color: #EAFDF2;
}
</style>

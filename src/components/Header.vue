<template>
  <div class='main'>
    <a href="">
      <img src="/static/portrait.png" alt="Profile pic" class="profile-img rounded-circle">
    </a>
    <a href="http://www.edware.io">
      <h1>Edmond Petres</h1>
    </a>
    <h2>Developer @ Praqma</h2>
  </div>
</template>
<script>
export default {

};
</script>

<style lang="scss">
$light-green: #E0F2E9;
$border-color: 1px solid #A7CEBA;

.main {
  font-family: 'Open Sans', sans-serif;
  /* font-family: 'Roboto', sans-serif; */
  /* font-family: 'Arvo', serif; */
  padding-top: 50px;
  padding-bottom: 50px;
  background-color: $light-green;
  color: #595959;
  font-weight: bold !important;
  border-bottom: $border-color;
  border-top: 1px solid #A7CEBA;
}
</style>

<style>
.profile-img {
  width: 130px;
  padding: 0.5rem;
  margin-bottom: 20px;
  border: 1px solid #A7CEBA;
  background-color: white;
}
.profile-img:hover {
  border-color: #595959;
}

h1 {
  font-weight: 700;
  font-size: 48px;
}
h2 {
  font-weight: 100;
}
a:hover, a:active {
    text-decoration: none;
}
</style>

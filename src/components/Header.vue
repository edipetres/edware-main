<template>
  <div class='main'>
    <a href="//edware.io">
      <img src="/static/portrait.png" alt="Profile pic" class="profile-img rounded-circle">
    </a>
    <a href="//edware.io">
      <h1>Edmond Petres</h1>
    </a>
    <h2>Developer <a target="_blank" href="https://www.praqma.com/">@Praqma</a><br>
    🎓 Computer Science <a target="_blank" href="https://www.cphbusiness.dk/">@Cphbusiness</a></h2>
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
  padding-top: 30px;
  padding-bottom: 20px;
  background-color: $light-green;
  color: #595959;
  font-weight: bold !important;
  border-bottom: $border-color;
  border-top: 1px solid #A7CEBA;
}
</style>

<style>
.profile-img {
  width: 115px;
  padding: 0.5rem;
  margin-bottom: 10px;
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
  font-family: 'Merriweather', sans-serif;
  color: #829099;
  font-size: 1.5rem;
}
a:hover, a:active {
    text-decoration: none;
}
</style>

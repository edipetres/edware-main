<template>
  <div class='main'>
    <img src="/static/portrait.png" alt="Profile pic" class="profile-img rounded-circle">
    <h1>Edmond Petres</h1>
    <h2>Developer @ Praqma</h2>
  </div>
</template>
<script>
export default {

};
</script>

<style>
.main {
  font-family: 'Open Sans', sans-serif;
  /* font-family: 'Roboto', sans-serif; */
  /* font-family: 'Arvo', serif; */
  padding-top: 50px;
  padding-bottom: 50px;
  background-color: #E0F2E9;
  color: #595959;
  font-weight: bold !important;
  border-bottom: 1px solid #A7CEBA;
  border-top: 1px solid #A7CEBA;
}
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
</style>

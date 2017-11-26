<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col no-padding">
        <main-header></main-header>
      </div>
    </div>

    <div class="row">
      <div class="col cardboard hello">
        <div class="card-deck">
          <div class="card">
            <a href="//questionnaire.edware.io" class="card-link">
              <img class="card-img-top" src="/static/questionnaire-matrix.png" alt="Card image cap">
            </a>
            <div class="card-body">
              <h4 class="card-title">Questionnaire Engine</h4>
              <p class="card-text">This was an internship project at Praqma. A web application that displays forms written in Yaml files in a matrix.</p>
              <a href="//questionnaire.edware.io" class="card-link">Demo</a>
              <a href="https://github.com/Praqma/questionnaire-engine" class="card-link">GitHub repo</a>
            </div>
          </div>
          <div class="card">
            <img class="card-img-top" src="/static/sc-admin-light.png" alt="Card image cap">
            <div class="card-body">
              <h4 class="card-title">SiteCampaign Admin Page</h4>
              <p class="card-text">A dashboard interface for manually editing running campaigns. An internal project at SiteCampaign.</p>
              <!-- <p class="card-text">
                <small class="text-muted">Last updated 3 mins ago</small>
              </p> -->
            </div>
          </div>
          <div class="card">
            <img class="card-img-top" src="http://aestheticc.com/wp-content/uploads/2016/06/coming-soon.jpg" alt="Card image cap">
            <div class="card-body">
              <h4 class="card-title">Toggl Rules</h4>
              <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even
                longer content than the first to show that equal height action.</p>
              <a href="https://github.com/Praqma/toggl-rules" class="card-link">GitHub repo</a>
            </div>
          </div>
        </div>
      </div>

    </div>

  </div>
</template>


<script>
import MainHeader from './Header';

export default {
  name: 'hello',
  data() {
    return {
      msg: 'Welcome to Edware',
    };
  },
  components: {
    MainHeader,
  },
};
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h1,
h2 {
  /* font-weight: normal; */
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #35495e;
}

.no-padding{
  padding: 0! important;
}

.cardboard {
  margin-top: 30px;
}

</style>

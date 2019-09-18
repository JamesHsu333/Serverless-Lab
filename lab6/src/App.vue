<template>
  <div>
    <b-navbar style="background-color: rgb(237, 125, 49)">
        <a class="navbar-brand">
            <img src="https://i.imgur.com/skVSs35.png" width="160">
        </a>
    </b-navbar>
    <div id="component" class="jumbotron jumbotron-fluid" style="padding-top: 1rem; background-color: rgb(64, 64, 64);">
        <div class="container">
            <h2 class="display-4" style="padding-bottom: 1rem;">Lab 6: Azure Serverless </h2>
            <p class="lead">QAQ Build Serverless Environment with Azure Function</p>
            <hr class="my-4">
            <button type="button " class="btn btn-success" >Get Item by function</button>
        </div>
    </div>
    <!--<router-view/>-->
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
body {
        color: white;
        background-color: rgb(64, 64, 64);
    }


    hr {
        margin-top: 1rem;
        margin-bottom: 1rem;
        border: 0;
        border-top: 1px solid rgb(108, 117, 125);
    }
</style>

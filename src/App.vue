<template>
  <div class="header">
    <md-toolbar class="md-transparent" md-elevation="0">
      <h1 class="md-title">美食与烹饪</h1>
    </md-toolbar>
    <md-content>
      <div class="md-layout md-alignment-center-space-around">
        <div id="search" class="md-layout-item md-size-20">
          <md-field>
            <label>Search</label>
            <md-input></md-input>
            <md-icon>search</md-icon>
          </md-field>
        </div>
      </div>
    </md-content>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style>
@import url("https://fonts.googleapis.com/icon?family=Material+Icons");

.md-content {
  width: 100%;
  height: 400px;
  align-items: center;
  background-image: linear-gradient(
    45deg,
    rgb(55, 119, 175),
    rgb(125, 92, 141) 50%,
    rgb(231, 50, 88)
  );
}

.header {
  background-image: linear-gradient(
    45deg,
    rgb(55, 119, 175),
    rgb(125, 92, 141) 50%,
    rgb(231, 50, 88)
  );
}

#search {
  margin-top: 5%;
}
</style>

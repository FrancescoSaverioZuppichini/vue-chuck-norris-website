<template>
<div id="app" class='d-flex flex-column'>
  <div class="jumbotron">
    <h1> Click on Chuck Norris
    </h1>
    <h6>to discover funny jokes about him!</h6>
  </div>
  <div class="flex--grow"></div>
  <div class="container">
    <div class="d-flex justify-content-center">
      <chuck-norris ></chuck-norris>
    </div>
  </div>
    <div class="flex--grow"></div>
</div>
</template>

<script>

import ChuckNorris from 'vue-chuck-norris'

export default {
  name: 'app',
  components: {
    ChuckNorris
  }
}
</script>

<style>
#app{
    height: 100vh;
}
.flex--grow {
  flex-grow: 99;
}
</style>

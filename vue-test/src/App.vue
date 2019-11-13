<template>
  <div id="app">
     <img src="../static/logo.png">
     <h2>Vue.js logo</h2>
     <router-view class="view"></router-view>
  </div>
</template>

<style>
  body {
    font-family: Helvetica, sans-serif;
  }
  .router-link-active{
    color: red ;
  }
</style>

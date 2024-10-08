<template>
    <div id="app">
      <header>
        <h1>Welcome</h1>
      </header>
      <main>
        <h2>Welcome to S42.site</h2>
        <p>This is a simple Vue.js application.</p>
      </main>
    </div>
  </template>
  
  <script>
  export default {
    name: 'App',
  };
  </script>
  
  <style>
  #app {
    text-align: center;
    margin-top: 50px;
  }
  
  header {
    background-color: #42b983;
    color: white;
    padding: 20px;
    border-radius: 5px;
  }
  
  h1 {
    margin: 0;
  }
  
  main {
    margin-top: 20px;
  }
  </style>
  
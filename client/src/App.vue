<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/quizPage">Quiz</router-link> |
      <router-link to="/mapworld">Mapworld</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  background-color: #F2DAC4;
}

#nav a {
  font-weight: bold;
  color: #184059;
}

#nav a.router-link-exact-active {
  color: #F26B83;
}
</style>

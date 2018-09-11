<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>

html {
  background-color: silver;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  
}
#nav {
  padding: 30px;
}


#nav a.router-link-exact-active {
  color: lightseagreen;
}

h1 {
  font-size: 9vw;
  text-shadow: 2px 2px 2px #0079bf;
}

h3 {
  color: lightseagreen;
  font-size: 2.5vw;
  text-shadow: 1px 1px 1px #0079bf;
}

h1, h2 {
  color: lightseagreen;
  font-family: 'Archivo Narrow', sans-serif;
}

p, a, h3 {

  font-family: 'Lato', sans-serif;
}
</style>

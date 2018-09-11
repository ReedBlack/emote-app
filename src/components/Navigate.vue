<template>
    <nav id="nav">
        <router-link to="/">home</router-link> |
        <router-link to="/about">about</router-link> |
        <router-link to="/logout">logout</router-link> 
    </nav>
</template>

<style scoped>
#nav a {
  font-weight:bolder;
  color: lightseagreen;
  font-size: 2.4vh;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
    
</style>
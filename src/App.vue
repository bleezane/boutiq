<template>
  <div id="nav">
    <router-link to="/">Accueil</router-link> |
    <router-link to="/magasin">magasin</router-link>
  </div>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: right;
  color: #50342c;
-ms-text-align-last: right
}
template
#nav {
  padding: 25px;
}
script
#nav a {
  font-weight: bold;
  color: #2c5037;
}

#nav a.router-link-exact-active {
  color: #4297b9;
}
</style>

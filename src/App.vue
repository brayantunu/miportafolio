<template>
  <nav>
    <router-link class="inicio" to="/">B.T</router-link> 
    <router-link class="inici" to="/portafolio">PORTAFOLIO</router-link> |
    <router-link class="acerca" to="/acercade">ACERCA DE</router-link>
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  display: flex;
  padding: 30px;
  background-color: transparent;

}

nav a {
  font-weight: bold;
  color: #2c3e50;
}
.inicio{
 margin-left: 20PX;
margin-right: auto;
text-decoration: none;
}
.inici{
  margin-left: 10px;
  text-decoration: none;
}
nav a.router-link-exact-active {
  color: #42b983;
}


</style>

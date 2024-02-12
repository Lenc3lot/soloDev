<template>
  <nav>
    <img width="50" height="50" src="./assets/logo.png"/>
    <span>
      <router-link to="/">Accueil</router-link>
      <router-link to="/about">Voter</router-link>
      <router-link to="/login">Connexion</router-link>
    </span>
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

#app > nav:nth-child(1) {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav {
  padding: 30px;
}

nav>span{
  /* border: solid 1px;
  padding: 1%; */
  width: 30%;
  display: flex;
  justify-content: space-between;
}

nav>span>a{
  border: solid 1px;
  border-color: black;
  width: 100%;
  height: 100%;
  padding: 2%;
}

nav>span>:nth-child(1),:nth-child(2){
  border-right: none;
}

nav>span>:nth-child(2),:nth-child(3){
  border-left: none;
}


nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>


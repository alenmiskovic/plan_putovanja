<template>
  <div id="app">
    <nav class="navbar navbar-light bg-light">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="@/assets/putovanje.jpg" alt="" width="40" height="40" class="d-inline-block align-text-top">
          Plan Putovanja
        </a>
      </div>
    </nav>
    <div class="nav-links">
      <router-link to="/">Home</router-link>
      <router-link to="/login">Prijava</router-link>
      <router-link to="/signup">Registracija</router-link>
    </div>
    <router-view/>
  </div>
</template>

<style>
.nav-links {
  display: flex; 
  justify-content: space-around; 
  background-color: #f8f9fa; 
  padding: 10px; 
}
.nav-links router-link {
  text-decoration: none; 
  padding: 10px;
}
</style>




<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
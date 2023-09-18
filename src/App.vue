<template>
  <div id="app">
    <div class="container">
      <div class="row">
        <div class="col">
          <nav id="nav" class="navbar navbar-expand-lg navbar-light bg-light">
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
              <a class="navbar-brand" href="#">
                
  <img src="@/assets/putovanje.jpg" alt="¸Putovanje" width="50" height="50" class="d-inline-block align-text-top">                                
              </a>
              <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
                <li class="nav-item">
                  <router-link to="/" class="nav-link">Home</router-link>
                </li>
                <li class="nav-item">
                  <router-link to="/login" class="nav-link">Prijava</router-link>
                </li>
                <li class="nav-item">
                  <router-link to="/signup" class="nav-link">Registracija</router-link>
                </li>
              </ul>
              <form class="form-inline my-2 my-lg-0">
                <input class="form-control mr-sm-2" type="search" placeholder="Pretraga" aria-label="Search">
              </form>
            </div>
          </nav>
        </div>
      </div>
    </div>

    <div class="container">
      <router-view/>
      <!-- tu router dinamicki ubaci screen -->
    </div>

  </div>
</template>

<style lang="scss">
body {
  background-color: rgba(var(--b3f,250,250,250),1);
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  background-color: white;
  border-bottom: #ccc 1px solid;

  margin-bottom: 30px;
  a {
    font-weight: bold;
    color: lightcoral;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
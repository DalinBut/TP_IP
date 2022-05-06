<template>
  <div id="app">
    <div class="lcontainer">
      <img src="./assets/logo.png" alt="logo" class="logo">
      <h1>Welcome</h1>
        <nav>
          <router-link to="/">Login</router-link> |
          <router-link to="/register">Register</router-link>
        </nav>
    </div>
    <router-view/>
  </div>
</template>

<script>

</script>
<style>
.lcontainer {
  display: flex;
  flex-direction: column;
  place-items: flex-star;
  flex-wrap: wrap;
  text-align: center;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  display: flex;
  place-items: center;
  justify-content: space-around;
}

nav {
  padding: 30px;
  display: flex;
  place-items: flex-start;
  /* flex-wrap: wrap; */
  width: 50%;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>

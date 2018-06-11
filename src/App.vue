<template>
  <div id="app">
    <header>
      <span>Vue.js</span>
      <router-link to="/login" exact id="rutas">Login</router-link>
      <router-link to="/" exact id="rutas">home</router-link>
    </header>
    <main>
      <img src="./assets/logo.png" alt="Vue.js PWA">
      <router-view></router-view>
    </main>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
body {
  margin: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

main {
  text-align: center;
  margin-top: 40px;
}

header {
  margin: 0;
  height: 56px;
  padding: 0 16px 0 24px;
  background-color: #35495E;
  color: #ffffff;
  justify-content: center;  
  align-items: center;
  align-content: center;
}

header span {
  position: relative;
  font-size: 20px;
  line-height: 2;
  letter-spacing: .02em;
  font-weight: 400;
  box-sizing: border-box;
  padding-top: 16px;
}
#rutas {
  position: relative;
  font-size: 20px;
  line-height: 2;
  letter-spacing: .02em;
  font-weight: 400;
  box-sizing: border-box;
  
  color: white;
  
}
</style>

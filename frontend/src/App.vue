<!--
<template>
  <div class="nav">
    <router-link class="nav-link" to="/">Home</router-link> |
    <router-link class="nav-link" to="/counter">Counter</router-link> |
    <router-link class="nav-link" to="/users">Users</router-link> |
    <router-link class="nav-link" to="/about">About</router-link>
  </div>
  <router-view />
</template>

<style scoped>
.nav {
  text-align: center;
  padding: 30px;
}

.nav-link {
  font-weight: bold;
  color: #2c3e50;
}

.nav-link.router-link-exact-active {
  color: #42b983;
}
</style>
-->
<template>
  <div id="app">
    <Header />
    <router-view />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Footer from "./components/Footer.vue"
export default {
  components: {
    Header,
    Footer
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
}
body {
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
}
ul {
  list-style: none;
}
a {
  text-decoration: none;
}
</style>
<template>
  <div id="app">
    <header>
        <router-link class="li" to="/">Home</router-link>
        <router-link class="li" to="/about">who we are?</router-link>
        <router-link class="li" to="/stats">educourse stats</router-link>
    </header>
    <router-view></router-view>    
  </div>
</template>

<script>
import VueRouter from 'vue-router'
import Home from './pages/Home.vue'
import About from './pages/About.vue'
import Stats from './pages/Stats.vue'
const routes = [
  { path: '/', component: Home },
  { path: '/about', component: About },
  { path: '/stats', component: Stats }
]

// 3. Create the router instance and pass the `routes` option
// You can pass in additional options here, but let's
// keep it simple for now.
const router = new VueRouter({
  routes, // short for `routes: routes`
  mode: 'history'
})

export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  router
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>

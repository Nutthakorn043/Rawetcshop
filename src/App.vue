<template>
  <div id="app">
     <b-navbar toggleable type="dark" variant="faded" class="shadow p-3 mb-5 bg-white rounded">
        
    <b-navbar-brand href="#"><img src="../photo/NUTHAT.png" style="max-width: 10rem;"  alt=""></b-navbar-brand>
    

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
    
    <b-navbar-nav class="ml-auto">
        <li class="nav-item">
              <a class="nav-link nav-link-icon text-dark" href="#">
                <b-icon icon="person-circle"></b-icon> Login
              </a>
            </li>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <router-view />
  

     
  </div>
</template>
<script>
import Home from './views/Home.vue'
export default {
    name: 'App',
    views: {
      Home,
    },

  };

</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>

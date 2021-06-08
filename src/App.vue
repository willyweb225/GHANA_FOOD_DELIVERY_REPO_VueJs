<template>
  <div id="app">
      <!--<div id="nav">
            <router-link to="/">Home</router-link> |
            <router-link to="/about">About</router-link>
            <p>tititit</p>
        </div>-->
        <Header></Header>
      <router-view/>
      <Footer/>
  </div>
</template>

<script>
import Header from './views/layouts/Header.vue'
import Footer from './views/layouts/Footer.vue'
  export default{
    name:'App',
    components:{
      Header, Footer
    }
  }
</script>

<style lang="scss">
@import './assets/css/style.css';
@import './assets/css/custom.css';
@import './assets/css/home.css';
@import './assets/css/order-sign_up.css';
@import './assets/css/bootstrap_customized.min.css';
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>

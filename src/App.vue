<template>
  <div id="app">
    <NavBar/>
    <Home title="Admin Panel" msg="Create New Recipes and add Ingredients"/>
    <Contact title="Contact Us" />
  </div>
</template>

<script>
import Home from './components/Home.vue'
import NavBar from "@/components/NavBar";

export default {
  name: 'App',
  components: {
    Home,
    NavBar
  }
}
</script>



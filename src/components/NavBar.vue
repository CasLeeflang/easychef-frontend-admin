<template>
<b-navbar class="is-fixed-top">
  <template #brand>
    <b-navbar-item tag="router-link" :to="{path: '/'}">

      <img src="../../assets/EasyChefLogo.png"/></b-navbar-item>
  </template>

  <template #start>
    <b-navbar-item href="#">
      Home
    </b-navbar-item>
    <b-navbar-item href="#">
      Recipes
    </b-navbar-item>
  </template>

  <template #end>
    <b-navbar-item tag="div">
      <div class="buttons">
        <a class="button is-primary">
          <strong>Sign Up</strong>
        </a>
        <a class="button is-light">
          Log in
        </a>
      </div>
    </b-navbar-item>
  </template>

</b-navbar>
</template>

<script>
export default {
  name: "NavBar"
}
</script>

<style scoped>

</style>
<template>
  <div class="hero is-primary is-halfheight is-bold">
    <div class="hero-body">
      <div class="container has-text-centered">
        <h1 class="title">{{title}}</h1>
        <p class="is-size-5">{{ msg }}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    title: String,
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
.m-t-30 {
  margin-top:30px;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

</style>

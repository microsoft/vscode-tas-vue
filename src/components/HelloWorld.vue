<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p class="description">
      This project was generated with the Vue CLI. For guides and recipes on how to configure and
      customize this project, check out the
      <a href="https://cli.vuejs.org" target="_blank">vue-cli documentation</a>.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
};
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
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}

p.description {
  width: 50%;
  margin: auto;
}
</style>

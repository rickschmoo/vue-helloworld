<template>
  <div class="helloworldrick">
    <h1>{{ test }}</h1>
    <p>{{ test }} {{ message }}</p>
    <ul>
      <li>1</li>
      <li>2</li>
      <li>3</li>
    </ul>
    <div id="app-2">
      <span v-bind:title="message">
        Hover your mouse over me for a few seconds
        to see my dynamically bound title!
      </span>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld123',
  props: {
    test: String,
    message: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
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

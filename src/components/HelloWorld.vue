<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Em breve uma página melhor! 💻</p>
    <p>
        Siga meu perfil de tecnologia no Instagram! <a href="https://www.instagram.com/dev_insano/?hl=pt-br" target="blank">Dev Insano</a>
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
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
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
  text-decoration: none;
}
a:hover {
  color: #DB1C1C;
}
</style>

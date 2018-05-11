<template>
<v-jumbotron
    :gradient="gradient"
    :src= "require('@/assets/HomeBg.png')"
    height="80%"
    dark
  >
  </v-jumbotron>
</template>

<script>
export default {
  data () {
    return {
      gradient: 'to top right, rgba(63,81,181, .7), rgba(25,32,72, .7)'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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

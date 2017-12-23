<template>
  <div class="hello">
    <h2>Essential Links</h2>
    <vue-birthday v-model="dob"></vue-birthday>
  </div>
</template>

<script>
import vueBirthday from '/Users/xank/dev-npm/vue-birthday-input/src/vue-birthday-input'
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      dob: ''
    }
  },
  components: {
    vueBirthday
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

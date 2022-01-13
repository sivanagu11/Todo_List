<template>
  <todo msg = ""/>
</template>

<script>
import Todo from './components/Todo.vue'

export default {
  name: 'App',
  components: {
        Todo
  }
}
</script>

<style>
body{

background-image: linear-gradient( 90deg, #00DBDE 0%, #FC00FF 100%);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

</style>

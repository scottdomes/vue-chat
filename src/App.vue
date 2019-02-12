<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MessageList v-bind:messages="messages"/>
  </div>
</template>

<script>
import MessageList from './components/MessageList.vue'

export default {
  name: 'app',
  components: {
    MessageList
  },
  data: () => ({
    messages: []
  })
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

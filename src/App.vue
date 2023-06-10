<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <NavBar />
    <Form />
  </div>
  
</template>

<script>
import NavBar from './components/layouts/NavBar.vue'
import Form from './components/layouts/CreateNewAnime.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    Form
  }
}
</script>


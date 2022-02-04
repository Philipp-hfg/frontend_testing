<template>
  <div id="app">
    <Header/>
    <Sidebar/>
    <BookPreview/>
    <AddBookForm/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Sidebar from './components/Sidebar.vue'
import BookPreview from './components/BookPreview.vue'
import AddBookForm from './components/AddBookForm.vue'

export default {
  name: 'App',
  components: {
    Header,
    Sidebar,
    BookPreview,
    AddBookForm
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2D2D2D;
}

body {
  margin: 0px;
}

</style>

<template>
  <div>
    <Navbar/>
    <div class="container">
      <router-view/>
    </div>
  </div>
</template>

<script>
import Navbar from './components/Navbar'
import 'materialize-css/dist/css/materialize.min.css'
import 'materialize-css/dist/js/materialize.min.js'


export default {
  name: 'app',
  components: {
    Navbar
  }
}
</script>

<style>

</style>

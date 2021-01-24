<template>
  <div id="app">
    <Nav></Nav>
    <router-view/>
  </div>
</template>

<script>
import Nav from './components/Navbar'
export default {
    components: { Nav }
}
</script>

<style >

</style>
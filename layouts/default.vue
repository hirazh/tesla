<template>
  <div>
    <Nav></Nav> 
    <nuxt/>
  </div>
</template>

<script>
import Nav from '../components/Nav.vue'

export default {
  components: {
    Nav
  }
}
</script>

<style>
* {
  border: 0;
  margin: 0;
  padding: 0;
}

</style>

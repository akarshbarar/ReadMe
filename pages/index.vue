<template>
  <div class="container">
    <Nav />
    <div></div>
  </div>
</template>

<script>
import Nav from '../components/Nav.vue'
export default {
  components: {
    Nav,
  },
  head() {
    return {
      title: 'ReadMe: Creative Way to create Readme file.',
    }
  },
}
</script>

<style scoped></style>

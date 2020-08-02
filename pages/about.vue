<template>
  <div>
    <h1 class="title text-center display-3 pt-4">
      <a href="/" class="text-dark">Arnas Boruchovas</a>
    </h1>

    <NavBar />
  </div>
</template>

<script>
import NavBar from '~/components/NavBar.vue'

export default {
  components: {
    NavBar
  }
}
</script>

<style>
.title {
  font-family: 'Roboto';
  font-weight: 500;
}

a {
  text-decoration: none !important;
}
</style>

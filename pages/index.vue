<template>
  <div>
    <h1 class="title text-center display-3 pt-4">
      <a href="/">Arnas Boruchovas</a>
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
  font-family: 'Roboto', sans-serif;
  font-weight: 500;
}

.title a {
  color: black;
}

a {
  text-decoration: none !important;
}
</style>

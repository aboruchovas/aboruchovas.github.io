<template>
  <div>
    <h1
      class="title text-center display-3 pt-4 animate__animated animate__headShake"
    >
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
  overflow: hidden;
}

.title a {
  color: black;
}

a {
  text-decoration: none !important;
}

@media only screen and (max-width: 768px) {
  .title {
    font-size: 3rem;
  }
}

/* https://coolors.co/f8b544-847996-88b7b5-a7cab1-f4ecd6 */
</style>

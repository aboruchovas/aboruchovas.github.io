<template>
  <div>
    <NavBar />
    <div class="container">
      <div>
        <div class="art-block">
          <h1 class="title">
            My work
          </h1>
        </div>
        <h2 class="subtitle">
          Some of the things I've worked on
        </h2>
      </div>
    </div>
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
.container {
  margin: 0 auto;
  min-height: 50vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Tahoma', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.art-block {
  background-color: #d8dee9;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding: 1em 0;
}

.links {
  padding-top: 15px;
}
</style>

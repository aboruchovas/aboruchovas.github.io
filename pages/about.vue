<template>
  <div>
    <h1 class="title text-center display-3 pt-4">
      <a href="/">Arnas Boruchovas</a>
    </h1>

    <div class="about p-5">
      <div>
        <p class="pt-4">
          Hi there! 👋
        </p>
        <p>
          I’m a third year Computer Science student at the 🎓 University of
          Sheffield, currently completing a summer internship at Tribepad.
        </p>
        <p>
          I’m passionate about designing and creating elegant solutions using 👨‍💻
          modern technologies.
        </p>
      </div>

      <div class="pt-5">
        <p>
          I'm also the Trips Officer 🚀 for hackSheffield, a society at the
          University of Sheffield ran by students. We organise a yearly
          hackathon open to students around the world, as well as visiting other
          hackathons!
        </p>
      </div>
    </div>

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
}

.title a {
  color: black;
}

.about {
  font-family: 'Roboto', sans-serif;
  font-size: 2.5em;
}

a {
  text-decoration: none !important;
}
</style>

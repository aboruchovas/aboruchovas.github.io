<template>
  <div>
    <h1 class="title text-center display-3 pt-4">
      <a href="/">Arnas Boruchovas</a>
    </h1>

    <div class="about p-5">
      <div>
        <p class="pt-4 pb-3">
          Hi there! 👋
        </p>
        <p class="pb-3">
          I’m a third year Computer Science student at the 🎓 University of
          Sheffield, currently completing a summer internship at Tribepad.
        </p>
        <p class="pb-3">
          I’m passionate about designing and creating elegant solutions using 👨‍💻
          modern technologies.
        </p>
        <p class="pb-3">
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
body {
  margin-bottom: 100px;
}

.title {
  font-family: 'Roboto', sans-serif;
  font-weight: 500;
}

.title a {
  color: black;
}

.about {
  font-family: 'Roboto', sans-serif;
  font-weight: 500;
  font-size: 2.5rem;
}

a {
  text-decoration: none !important;
}

@media only screen and (max-width: 768px) {
  .title {
    font-size: 3rem;
  }
  .about {
    font-size: 1.5rem;
    padding-top: 1.5rem !important;
  }
}
</style>

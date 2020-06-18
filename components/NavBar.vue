<template>
  <b-navbar type="dark" variant="info">
    <b-navbar-nav class="mx-auto">
      <b-nav-item href="/">About me</b-nav-item>
    </b-navbar-nav>
    <b-navbar-nav class="mx-auto">
      <b-nav-item href="/work">Work</b-nav-item>
    </b-navbar-nav>
    <b-navbar-nav class="mx-auto">
      <b-nav-item href="/contact">Contact</b-nav-item>
    </b-navbar-nav>
  </b-navbar>
</template>

<style>
.navbar {
  min-height: 75px;
}

.navbar.navbar-dark.bg-info {
  background-color: #e5e9f0 !important;
}

.nav-link {
  color: #434c5e !important;
  font-size: 1.25em;
}

.nav-link:hover {
  color: #313846 !important;
}
</style>

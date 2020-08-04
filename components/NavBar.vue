<template>
  <footer class="footer">
    <div class="container d-flex justify-content-between h-100">
      <a href="/about" class="text-white align-self-center">
        About
      </a>
      <a href="/contact" class="text-white align-self-center">
        Contact
      </a>
    </div>
  </footer>
</template>

<style>
.footer {
  font-family: 'Roboto', sans-serif;
  background-color: #88b7b5;
  position: fixed;
  bottom: 0;
  width: 100%;
  height: 80px;
}

.footer a {
  font-weight: 500;
  text-decoration: none !important;
  font-size: 3.5rem;
}

@media only screen and (max-width: 768px) {
  .footer a {
    font-size: 2.5rem;
  }
}
</style>

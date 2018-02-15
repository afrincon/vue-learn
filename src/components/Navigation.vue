<template>
  <div class="navbar-end">
    <router-link tag="a" to="/" class="navbar-item">
      Home
    </router-link>
    <router-link tag="a" to="/about" class="navbar-item">
      About
    </router-link>

    <router-link tag="a" to="/contact" class="navbar-item">
      Contact
    </router-link>

    <span class="navbar-item">
    <a class="button is-primary is-inverted">
      <span class="icon">
        <i class="fab fa-github"></i>
      </span>
      <span>login</span>
    </a>
    </span>
  </div>
</template>

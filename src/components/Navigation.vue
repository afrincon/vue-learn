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
    <a class="button is-primary is-inverted is-outlined">
      <span class="icon">
      </span>
      <span>login</span>
    </a>
    </span>
  </div>
</template>

<script>
export default {
  name: 'navigation',
};
</script>

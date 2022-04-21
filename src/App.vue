<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <!-- header -->
  <header>
    <div>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">Profile</RouterLink>
        <RouterLink to="/about">Skill</RouterLink>
        <RouterLink to="/about">Work</RouterLink>
        <RouterLink to="/about">Contact</RouterLink>
      </nav>
    </div>
  </header>

  <!-- body -->
  <RouterView />

  <!-- footer -->
</template>

<style>
@import '@/assets/base.css';

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;

  font-weight: normal;
}

nav {
  text-align: center;
  margin-left: -1rem;
  font-size: 1rem;

  padding: 1rem 0;
}

header {
  position: fixed;
  left: 0;
  top: 0;
  width: 100%;
}

a,
.green {
  text-decoration: none;
  color: hsla(160, 100%, 37%, 1);
  transition: 0.4s;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 4rem;
  border-left: 1px solid var(--color-border);
}

body {
  display: flex;
  place-items: center;
}
</style>

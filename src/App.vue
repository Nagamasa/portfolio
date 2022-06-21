<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <!-- header -->
  <div class="">
    <header>
      <div>
        <nav>
          <RouterLink to="/">Home</RouterLink>
          <RouterLink to="/profile">Profile</RouterLink>
          <RouterLink to="/about">Skill</RouterLink>
          <RouterLink to="/about">Work</RouterLink>
          <RouterLink to="/contact">Contact</RouterLink>
        </nav>
      </div>
    </header>

    <!-- body -->
    <main>
      <RouterView />
    </main>

    <!-- footer -->
  </div>
</template>

<style>
@import '@/assets/base.css';
@import url('https://fonts.googleapis.com/css?family=Roboto');

#app {
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
  width: 100vw;
  height: 50px;
  color: rgb(240, 245, 245);
  background-color: rgb(7, 7, 7);
} 

a {
  text-decoration: none;
  color: rgb(247, 248, 248);
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
  /* display: flex; */
  /* place-items: center; */
  background-color: rgb(151, 156, 156);
  font-family: Roboto;
}

main {
  padding-top:100px;
  z-index:-1;
}
</style>
